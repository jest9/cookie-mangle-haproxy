# cookie mangler via haproxy

Quick and easy cookie encryption/decryption at haproxy reverse proxy via lua.

# setup
This uses the [openssl library](https://github.com/zhaozg/lua-openssl) from luarocks to handle the actual encryption.

Install luarocks following the steps from https://luarocks.org/ and then install the openssl package.
 
```
sudo luarocks install openssl
```

Make sure to install in the same directory for the version of lua your haproxy installation is using.
