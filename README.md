# go-socks5

Provides the `socks5` package that implements a [SOCKS5](http://en.wikipedia.org/wiki/SOCKS).
SOCKS (Secure Sockets) is used to route traffic between a client and server through
an intermediate proxy layer. This can be used to bypass firewalls or NATs.

### Feature


The package has the following features:
- Support socks5 server
- Support TCP/UDP and IPv4/IPv6
- Unit tests
- "No Auth" mode
- User/Password authentication optional user addr limit
- Support for the CONNECT command
- Support for the ASSOCIATE command
- Rules to do granular filtering of commands
- Custom DNS resolution
- Custom goroutine pool
- buffer pool design and optional custom buffer pool
- Custom logger

