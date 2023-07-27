## micro
Highly concurrent mall system built on go-zero

## Features
- [x] RPC
- [x] Web
- [x] Redis
- [x] Mysql
- [x] JWT
- [x] Swagger
- [x] Log
- [x] Graceful shutdown

## Quick start

```shell
# install
go mod download

# build
make build

# run
./micro
```
## port

### API

| server name    | port  |
| -------------- | ------|
| api bff        | 8001  |


### RPC
| server name    | port  |
| -------------- | ------|
| user rpc       | 9001  |
| product rpc    | 9002  |
| order rpc      | 9003  |
