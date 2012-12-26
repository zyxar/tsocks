# TSOCKS #
## A transparent SOCKS proxying library, forked from http://tsocks.sourceforge.net ##

## Build ##

    ./configure --prefix=/opt
    make && sudo make install

## Features ##

- support for `TSOCKS_SERVER`, `TSOCKS_SERVER_PORT` and `TSOCKS_LOCAL` env settings.
- support for `--server`, `--server-port` and `--local` cmdline arguments.
- default `TSOCKS_PASSWORD`: null string.
