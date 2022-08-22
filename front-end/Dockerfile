FROM node:16

WORKDIR /app
COPY . .

RUN npm i && npm run build

RUN mkdir -p var/ww/html
RUN mv build/* /var/ww/html


WORKDIR / 
RUN rm -rf /app