#frontend containerization
FROM node:latest

WORKDIR /app

COPY package*.json .

RUN "npm install"

EXPOSE 3000

CMD ["npm","run","dev"]
