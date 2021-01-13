FROM node:15.0.0-alpine

WORKDIR /front

COPY ./src /front/src
COPY package.json /front/

RUN npm install

ENTRYPOINT ["npm","start"]