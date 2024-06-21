FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV MONGO_USER = "root"
ENV MONGO_PASSWORD = "example_pass"

CMD ["npm", "start"]