FROM node:8.2
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY package.json /usr/src/app/
RUN npm install --production
COPY . /usr/src/app
EXPOSE 8081
ENV NODE_ENV production
CMD [ "npm", "start" ]