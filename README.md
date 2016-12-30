# ShadowsocksX2

Current version is 2.3

This project is base on [ShadowsocksX-NG](https://github.com/qiuyuzhou/ShadowsocksX-NG) with different implment details.


## Requirements

### Runtime

- Mac OS X 10.11 +

### Building

- XCode 8.0+
- cocoapod 1.0.1+
- Homebrew 0.9.9
- Run "sh build.sh" to configrue after git clone.

## Download

From [here](https://github.com/shadowsocks/ShadowsocksX-NG/releases/)

## Fetures

- Embad shadowsocks-libev (lastest)
- Update PAC by download GFW List from github.
- Show QRCode for current server profile.
- Scan QRCode from screen.
- Auto launch at login.
- User rules for PAC.
- Support One Time Auth
- An advance preferences panel to configure:
    - Local socks5 listen address.
    - Local socks5 listen port.
    - Local socks5 timeout.
    - If enable UDP relay.
    - GFW List URL.
- Manual specify network service profiles which would be configure the proxy.
- Could reorder shadowsocks profiles by drag & drop in servers preferences panel.


## Different from orignal ShadowsocksX

- Support configure Socks5 Listen Adress and Port.
- Support [One Time Auth](https://shadowsocks.org/en/spec/one-time-auth.html).

## Diferences with ShadowsocksX-NG

- Run ss-local as in app thread mode which share the same lifecycle with GUI.
- After you quit the app, The ss-local will be terminated.

## TODO List

- [x] Embed the http proxy server [privoxy](http://www.privoxy.org/), [get it](https://homebrew.bintray.com/bottles/privoxy-3.0.26.sierra.bottle.tar.gz).

## License

- The project is released under the terms of GPLv3.
