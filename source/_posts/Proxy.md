---
title: Agency
date: 2018-10-07 15:23:48
tags: Proxy
categories: Proxy
declare: true
toc: false
updated:
---
# vps搭建ss/ssr参考教程

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=100% height=86 src="//music.163.com/outchain/player?type=2&id=1308233736&auto=1&height=66"></iframe>

[参考1](https://leziqu.com/3001.html)
[参考2](https://blog.csdn.net/weixin_42172676/article/details/81082295)
[参考3](https://www.freeluffy.com/vultr-vps-ss/)
[雨落无声](https://www.zhujiboke.com/)
<!-- more -->

# SSR单端口管理脚本
[https://leziqu.com/3001.html](https://leziqu.com/3001.html)

	yum -y install wget
	wget -N --no-check-certificate https://softs.fun/Bash/ssr.sh && chmod +x ssr.sh && bash ssr.sh
	#备用
	wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh

# SSR多用户管理脚本[https://github.com/FunctionXJB/SSR-Bash-Python](https://github.com/FunctionXJB/SSR-Bash-Python)
[参考1](http://www.nbmao.com/archives/3052)
[参考2](https://blog.csdn.net/sinat_33479559/article/details/80778438)

	yum -y install wget yum install perl
	
安装&更新

	wget -q -N --no-check-certificate https://raw.githubusercontent.com/hotmop/SSR-duoyonghu/master/install.sh && bash install.sh
卸载

	wget -q -N --no-check-certificate https://raw.githubusercontent.com/hotmop/SSR-duoyonghu/master/install.sh && bash install.sh uninstall

# 客户端

## SS
* [https://github.com/shadowsocks/shadowsocks-windows/releases](https://github.com/shadowsocks/shadowsocks-windows/releases)
* [https://github.com/shadowsocks/shadowsocks-android/releases](https://github.com/shadowsocks/shadowsocks-android/releases)

## SSR
* [https://github.com/shadowsocksrr/shadowsocksr-csharp/releases](https://github.com/shadowsocksrr/shadowsocksr-csharp/releases)
* [https://github.com/shadowsocksr-backup/shadowsocksr-android/releases](https://github.com/shadowsocksr-backup/shadowsocksr-android/releases)

## SSTap
* [SSTap][https://www.sockscap64.com/zh-hans//]
* [https://www.sockscap64.com/zh-hans//](https://www.sockscap64.com/zh-hans//)
* [https://www.sockscap64.com/zh-hans/homepage/](https://www.sockscap64.com/zh-hans/homepage/)

---