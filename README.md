# SYNOPSIS

A Node.js adapter for the Operator Framework

# DESCRIPTION

[Operator Framework][0] uses a simple uri-based protocol for brokering messages
between the render process and the main process. Messages are sent over `stdin`
and `stdout`. This module is an optional, higher level adapter for this protocol
that should make Node.js developers feel more at-home. Check out the [this][1]
repo for some examples about how to use it.

[0]:https://operatorframework.dev
[1]:https://github.com/socketsupply/op-examples
