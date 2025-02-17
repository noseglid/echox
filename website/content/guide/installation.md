+++
title = "Installation"
description = "Installing Echo"
[menu.main]
  name = "Installation"
  parent = "guide"
weight = 1
+++

## Prerequisites

- [Install](https://golang.org/doc/install) Go
- [Set](https://golang.org/doc/code.html#GOPATH) GOPATH

## Using [go get](https://golang.org/cmd/go/#hdr-Download_and_install_packages_and_dependencies)

```sh
$ cd <PROJECT IN $GOPATH>
$ go get -u github.com/labstack/echo/...
```

## Using [dep](https://github.com/golang/dep)

```sh
$ cd <PROJECT IN $GOPATH>
$ dep ensure -add github.com/labstack/echo@^3.1
```

## Using [glide](http://glide.sh)

```sh
$ cd <PROJECT IN $GOPATH>
$ glide get github.com/labstack/echo#~3.1
```

## Using [govendor](https://github.com/kardianos/govendor)

```sh
$ cd <PROJECT IN $GOPATH>
$ govendor fetch github.com/labstack/echo@v3.1
```

Echo follows [semantic versioning](http://semver.org) managed through GitHub
releases, specific version of Echo can be installed using a [package manager](https://github.com/avelino/awesome-go#package-management).
