# redis

[![Build Status](https://travis-ci.org/gomodule/redis.svg?branch=master)](https://travis-ci.org/gomodule/redis)
[![GoDoc](https://godoc.org/github.com/shupkg/redis?status.svg)](https://godoc.org/github.com/shupkg/redis)

redis is a [Go](http://golang.org/) client for the [Redis](http://redis.io/) database.

## Features

- A [Print-like](http://godoc.org/github.com/shupkg/redis#hdr-Executing_Commands) API with support for all Redis commands.
- [Pipelining](http://godoc.org/github.com/shupkg/redis#hdr-Pipelining), including pipelined transactions.
- [Publish/Subscribe](http://godoc.org/github.com/shupkg/redis#hdr-Publish_and_Subscribe).
- [Connection pooling](http://godoc.org/github.com/shupkg/redis#Pool).
- [Script helper type](http://godoc.org/github.com/shupkg/redis#Script) with optimistic use of EVALSHA.
- [Helper functions](http://godoc.org/github.com/shupkg/redis#hdr-Reply_Helpers) for working with command replies.

## Documentation

- [API Reference](http://godoc.org/github.com/shupkg/redis)
- [FAQ](https://github.com/gomodule/redis/wiki/FAQ)
- [Examples](https://godoc.org/github.com/shupkg/redis#pkg-examples)

## Installation

Install redis using the "go get" command:

    go get github.com/gomodule/redis

The Go distribution is redis's only dependency.

## Related Projects

- [rafaeljusto/redismock](https://godoc.org/github.com/rafaeljusto/redismock) - A mock library for redis.
- [chasex/redis-go-cluster](https://github.com/chasex/redis-go-cluster) - A Redis cluster client implementation.
- [FZambia/sentinel](https://github.com/FZambia/sentinel) - Redis Sentinel support for redis
- [mna/redisc](https://github.com/mna/redisc) - Redis Cluster client built on top of redis

## Contributing

See [CONTRIBUTING.md](https://github.com/gomodule/redis/blob/master/.github/CONTRIBUTING.md).

## License

redis is available under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).
