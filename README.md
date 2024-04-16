# Old MongoDB driver for Go

This is a drop-in replacement to `github.com/globalsign/mgo`.

## Installation

Add the following line to your project `go.mod` file:

```
replace github.com/globalsign/mgo => github.com/nexcode/mgo latest
```

and run:

```
go mod tidy
```

## Changes

- Fixed a critical bug where the driver ignored consistency settings
