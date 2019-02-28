FROM node:latest
# Create app directory
RUN mkdir -p /usr/src/app
RUN npm install forever -g
WORKDIR /usr/src/app
# Bundle app source
EXPOSE 3000
CMD [ "npm", "start" ]