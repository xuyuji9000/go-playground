The goal of this document is to demonstrate how to use protobuf in golang.


- Compile protobuf object: `protoc --go_out=. *.proto`

- Run go code: `go run main.go person.pb.go`

- Build go code: `go build main.go person.pb.go`

- Add **protoc-gen-go** to dependency: `go install google.golang.org/protobuf/cmd/protoc-gen-go`


# Reference

1. [ Go Protocol Buffer Tutorial](https://tutorialedge.net/golang/go-protocol-buffer-tutorial/)

