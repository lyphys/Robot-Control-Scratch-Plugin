# ScratchSerial
a demo for scratch extension about serial communication 

## 

## 环境依赖安装

node可以在https://nodejs.org/en/download/下载安装

serialport组件在node安装成功后，只需要通过命令行输入npm install -g seiralport即可，-g是指全局安装（安装在系统目录），如果不喜欢全局安装，只需要在当前程序的server目录中输入npm install seiralport，安装完成后会自动在项目中创建一个node_modules文件夹，将需要的库及其依赖库下载进去。

（这种方法炸windows下安装提示不成功）



node串口操作-serialport
依赖插件：serilaport

安装命令：npm install serialport -save



## 启动服务

程序使用了Nodejs做了个简单的服务器，实现功能。其实，也不用对node很了解，只要可以搭建一个本地bs服务器并且调用串口即可，本人只是电脑刚好有这个环境，就用了node，具体程序可以看源码。本程序使用只需要在本机安装node和serialport组件即可，在项目目录下使用命令行输入：node server.js即可。



