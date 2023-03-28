# Caddyfile

一些自己的Caddyfile


## 首先启动go语言的http服务

```go
go run http-server.go
```

## 然后测试跨域或其他

目前仅有一个反向代理跨域的

run caddy
```
caddy run -c cors/Caddyfile
```

## 最后在浏览中打开index.html

打开开发者工具控制台查看反向代理