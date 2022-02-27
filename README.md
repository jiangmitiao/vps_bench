


https://github.com/haydenjames/bench-scripts

```bash

wget -qO- bench.sh | bash

curl -s wget.racing/nench.sh | bash

(curl -s wget.racing/nench.sh | bash; curl -s wget.racing/nench.sh | bash) 2>&1 | tee nench.log

```


https://github.com/masonr/yet-another-bench-script

```bash

curl -sL yabs.sh | bash

wget -qO- yabs.sh | bash
```





```bash

systemctl stop firewalld.service

yum install -y wget && wget https://cdn.ipip.net/17mon/besttrace4linux.zip && yum install -y unzip && unzip besttrace4linux.zip && chmod +x besttrace && cp besttrace /usr/local/bin

# 北京联通
besttrace -g cn -q 1 -T 202.106.196.115

# 广东联通
besttrace -g cn -q 1 -T 210.21.4.130

# 广东电信
besttrace -g cn -q 1 -T 202.96.128.86

# 广东移动
besttrace -g cn -q 1 -T 211.136.17.107
```



## 下载

```bash
yum install -y epel-release && yum install -y nginx && systemctl start nginx && dd if=/dev/random of=/usr/share/nginx/html/test.bin count=102400 bs=1024

curl -Lo /dev/null -skw "%{speed_download}\n"  http://XXX/test.bin
```
