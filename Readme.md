# fileserve
A simple file service writed with go, like python `http.server`.

It will create file service in current directory.

# Installation
To install this package, you need to install Go and set your Go workspace first.

1. The first need Go installed (version 1.11+ is required), then you can use the below Go command to install fileserve.

```shell
$ go get -u github.com/jummyliu/fileserve
```

# Usage

```shell
$ fileserve -h
  -addr string
        addr (default "0.0.0.0")
  -h    help
  -port int
        port (default 8000)
```