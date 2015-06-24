Docker Image for [wrk](https://github.com/wg/wrk)
====

How to use.
----

### setup

```console
$ git clone https://github.com/yokogawa-k/docker-wrk.git
$ cd docker-wrk
$ docker build -t yokogawa/wrk .
```

### help

```console
$ docker run --rm yokogawa/wrk
```

If you use `./run` script.

```console
$ ./run
```

### Performance test

```console
$ docker run --rm yokogawa/wrk  -t 2 -c 10 -d 10s --timeout 20 example.com
```

If you use `./run` script.

```console
$ ./run -t 2 -c 10 -d 10s --timeout 20 example.com
```

### use bash

```console
$ ./run bash
```
