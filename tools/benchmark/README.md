# etcd/tools/benchmark

`etcd/tools/benchmark` is the official benchmarking tool for etcd clusters.

## Download
To get `etcd` from the `master` branch via `go get`:
```sh
go get github.com/coreos/etcd/tools/benchmark
```

## Install
```
# GOPATH should be set
go install -v $GOPATH/src/github.com/coreos/etcd/tools/benchmark
```
you can find it under  `$GOPATH/bin`

or
```
go build -o benchmark -a $GOPATH/src/github.com/coreos/etcd/tools/benchmark
```
