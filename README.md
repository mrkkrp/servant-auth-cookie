# servant-auth-cookie

[![Build Status](https://travis-ci.org/mrkkrp/servant-auth-cookie.svg?branch=master)](https://travis-ci.org/mrkkrp/servant-auth-cookie)

## Description

Authentication via encrypted client-side cookies, inspired by
[client-session](https://hackage.haskell.org/package/clientsession)
library by Michael Snoyman and based on ideas of the paper
["A Secure Cookie Protocol"](http://www.cse.msu.edu/~alexliu/publications/Cookie/cookie.pdf)
by Alex Liu et al.

## Status

The library is under development.

API might change a little bit, but the core can be considered stable.
The further changes will mostly reflect security and performance improvements.

## Demo

Type `cabal run example` to launch a local server with cookie
authentication at 8080 port. It's a simple three-paged web site that
will show the private page only if a correct cookie is presented. For
valid accounts see `usersDB` list in `example/Main.hs`.
