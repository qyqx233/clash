fork from `https://github.com/Dreamacro/clash`

## 修改记录

1. commt at 2020.3.28 增加了异常节点过滤功能，如果某代理节点(vmess...)返回特定的错误，则记录下来,URLTest的时候忽略掉这些节点(PS:我目前使用的是proxy-provider自动获取的节点,proxy-group选的是url-test,仅针对这种使用场景做了修改)

```
 modified:   adapters/outbound/base.go
 modified:   adapters/outboundgroup/urltest.go
 modified:   constant/adapters.go
 modified:   tunnel/tunnel.go
```


