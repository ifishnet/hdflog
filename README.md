hdflog
======

[![Build Status](http://img.shields.io/travis/ifishnet/hdflog.svg)](https://travis-ci.org/ifishnet/hdflog)
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](http://copyfree.org)
[![GoDoc](https://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/ifishnet/hdflog)

package hdflog defines a logger interface and provides a default implementation
of a subsystem-aware leveled logger implementing the same interface.

## Installation

```bash
$ go get github.com/ifishnet/hdflog
```

## GPG Verification Key

All official release tags are signed by Conformal so users can ensure the code
has not been tampered with and is coming from the ifishnet developers.  To
verify the signature perform the following:

- Download the public key from the Conformal website at
  https://opensource.conformal.com/GIT-GPG-KEY-conformal.txt

- Import the public key into your GPG keyring:
  ```bash
  gpg --import GIT-GPG-KEY-conformal.txt
  ```

- Verify the release tag with the following command where `TAG_NAME` is a
  placeholder for the specific tag:
  ```bash
  git tag -v TAG_NAME
  ```

## License

package hdflog is licensed under the [copyfree](http://copyfree.org) ISC
License.
