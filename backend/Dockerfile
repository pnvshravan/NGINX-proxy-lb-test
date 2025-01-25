FROM node:20-alpine

WORKDIR /server

COPY package*.json .

RUN npm ci --omit=dev

COPY . .
EXPOSE 5000

CMD ["npm", "start"]