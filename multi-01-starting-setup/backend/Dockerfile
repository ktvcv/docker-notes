FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8081

ENV MONGODB_USERNAME=root
ENV MONGODB_PASSWORD=secret

CMD ["node", "app.js"]