FROM node:14.17.1-alpine3.13
WORKDIR /app
COPY package.json ./
RUN npm install
EXPOSE 3000
CMD ["npm", "run", "dev"]