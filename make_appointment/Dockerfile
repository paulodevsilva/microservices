# FROM node:14-alpine

# # COPY package.json /usr/src/app/package.json
# # COPY ./package*.json ./
# # RUN yarn 

# # COPY . /usr/src/app
# # # CMD yarn start:dev

# # create the directory inside the container
# WORKDIR /usr/src/app

# # copy the package.json files from local machine to the workdir in container
# COPY package.json /usr/src/app/package.json
# COPY ./package*.json ./


# # run npm install in our local machine

# RUN yarn

# COPY . /usr/src/app
# # copy the generated modules and all other files to the container
# COPY . .

# # our app is running on port 5000 within the container, so need to expose it


# # the command that starts our app
# # CMD ["yarn", "start:dev"]
# # CMD yarn start:dev



FROM node:14-alpine


# WORKDIR /usr/src/app

# COPY package*.json ./
# RUN yarn

# COPY . .

# CMD [ "yarn", "start:dev" ]


WORKDIR /usr/src/app

COPY package.json /usr/src/app/package.json
RUN yarn

COPY . /usr/src/app