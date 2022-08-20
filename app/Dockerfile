FROM node:16

# create workdir
WORKDIR /usr/src/app

COPY package*.json .

# install dep
RUN yarn install

# copy sources
COPY . .

# uncomment this, if you want to directly access node app
# EXPOSE 3000 

# run app
CMD npm run start