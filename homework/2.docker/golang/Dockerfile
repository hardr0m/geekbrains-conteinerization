FROM golang:1.19.0-bullseye
RUN mkdir /build
ADD go.mod go.sum main.go /build/
WORKDIR /build
RUN go build
