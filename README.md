# shippy-cli-consignment

This is part code of Microservices in Golang using go-micro

## Structures

- [shippy-service-consignment](https://github.com/repodevs/shippy-service-consignment) Is Consignment Service
- [shippy-service-vessel](https://github.com/repodevs/shippy-service-vessel) Is Vessel Service
- [shippy-cli-consignment](https://github.com/repodevs/shippy-cli-consignment) Is Client that Consume Consignment Service (_this code_)

## How to use

**This code using go 1.14 and using `go modules`**

### Install deps

```sh
go mod download
go mod vendor
```

### Run the service

```sh
go run main.go
```

### Build service to binary

```sh
go build -o cli *.go
```
