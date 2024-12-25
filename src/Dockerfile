# Use a imagem base do Ubuntu
FROM node:20.10.0-alpine3.18

WORKDIR /app

COPY package*.json .
RUN npm install 


COPY . .

EXPOSE 8080

# Comando para iniciar a aplicação
ENTRYPOINT [ "node","server.js"]