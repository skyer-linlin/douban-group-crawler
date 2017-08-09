利用 Node.js 实现爬虫，爬取了豆瓣西安租房小组最新回复的100条帖子的内容，再通过express将数据传到前端，展示在页面上，省去一个一个点开筛选租房信息的时间。作为 Node.js 新手的练手项目，项目十分简单，可以帮助新手理解简单的爬虫工作原理、前后端数据交互等知识点。
同时该项目也存在不完善的地方，欢迎大家提出意见和建议，我也会在学习过程中不断完善这个应用。

## 技术栈：
- 后台：express superagent cheerio async
- 前端：JQuery ajax

## 我的软件版本（2017.08）
Node.js v8.1.4

## 项目运行：

```
# 克隆到本地：
$ git clone

# 安装依赖：
$ git install

# 开启本地服务器
$ npm start
```
开启本地服务器后，打开 http://localhost:3000/app.html 就可以看到抓取到的数据展示页