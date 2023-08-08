FROM docker.io/library/golang:1.21

COPY highcpu.go .

RUN go build -o highcpu highcpu.go

CMD ["./highcpu"]
