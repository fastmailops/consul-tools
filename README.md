# consul-tools

Some useful tools that run on top of [Consul](https://consul.io/)

* consul-lock - run a program under lock (like [`consul lock`](https://www.consul.io/docs/commands/lock.html), but without an intermediate shell and with working kill signal propagation)
* consul-kvsync - keep a KV tree in sync with another (like [consul-replicate](https://github.com/hashicorp/consul-replicate) but with proper timeouts to detect network failures)

## credits and license

Copyright (c) 2015 Robert Norris. MIT license. See LICENSE.
