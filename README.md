搭建 Shadowsocks-rust， V2ray+ Nginx + WebSocket 和 Reality, Hysteria2 代理脚本，支持 Debian、Ubuntu、Centos，并支持甲骨文ARM平台。

简单点讲，没域名的用户可以安装 Reality 和 hy2 代理，有域名的可以安装 V2ray+ Nginx + WebSocket 代理，各取所需。

运行脚本：

```
wget https://raw.githubusercontent.com/jiuub/v2ray-wss/main/tcp-wss.sh && bash tcp-wss.sh
```


WSS客户端配置信息保存在：
`cat /usr/local/etc/v2ray/client.json`

Shadowsocks客户端配置信息：
`cat /etc/shadowsocks/config.json`

Reality客户端配置信息保存在：
`cat /usr/local/etc/xray/reclient.json`

Hysteria2客户端配置信息保存在：
`cat /etc/hysteria/hyclient.json`

卸载方法如下：
https://1024.day/d/1296

**提醒：连不上的朋友，建议先检查一下服务器自带防火墙有没有关闭？**
