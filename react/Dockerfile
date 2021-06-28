FROM node:latest

ADD . /usr/src/app

WORKDIR /usr/src/app

RUN yarn install

ENTRYPOINT [ "yarn", "start" ]