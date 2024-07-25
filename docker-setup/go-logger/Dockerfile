# docker-setup/go-logger/Dockerfile

FROM golang:1.19-alpine

WORKDIR /go-logstash-json

COPY . .

RUN go build -o out/logger *.go

CMD [ "./out/logger" ]