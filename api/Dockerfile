FROM node:16.6.2

RUN mkdir -p /app
WORKDIR /app

COPY package.json .
# RUN npm install graphql
RUN npm i
COPY . .
# RUN npm run seedDb

EXPOSE 4001

CMD ["npm", "start"]
