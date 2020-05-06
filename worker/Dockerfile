FROM node:alpine

WORKDIR "/app"

COPY ./package.json ./

RUN apk add nodejs

RUN apk add npm

RUN npm i -g nodemon

RUN npm install 

COPY . .

CMD ["npm", "run", "start"]