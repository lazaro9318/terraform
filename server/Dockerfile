FROM --platform=linux/amd64 node:11.15

WORKDIR /work/

COPY ./package.json /work/package.json

RUN npm install

COPY . /work/

CMD node .