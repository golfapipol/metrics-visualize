FROM node:12-alpine
WORKDIR /app
ADD package.json package-lock.json /app/
RUN npm install
ADD index.js .
CMD node index.js