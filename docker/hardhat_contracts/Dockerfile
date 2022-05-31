FROM node:16.3-alpine
RUN apk update && apk --no-cache --virtual build-dependencies add \
  python3 \
  make \
  g++ \
  git
RUN  rm -rf node_modules \
  && yarn

WORKDIR /contracts