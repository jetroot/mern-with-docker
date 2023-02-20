FROM node:16-alpine3.16

WORKDIR /server

COPY . .

RUN npm i -f

ENTRYPOINT [ "npm", "start" ]