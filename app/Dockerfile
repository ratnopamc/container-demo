FROM node:16

LABEL MAINTAINER=ratnopamc@yahoo.com

WORKDIR /usr/src/app

# Copy app to /src
COPY package*.json ./

# Install app and dependencies into /src
RUN npm install

COPY . .

EXPOSE 8080

CMD [ "node", "server.js" ]