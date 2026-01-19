# proto
proto文件
### hello
生成命令：
protoc  -I api  --go_out=gen --go_opt=paths=source_relative  --go-grpc_out=gen --go-grpc_opt=paths=source_relative  api/hello/v1/hello.proto