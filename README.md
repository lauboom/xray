#xray

##介绍

xray-wp.sh

xray安装脚本，适用于centos7

调用xray官方安装脚本

使用vless+tcp+xtls模式

回落使用nginx，配置wordpress

先更新
```bash
yum install epel-release -y
yum update -y
```
再执行
```bash
bash <(curl -Ls https://raw.githubusercontent.com/lauboom/xray/main/xray-wp.sh)
```
