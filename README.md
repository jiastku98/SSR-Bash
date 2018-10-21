# SSR-Bash
SSR多用户管理

# 安装 #


###Debian/Ubuntu系列

    apt-get update -y && apt-get install unzip zip -y && apt-get install wget -y && wget -N --no-check-certificate https://raw.githubusercontent.com/jiastku98/Easy-SSR-Bash-Python-The-Final/master/ssr.zip && unzip ssr.zip && cd SSR* && bash install.sh


###CentOS系列

    yum update -y && yum install unzip zip -y && yum install wget -y && wget -N --no-check-certificate https://raw.githubusercontent.com/jiastku98/Easy-SSR-Bash-Python-The-Final/master/ssr.zip && unzip ssr.zip && cd SSR* && bash install.sh

## 卸载 ##

    cd /root/SSR-Bash-Python-The-Final && bash uninstall.sh

## 自检 ##

    cd /root/SSR-Bash-Python-The-Final && bash self-check.sh
