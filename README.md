### tiny DNS resolver

This is a command line program that makes DNS queries. There's a version in bash and a version in Go.


### how to run it

The bash version:

```
bash resolve.sh example.com.
```

The go version:

```
go run resolve.go example.com.
```

### other versions

* Rust: https://github.com/kmkaplan/tiny-resolver-rs
* Elixir: https://www.bortzmeyer.org/files/tiny-resolver.tar
* Python: https://www.bortzmeyer.org/files/tiny-resolver.py

### blog post

You can read more about how this works in [A toy DNS resolver](https://jvns.ca/blog/2022/02/01/a-dns-resolver-in-80-lines-of-go/)
