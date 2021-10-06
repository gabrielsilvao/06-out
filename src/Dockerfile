FROM node:14.16.1-alpine3.13
WORKDIR /app
COPY package.json ./
COPY package-lock.json ./
RUN npm install
COPY . .
EXPOSE 8008
CMD ["node","app.js"]
