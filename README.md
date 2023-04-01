# What's My IP?

本仓库主要用来列举一些可用来获取公网 IP 地址的站点域名。

主要是供编程获取使用，当然，用浏览器或命令行查看也是可以的。

由于出口线路的不同以及是否开启 代理/VPN 等，不同的方式获取的公网 IP 可能不一样。可以同时获取多个，按多的算。

列表按友好、易用性等递减排序。

## 列表

* <https://ifconfig.me/>

  - 附加：浏览器信息
  - 格式：纯文本
  - 缺点：不支持 IPv6

- <https://ifconfig.co/>

  - 附加：地理位置、运营商、ASN、端口测试、地图
  - 格式：JSON、纯文本
  - 说明：浏览器直接打开是网页，curl 可以直接拿到 IP：`curl ifconfig.co`

- <https://ipinfo.io/ip>

  - 格式：纯文本
  - 缺点：不支持 IPv6

- <https://ipecho.net/plain>

  - 格式：纯文本
  - 缺点：不支持 IPv6

- <https://api.ip.sb/ip>

  - 格式：纯文本、JSON

* <https://wtfismyip.com/>，<https://myip.wtf/>

  - 附加：地理位置、运营商
  - 格式：[XML](https://wtfismyip.com/xml)、[JSON](https://wtfismyip.com/json)、[纯文本](https://wtfismyip.com/text)

- <https://ip-api.com/docs/api:json>

  - 附加：国家、地理位置、时区、组织、运营商等
  - 格式：JSON、纯文本、XML、CSV
  - 缺点：免费用户不能使用 HTTPS，1 分钟有 45 次请求的限制

- <http://ipv4.icanhazip.com/>，<http://icanhazip.com/>

  - 格式：纯文本

- <https://api.ipify.org/>

  - 格式：纯文本
  - 缺点：不支持 IPv6

- <http://myip.com.tw/>

  - 格式：HTML

- <https://myip.ipip.net/>

  - 附加：地理位置、运营商
  - 格式：纯文本

- <http://ip138.com/>

  - 附加：地理位置
  - 格式：HTML
  - 缺点：命令行/编程不友好
