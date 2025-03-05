# left un taged ":name" the default will be :latest

FROM node:19.6-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY ./src .

CMD ["node", "index.js"]

# basic docker build comand using '.' to grab everything
# docker build -t buildName:<version numbner i.e 0 or 1> .
