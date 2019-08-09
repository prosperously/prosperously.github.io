---
title: hexo建站教程
date: 2019-02-18 21:43:04
tags:
---


# hexo建站教程
1. 下载安装 `Git` `node.js` 
   设置环境变量

2. 把 `npm` 的镜像切换到 `cnpm`
```
npm install -g cnpm --registry=https://registry.npm.taobao.org
```

3. 下载并安装 `hexo` 客户端
```
cnpm install -g hexo-cli
```

4. 初始化一个项目
```
hexo init blog
```

5. 进入项目目录
   编辑 `_config.yml` 修改参数

6. 新建一个博文，并编辑博文
```
hexo new post 博文名称
```

7. 生成博客静态文件并映射到本地4000端口
```
hexo g
hexo s
```