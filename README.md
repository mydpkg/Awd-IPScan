# Awd-IPScan
CTF AWD主机扫描工具使用教程

```
root@root: $ ./Awd-IPScan_darwin_amd64 -h
Usage of ./Awd-IPScan_darwin_amd64:
  -c string
    	CTF中C段遍历，例如：127.0.0.{},www.baidu-{}.com
  -d	默认使用http访问探测，此配置使用dns探测
  -f string
    	主机地址文件默认为空，一行一个或,分割
  -i string
    	默认为127.0.0.1主机，例如：127.0.0.1,www.google.com
  -l	默认不显示日志，此配置显示日志
  -p string
    	默认80端口，例如：80,8080,999/1-65535
  -s	默认使用http，此配置打开使用https
```

注意：本工具并不适用端口扫描，端口扫描未配置多线程
