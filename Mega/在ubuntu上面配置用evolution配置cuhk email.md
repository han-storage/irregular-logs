# 在ubuntu上面配置用evolution配置cuhk email

1. 下载evolution
2. 安装evolution-ews
3. 编辑-accounts-邮件账号-添加-mail acount
4. 标识：需要的信息，填姓名和邮件地址
5. 服务器类型：exchange网络服务
6. 主机url改称https://outlook.office365.com/EWS/Exchange.asmx
7. 检查支持的类型-OAuth2
8. Override xxx
9. 跟着这个找到tenant和application ID：https://wiki.gnome.org/Apps/Evolution/EWS/OAuth2， 剩下那个空着
10. 狂点确定，完成

