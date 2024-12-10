FROM node:alpine

WORKDIR /app/jira-clone/

EXPOSE 3000

COPY /jira-clone/package*.json ./

RUN npm install

COPY . .

CMD [ "npm", "run", "dev" ]