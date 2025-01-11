FROM node:15

WORKDIR /usr/src/app

COPY . .

RUN npm install axios
RUN npm install mysql

RUN npm install 

EXPOSE 3000

CMD [ "node", "index.js" ]