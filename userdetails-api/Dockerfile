FROM node:14-slim

WORKDIR /usr/src/app

COPY ./package.json ./

COPY ./package-lock.json ./

RUN  npm install 

EXPOSE 8447

COPY . .

CMD ["npm", "start"]