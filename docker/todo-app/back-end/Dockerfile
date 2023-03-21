FROM node:14

WORKDIR /app

EXPOSE 3001

COPY . .

ADD ./node_modules.tar.gz /app

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
