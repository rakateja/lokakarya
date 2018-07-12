# Order mini-application
This is just a small application to demonstrate how to write http application using Go.

## Requirements
- Go
- MySQL

## Installation
```
$ go get .
$ mysql -h localhost -u raka -p < migration.sql
$ go build -o order-server
$ ./order-server
```