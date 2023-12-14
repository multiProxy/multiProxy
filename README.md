# Xray-core/sing-box 一键脚本快速安装


# 一、项目介绍

## 核心

- Xray-core
- sing-box

## 协议

> 以下均使用TLS，支持多种协议组合

- VLESS(Reality、Vision、TCP、WS、gRPC)
- VMess(TCP、WS)
- Trojan(TCP、gRPC)
- Hysteria2
- Tuic

## 功能

- [支持无域名版本的VLESS Reality搭建](https://www.v2ray-agent.com/archives/1680104902581)
- [支持多种分流用于解锁（wireguard、IPv6、任意门、DNS、VMess(ws)、SNI反向代理）](https://www.v2ray-agent.com/archives/ba-he-yi-jiao-ben-yu-ming-fen-liu-jiao-cheng)
- [支持批量添加CDN节点并配合ClashMeta自动优选](https://www.v2ray-agent.com/archives/1684858575649)
- 支持证书自动申请及更新
- [支持订阅以及多VPS组合订阅](https://www.v2ray-agent.com/archives/1681804748677)
- 支持批量新增端口
- 支持核心的升级以及回退
- 支持自主更换伪装站点
- 支持BT下载管理以及域名黑名单管理

# 二、使用指南

- [脚本快速搭建教程](https://www.v2ray-agent.com/archives/1682491479771)
- [垃圾VPS大救星，hysteria2最新协议一键搭建](https://www.v2ray-agent.com/archives/1697162969693)
- [Tuic V5性能提升及使用方法](https://www.v2ray-agent.com/archives/1687167522196)
- [Cloudflare优选IP、自动选择最快节点教程](https://www.v2ray-agent.com/archives/1684858575649)
- [脚本异常处理](https://www.v2ray-agent.com/archives/1684115970026)

# 三、线路推荐


# 四、安装使用

## 1.下载脚本

- 支持快捷方式启动，安装完毕后，shell输入【**vasma**】即可打开脚本，脚本执行路径[**/etc/v2ray-agent/install.sh**]

- Github

```
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/multiProxy/multiProxy/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh
```


## [2.脚本快速搭建教程](https://www.v2ray-agent.com/archives/1682491479771)

# 四、反馈和建议

> 如果您在使用过程中遇到任何问题或者有任何建议，欢迎在这里提交[issue](https://github.com/multiProxy/multiProxy/issues)
> ，或者[加入](https://t.me/technologyshare)这个电报群进行交流。

# 五、捐赠

> 感谢您对开源项目的关注和支持。如果您觉得这个项目对您有帮助，欢迎通过以下方式进行捐赠。


# 六、许可证

[AGPL-3.0](https://github.com/multiProxy/multiProxy/blob/master/LICENSE)
