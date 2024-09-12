
原作者不更新了，导致后续无法使用。所以本人修复了部分BUG，现在依然可以安装。



OneClickDesktop–Linux系统一键安装桌面环境，并且可使用浏览器访问桌面

Github：https://github.com/Har-Kuun/OneClickDesktop

目前，本程序仅支持在Ubuntu 18.04/20.04 LTS以及Debian 10的64位操作系统上运行。您的服务器或者VPS最好是全新安装的系统，不带LAMP/LEMP等组件或cPanel/DirectAdmin/宝塔等用户面板。

您的服务器需要有外网IP地址。在安装之前，您需要解析一个域名（可以用三级域名或者一个免费域名）到您的服务器上。安装桌面环境需要至少1 GB的内存。

安装教程
可以使用sudo权限用户或root用户(不建议)登录服务器SSH，然后执行下面的命令即可。
中文安装方法：
wget https://github.com/love5461/ontime/blob/main/OneClickDesktop_zh-CN.sh && sudo bash OneClickDesktop_zh-CN.sh

英文安装方法：
wget https://raw.githubusercontent.com/Har-Kuun/OneClickDesktop/master/OneClickDesktop.sh && sudo bash OneClickDesktop.sh
