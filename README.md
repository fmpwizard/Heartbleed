Heartbleed
==========

A checker (site and tool) for CVE-2014-0160.

Public site at http://filippo.io/Heartbleed/

Tool usage: `./Heartbleed example.com:443`

Please note that the code is a bit of a mess, not exactly release-ready.

## Install

You will need Go 1.2.x, otherwise you get `undefined: cipher.AEAD` and other errors

```
go get github.com/FiloSottile/Heartbleed
go install github.com/FiloSottile/Heartbleed

```
