### 安装hexo-cli
```
npm install -g hexo-cli
```
### yarn安装依赖
 
### 新建一个网站。如果没有设置 folder ，Hexo 默认在目前的文件夹建立网站。
```
hexo init [folder]
```
### 新建一篇文章。如果没有设置 layout 的话，默认使用 _config.yml 中的 default_layout 参数代替。如果标题包含空格的话，请使用引号括起来。
```
hexo new [layout] <title>
```
### 生成静态文件。
```
hexo generate
```
-d, --deploy	文件生成后立即部署网站
-w, --watch	监视文件变动
该命令可以简写为
```
hexo g
```
### 发表草稿。
```
hexo publish [layout] <filename>
```
### 启动服务器。默认情况下，访问网址为： http://localhost:4000/。
```
hexo server
```
-p, --port	重设端口
-s, --static	只使用静态文件
-l, --log	启动日记记录，使用覆盖记录格式

### 部署网站。
```
hexo deploy
```
-g, --generate	部署之前预先生成静态文件