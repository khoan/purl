# Purl

Parallel curl: downloads files in parts in parallel, then assembles parts into files.

# Caveat

1. Server must support range request.
2. Only tested on Mac OS.

# Usage

```sh
$ curl https://raw.githubusercontent.com/khoan/purl/master/bin/install | sh
$ cd ~/Downloads
$ purl http://range-server.com/path/to/file local-file

# should any part fail, purl again
$ purl http://range-server.com/path/to/file local-file
```

# Install

TODO wiki to gory details

# Uninstall

```sh
$ curl https://raw.githubusercontent.com/khoan/purl/master/bin/uninstall | sh
```
