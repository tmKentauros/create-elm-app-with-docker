FROM node:10.16.0

RUN yarn global add create-elm-app@3.2.1
RUN yarn global add elm-verify-examples@4.0.0
RUN yarn global add node-sass-chokidar@1.3.5

RUN yarn global add elm-format@0.8.2
RUN yarn global add elm-analyse@0.16.4

ENV ELM_DEBUGGER=false

WORKDIR /elm

EXPOSE 3000
