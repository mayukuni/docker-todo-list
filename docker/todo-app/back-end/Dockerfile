
FROM node:14-alpine AS build
WORKDIR /back-end
ADD node_modules.tar.gz ;
EXPOSE 3001
COPY . .
CMD [ "npm", "start" ]