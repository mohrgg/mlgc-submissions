FROM node:18.20.3

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

ENV PORT=3000

ENV MODEL_URL=https://storage.googleapis.com/mlgc-submission-rifqiardhani/submissions-model/model.json

CMD ["npm", "start"]
