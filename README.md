# Python_Blog

使用python3写的blog程序，代码基于[廖雪峰的python3教程结尾的实战内容](http://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/001432170876125c96f6cc10717484baea0c6da9bee2be4000)
做了一些修改并完善了某些功能。

## 依赖的第三方库

- jinja2
- aiomysql
- aiohttp
- markdown2
- watchdog（开发环境使用）
- pygments
- [pygments css](https://github.com/richleland/pygments-css)

## 增加修改的主要功能

1. 文章分类功能
2. 本地评论管理中可以直接跳转到相应评论处
3. 用户信息页面
4. 图片上传功能
5. 可选使用Disqus评论系统
6. 使用JSON格式配置文件，并支持注释
7. 完善程序退出机制，手工退出不会报错
8. 代码高亮，gfm风格的markdown代码块

上线效果[www.cashqian.net](http://www.cashqian.net)
