# HYUploadServer
An Hyper Http file upload server

## 高性能HTTP文件上传服务器

## Features
- 大文件HTTP上传，文件大小不受限制
- HTTP上传断点续传支持
- 支持HTML5浏览器上传进度显示
- 支持IE8及以下浏览器上传进度显示
- 支持1000个实时并发连接
- 无缓冲即时写入
- 支持查看客户在线连接 用 http://ip:port/lists 
- Compatible with Chrome, FireFox, Safari, IE,Opera and Edge

## Installation
- 第一步：解压文件到一个硬盘目录，例如d:\hyfileserver

- 第二步：修改配置文件 <br>
        修改d:\hyfileserver\conf\config.xml文件里的目录设置 <br>
        将所有 dir= 变量指向的目录修改为硬盘上实实在在存在的目录 <br>
        
- 第三步：安装服务 <br/>
        执行cmd打开命令行窗口按步骤输入以下命令： <br/>
        d:  <br/>
        cd hyfileserver<br/>
        HYFileServer.exe -i  <br/>   
        
- 第四步：启动服务 <br/>
        打开系统的服务管理器，找到Hyper Http Upload Service服务启动它。
                
- 第五步：在浏览器里输入 http://127.0.0.1:8021 查看 <br>
        如果能够出现网页说明安装成功 <br>
        点击 一个上传文件连接 按钮试试上传一个文件。 <br>
        如果要在其它机器访问上传服务器页面，请将127.0.0.1用安装服务器的计算机的IP地址取代。 <br>
        如果外部机器还不能访问，看看防火墙是否关闭。 <br>
        端口8021可以在config.xml修改。
- 第六步：如果要进一步了解上传服务器，请查看 d:\hyfileserver\doc\文件上传服务器使用手册.pdf 文件

- Linux
  执行  <br>
  ./hyupdsrv  <br>
  如果要作为守护进程，执行  <br>
  ./hyupdsrv -d

## Contact
- QQ:2760529539
- Mail: wenshui2008@126.com

## Design
See (doc)






