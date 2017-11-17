# jumpserver
Jumpserver is a open source proxy server, developed by Python and Django, aim to help companies to efficiently user, assets, authority and audit management

Jumpserver是一款使用Python, Django开发的开源跳板机系统, 助力互联网企业高效 用户、资产、权限、审计 管理

Feature 功能

Auth 统一认证
CMDB 资产管理
Perm 统一授权
Audit 审计
LDAP AUTH 支持LDAP认证
Web terminal
SSH Server
Environment 环境

Python 2.6
Django 1.6
Install 安装


直接克隆使用
./server.sh start 启动即可



Usage 使用

  1. Visit http://$HOST:8000 (访问 http://你的主机IP:8000 来访问 Jumpserver)

  2. Click left navigation visit Applications-Terminal and accept coco and luna register (点击左侧 应用程序接受 Coco和Luna的注册)

  3. Click Assets-Admin user, Create admin user (添加 管理用户)

Click Assets-System user, Create system user (添加 系统用户)
  5. Click Assets-Asset, Add a asset (添加 资产)

  6. Click Perms-Asset permission, Add a perm rule (添加授权规则，授权给admin)

  7. Connect ssh server coco (连接 ssh server coco)

  ssh -p2222 $USER@$Host
  8. Visit web terminal server Luna, click server test connection (访问 访问Luna，点击左侧服务器连接测试)

  http://$HOST:5000
