FROM node:20
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npn install 
ENV MONGO="true" \
    MONGO_URL="mongodb://mongodb:2707/catalogue"
CMD ["node","server.js"]