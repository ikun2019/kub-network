FROM node:20.10.0-alpine3.19
WORKDIR /workspace

COPY package.json .
RUN npm install

COPY . .

CMD npm run start