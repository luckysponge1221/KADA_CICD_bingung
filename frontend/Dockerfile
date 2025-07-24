FROM node:18-alpine
WORKDIR /fullstack_cicd
COPY package.json .
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm", "start"]
