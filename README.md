# EasyGost
A script for using gost easily

国内nat用的话，先修改hosts，以便访问github
```
nano /etc/hosts
```
将下面两行加到最后保存。
140.82.114.4 github.com
199.232.68.133 raw.githubusercontent.com

先安装
wget --no-check-certificate -O gost.sh https://raw.githubusercontent.com/xxhjkl/EasyGost/master/gost.sh && chmod +x gost.sh && ./gost.sh
再次运行本脚本只需要输入
./gost.sh
