FROM node:10.10-alpine

RUN mkdir -p /src/app

WORKDIR /src/app

COPY . /src/app

RUN yarn install --ignore-engines

RUN yarn global add nodemon

EXPOSE 3000

CMD [ "npm", "run", "startdev" ]