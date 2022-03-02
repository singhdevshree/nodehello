FROM node:17
# Create app directory
WORKDIR /usr/src/redisapp

COPY package*.json ./
RUN npm install

COPY . .
CMD ["npm","start"]
