# Go implementation of Mark Adler's zran

This project is a Go implementation of
[Mark Adler's zran](https://github.com/madler/zlib/blob/ef24c4c7502169f016dcd2a26923dbaf3216748c/examples/zran.c)
that tries to remain in synchronization with
[upstream's flate](https://go.googlesource.com/go/+/e39e965e0e0cce65ca977fd0da35f5bfb68dc2b8/src/compress/flate/).
This project builds on the work of Timothy Palpant [^1] which itself builds on
the work of Patrick Baxter [^2].

Branch `source` contains this README file.

Branches starting with `upstream/` are upstream branches filtered with
[git-filter-repo](https://github.com/newren/git-filter-repo).

Other branches are the Go zran implementation over upstream branches.

[^1]: https://github.com/timpalpant/gzran/tree/master

[^2]: https://github.com/peebs/gzran/tree/gzran
