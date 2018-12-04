# PAY.JP for Go

[![Build Status](https://travis-ci.org/payjp/payjp-go.svg?branch=master)](https://travis-ci.org/payjp/payjp-go)

## Installation

    go get -u github.com/vibridi/payjp-go
    
## Notes

This is a fork of the original PayJP library to fix a retrocompatibility issue after a recent update to the endpoint called by the `Token.Create` method.
This fix is NOT meant to be used in production systems. For further information, please see [this issue](https://github.com/payjp/payjp-go/issues/10)

## Documentation

Please see PayJP's official [documentation](http://pay.jp/docs/api).
