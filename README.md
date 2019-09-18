# aliddns shell脚本

## 安装
ubuntu/debian
```
apt-get install wget curl dnsutils openssl cron -y
wget -N --no-check-certificate https://raw.githubusercontent.com/lllvcs/aliddns/master/aliddns.sh
chmod +x ./aliddns.sh
```

centos
```
yum install wget curl bind-utils openssl cron -y
wget -N --no-check-certificate https://raw.githubusercontent.com/lllvcs/aliddns/master/aliddns.sh
chmod +x ./aliddns.sh
```

## 设置定时任务
```
crontab -e
*/1 * * * * bash /root/aliddns.sh
```
