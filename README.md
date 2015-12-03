go-tid
======

Easy to test in the docker container.

Description
-----------

Usage
-----

```sh
$ tid -parallel 4 -verbose lb proxy db web api
```

Install
-------

To install, use `go get`:

```sh
$ go get -d github.com/linyows/tid
```

Contribution
------------

1. Fork ([https://github.com/linyows/tid/fork](https://github.com/linyows/tid/fork))
1. Create a feature branch
1. Commit your changes
1. Rebase your local changes against the master branch
1. Run test suite with the `go test ./...` command and confirm that it passes
1. Run `gofmt -s`
1. Create a new Pull Request

Author
------

[linyows](https://github.com/linyows)
