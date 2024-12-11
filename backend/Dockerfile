FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=sujeet
ENV MONGODB_PASSWORD=magic
ENV MONGODB_URL=mongodb
ENV MONGODB_NAME=goals-dev

CMD ["npm", "start"]