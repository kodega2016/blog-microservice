FROM node:alpine
WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY . .
EXPOSE 4002
CMD ["npm","run","start"]
