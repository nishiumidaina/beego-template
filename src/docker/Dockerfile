FROM golang:1.18.0-alpine

ENV ROOT /go
ENV CGO_ENABLED 0

WORKDIR ${ROOT}

RUN apk update && apk add --no-cache git