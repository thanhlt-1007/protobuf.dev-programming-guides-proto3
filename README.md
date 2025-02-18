# protobuf.dev-programming-guides-proto3-

- Language Guide (proto 3)

- Reference: https://protobuf.dev/programming-guides/proto3/

## gvm

```sh
gvm install go1.24.0
gvm use go1.24.0
```

## protoc

```sh
sudo apt install -y protobuf-compiler
protoc --version # libprotoc 29.3
```

## protoc-gen-go

```sh
go install google.golang.org/protobuf/cmd/protoc-gen-go@1.36.5
protoc-gen-go --version # protoc-gen-go v1.36.5
```

## protoc --go_out

```sh
protoc --go_out=. protos/your_proto.proto
```

