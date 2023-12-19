FROM node:alpine
#LABEL authors="user"
WORKDIR /app
COPY package.json ./
RUN npm install
COPY ./ ./
CMD ["npm", "start"]