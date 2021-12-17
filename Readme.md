# 图书管理系统
## 目录结构
```
.
├─.idea
│  ├─artifacts
│  └─libraries
├─lib
├─META-INF
├─out   //输出目录
├─src   //源目录
│  ├─main
│  │  ├─java    //源目录
│  │  │  └─com
│  │  │      └─scu
│  │  │          └─libMgr
│  │  │              ├─bean         //实体类
│  │  │              ├─controller   //控制层（servlet）
│  │  │              ├─dao          //持久化层（与数据库交互）
│  │  │              │  └─impl      //dao接口的实现
│  │  │              ├─service  //服务层
│  │  │              └─utils    //工具
│  │  └─resources   //源 资源目录
│  └─test
│      ├─java       //测试源目录
│      └─resources  //测试资源目录
└─web
    ├─assets    //前端模板
    └─WEB-INF
        ├─classes
        └─lib

```