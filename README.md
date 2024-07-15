# Clash-for-linux

## 1.linux下的clash安装包，汉化文件
+ [Clash-for-linux安装包](https://drive.google.com/file/d/1Xf6-Huv2p4aLN1uenR-EPiHoZVQcktH0/view?usp=drive_link)
+ [汉化文件](https://drive.google.com/file/d/1EYwcqMXEYpA0BGIVCKTlhyzyBq6J6oZo/view?usp=drive_link)
## 2.使用方法
+ 解压
```bash
tar -xzvf Clash-*...
```
+ 汉化
    * 用下载的app.asar替换掉Clash-*.../resources/app.asar
+ 授权限
```bash
mv Clash-*... Clash
cd Clash
sudo chmod +x cfw
./cfw
```
+ 此时将有一个可视化的界面
  + 配置中填入订阅链接，后下载
  + 不会用订阅链接的看这个：[魔戒 15块130G不限时间](https://mojie.app/register?aff=LVmo5wx7)
+ 设置代理端口
  + Ubuntu-->设置-->网络-->网络代理-->手动
```json
http:127.0.0.1:7890
https:127.0.0.1:7890
ftp:127.0.0.1:7890
socks:127.0.0.1:7890
忽略主机：localhost, 127.0.0.0/8, ::1
```

* 设置不用终端启动
    * clash-->主页-->开机自启-->重启ubuntu
