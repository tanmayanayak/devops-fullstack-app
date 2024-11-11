FROM golang:1.19
WORKDIR /app
COPY . .
RUN go get ./...
EXPOSE 8080
CMD ["go", "run", "main.go"]
