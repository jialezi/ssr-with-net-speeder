# shadowsocksR with net-speeder
这是一个ShadowsocksR Docker
## 启动方式

```
docker run -d --name ssr-with-net-speeder -p 8989:8989 jialezi/ssr-with-net-speeder -s 0.0.0.0 -p 8989 -k jaz -m rc4-md5 -o http_simple -O auth_sha1

```


## Arukas.io 启动

```
镜像 : jialezi/ssr-with-net-speeder
启动命令(CMD) ：-s 0.0.0.0 -p 8989 -k RUYO.net -m rc4-md5 -o http_simple -O auth_sha1
```



## SS镜像
https://github.com/jialezi/ss-with-net-speeder
