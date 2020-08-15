# HoshinoBot_docker
本项目为[HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot/) 的docker-compose一键部署模板, 使用[MiraiGo](https://github.com/Mrs4s/MiraiGo) 作为宿主。

# 部署方法

1. 前往(https://github.com/Mrs4s/go-cqhttp/releases)下载对应版本go-cqhttp，解压后将go-cqhttp可执行文件放置到本项目的go-cqhttp文件夹中
2. 在本项目根目录下 git clone https://github.com/Ice-Cirno/HoshinoBot.git
3. 修改./go-cqhttp/config.json中对应qq号和密码，并且配置好HoshinoBot。
4. sudo docker-compose up -d
5. sudo docker attach 生成的实例名, 输入验证码并完成登录验证