FROM node:alpine

LABEL maintainer="prithviBytes"

WORKDIR /app

COPY ./package*.json ./

RUN npm install

COPY . .

EXPOSE 3000