## 简介

[cyb-element-admin](https://github.com/jd-cyb/cyb-element-admin) 是一个后台集成解决方案，它基于 [vue](https://github.com/vuejs/vue) 和 [element](https://github.com/ElemeFE/element)。它使用了最新的前端技术栈，内置了i18国际化解决方案，动态路由，权限验证，提炼了典型的业务模型，提供了丰富的功能组件，它可以帮助你快速搭建企业级中后台产品原型。

<div align="center">
  <img src="./demo.png" alt="demo">
</div>

## 开发

```
# 全局安装CYB

npm install -g cyb-cli
```

```bash
# 克隆项目

git clone https://github.com/jd-cyb/cyb-element-admin

# 安装依赖

cd cyb-element-admin
npm install

# 启动服务

cyb dev
```

> cyb会帮助我们自动打开浏览器进入研发环境。

## 发布
```bash
# 发布

cyb dist

# 本地测试

cyb test
```

## 其他

本项目源码使用了[vue-element-admin](http://panjiachen.github.io/vue-element-admin)，用于演示塞伯坦（cybertron）CYB前端模块化工程构建工具强大的工程构建能力。

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2018 CYB前端小组
