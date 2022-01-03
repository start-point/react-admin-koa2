### react-admin-koa2 (后端 用的koa2)

🎉安装依赖

(注: 如果安装后 运行 出现错误 可能就是包依赖没有下载完全 你可以通过npm i 去安装一下 )

```bash
$ yarn
```

🎉项目启动

```bash
$ yarn start
  or
$ npm start
```

## 项目结构

```s
|-- core      
    |-- http-excption     -- 请求可能出现的错误 (尚未补全)
    |-- init   		-- 路由批量处理
|-- middlewares     -- 自定义中间件存放
|-- router     		-- 接口存放
|-- utils     		-- 工具类 (目前只存放了 数据库连接)
|-- app.js
```

--数据库用的是 mysql

数据库的 库名 admin_cms 在 utils文件里的 db.js 能看到 你需要建一个一样的库
在utils 文件夹下面有 user.json 和 userInfo.json 这是俩个数据库表 将他导入你新建好的 admin_cms 库中 
然后 运行 umi-admin 文件夹
账号: chen 密码: 123456