# go-proto-grpc

Platzi course for go protobuffers and grpc architecture

## Compiling your Student Protobuffer

To compile your protos use the following command:

`protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative proto/student.proto`
