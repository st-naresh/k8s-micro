FROM node:8
MAINTAINER naresh


WORKDIR /app
COPY . .

RUN npm install express
RUN npm install

EXPOSE 8080

#Runs in development Mode
CMD ["npm", "start"]
