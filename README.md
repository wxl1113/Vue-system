>一个Vue + nodejs +MongoDB 后台管理系统。到现在大概5天的时间，先写个总结。

>Vue负责前端页面的展示，路由功能交给Vue-router。

>Express不写路由，只负责写api接口，使用mongoose与MongoDB数据库进行数据交互，实现前后端解耦。

## 技术

**前端**

vue2 + vuex + vue-router + iview + axios/vue-axios + ES6

**后端**

nodejs + express +mongoose

**工具**
webpack

**数据库**
MongoDB 

# 项目预览

本地需要安装mongodb数据库

## 客户端client

```
//打开目录
 cd client

//安装依赖包
 npm i

//启动本地客户端服务器
npm run dev 

//打包文件
npm run build
```

## 服务端server

```
 cd server

 npm i

//开启服务器
 npm run start 

```


## 功能


- [x] 用户、文章、评论实现增删改查；
- [x] 基于JWT的登陆验证、状态留存；
- [x] 使用muler实现上传图片功能；
- [x] 多分类管理（曾删改）；


## 更新计划
- [ ] 优化分类，与各模块进行交互；
- [ ] 首页模块；
- [ ] 数据统计模块；






## 目录结构

**客户端目录**
```
|____client
| |____.babelrc
| |____index.html
| |____package.json
| |____README.md
| |____src
| | |____App.vue
| | |____assets    
| | | |____500007055.jpg
| | |____common
| | | |____getdata.js
| | |____components
| | | |____ClassifyTree.vue
| | | |____Form.vue
| | | |____Layout.vue
| | | |____Login.vue
| | |____main.js
| | |____my-theme
| | | |____index.less
| | |____routes.js
| | |____store
| | | |____index.js
| | |____views
| | | |____Ablum.vue
| | | |____Article.vue
| | | |____Classify.vue
| | | |____Comment.vue
| | | |____Home.vue
| | | |____Upload.vue
| | | |____User.vue
| |____webpack.config.js
|____LICENSE
|____README.md
```

**服务端目录**
```
|____server
| |____app.js
| |____bin
| | |____www
| |____controllers
| | |____ArticleCtrl.js
| | |____CateCtrl.js
| | |____CommentCtrl.js
| | |____UploadCtrl.js
| | |____UserCtrl.js
| |____MIME.js
| |____models
| | |____ArticleModel.js
| | |____CateModel.js
| | |____CommentModel.js
| | |____UploadModel.js
| | |____UserModel.js
| |____other.js
| |____package.json
| |____public
| | |____images
| | |____javascripts
| | |____stylesheets
| | | |____style.css
| |____README.md
| |____routes
| | |____article.js
| | |____cate.js
| | |____comment.js
| | |____index.js
| | |____upload.js
| | |____users.js
| |____server.js
| |____upload
| | |____ablums
| | | |____avatar-1495266654995.png
| | | |____avatar-1495266808125.png
| | | |____avatar-1495266970632.jpg
| |____views
| | |____error.ejs
| | |____index.ejs
|____UPDATE.md
```


## 项目地址

[Github地址](https://github.com/wxl1113/Vue-system)
