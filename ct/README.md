This is a cpoy of https://github.com/google/certificate-transparency-go
at revision 5cfe585726ad9d990d4db524d6ce2567b13e2f80.

Run `patch -p 0  -i ct/zcrypto_6ca0710425ec3df5e265e21ecde68a3a8db176bc_changes.diff`
to apply diff patch to starting revision

below is the original readme:

This is the really early beginnings of a certificate transparency log
client written in Go, along with a log scanner tool.

You'll need go v1.1 or higher to compile.

# Installation

This go code must be imported into your go workspace before you can
use it, which can be done with:

    go get github.com/google/certificate-transparency/go/client
    go get github.com/google/certificate-transparency/go/scanner
    etc.

# Building the binaries

To compile the log scanner run:

    go build github.com/google/certificate-transparency/go/scanner/main/scanner.go

# Contributing

When sending pull requests, please ensure that everything's been run
through ```gofmt``` beforehand so we can keep everything nice and
tidy.
