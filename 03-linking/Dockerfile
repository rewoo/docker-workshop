FROM ubuntu

RUN apt-get update
RUN apt-get install -y nodejs npm

ADD app /app

WORKDIR app

RUN npm install

CMD nodejs index.js
