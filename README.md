# 每天更新geoip_cn和geosite_cn

该项目旨在提供每天更新的 geoip_cn 和 geosite_cn 文件，以供相关系统及软件（如 Openwrt、Mosdns）使用。

## 描述

geoip_cn 和 geosite_cn 是用于网络代理软件的 IP 地址和域名数据库。该项目每天自动从v2ray-rules-dat获取最新的数据文件，并解包出geoip_cn 和 geosite_cn 文件。

### 更新说明

若文件相同则保持，若有变化则每天12：05分左右推送！
