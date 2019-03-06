# linux FAQ
## 服务端开启ssh
安装ssh：sudo apt-get install openssh-server
开启：sudo /etc/init.d/ssh start
# 设置开机自动启动ssh服务
sudo update-rc.d ssh defaults
sudo update-rc.d ssh enable
