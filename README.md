# grpc-federation
Try out gRPC Federation

## Preparation
### Install `Buf`
```sh
brew install bufbuild/buf/buf
```

### Update dependencies to download the grpc-federation proto files
```sh
buf mod update proto
```

## Use gRPC Federation
```sh
buf generate
```
