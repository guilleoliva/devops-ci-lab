FROM node:4.4
EXPOSE 8080

MAINTAINER José Ricardo Pla <joseripla@gmail.com>

RUN npm install redis

COPY server.js .
CMD node server.js
