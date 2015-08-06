# StaticPageDec
利用grunt静态页面开发，无需安装浏览器插件，文件修改时可自动刷新浏览器

## 使用方法

1. 根据你的系统下载安装[node.js(0.12.x)](https://nodejs.org/download/)
2. 克隆下来 `git clone git@github.com:jungor/StaticPageDev` 或者直接在右下方点击下载
3. 进入StaticPageDev文件夹，打开命令行，执行 `npm install`
4. 编写静态文件，注意html文件直接放在public文件夹内；注在html意css/js文件的引用使用相对路径比如```<link rel="stylesheet" href="css/style.css">```
5. 写完代码后在命令行运行 `grunt live`, 在浏览器打开网址 `http://localhost:8000`，即可查看所有静态页面;若有index.html文件会默认显示页面
6. 浏览器显示的静态页面若在编辑器有所修改，会自动刷新
