# management-system-server

# 注意事项：电脑内需安装mongoDB
1、下载链接：https://www.mongodb.com/download-center/community
2、安装选项：选custom  最后一步把Install MongoDB Compass的默认勾选去掉
3、配置mongDB：在MongoDB所在盘下的根目录创建一个data文件夹，并在data文件夹里创建一个db文件夹
然后打开cmd，进入到MongoDB的bin目录下，输入mongod --dbpath c:/data（如果报错就输入./mongod --dbpath c:/data）
在开一个cmd窗口，cd到 mongodb的bin目录下面，然后输入mongo，启动服务
4、将material-management-platform（前端代码）、material-management-server（服务器端代码）分别用vscode（其他的编译器也可以）打开，进行以下操作


# material-management-platform（前端代码）文件内操作
## Project setup
```
1、打开终端（vscode内是ctrl+~）npm install
```

### Compiles and hot-reloads for development
```
2、npm run serve
```
3、终端上的地址ctrl+鼠标左键在浏览器打开

4、页面表格内暂时无数据，点击增加按钮添加数据


# material-management-server（服务器端代码）文件内操作
```
npm run start
```




