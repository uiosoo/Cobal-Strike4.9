# Cobal-Strike4.9
工具保存

1.将zip包上传到kali，解压文件
  unzip CobaltStrike4.9.zip -d CobaltStrike4.9

赋予执行权限
  cd CobaltStrike4.9
  chmod +x teamserver  
  chmod +x TeamServerImage

3. 启动服务端
## 第一个参数为服务的IP地址，虚拟机直接写本机IP就行 ## 第二个参数为客户端连接密码
  ./teamserver 192.168.10.10 123456

4. 在windows上启动客户端

Alias随便填
host为服务端的ip地址
port默认端口为50050，如果自行修改的填写自己指定的port
user默认为neo
password输入启动服务端时指定的密码
