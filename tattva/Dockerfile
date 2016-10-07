FROM mhart/alpine-node:latest

RUN npm install -g http-server

COPY index.html .

CMD ["http-server","--port","8080"]
