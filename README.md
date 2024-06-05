# @fe-hl/admin-design-vue

## 本项目是基于 Vite、vue3、typescript、element-plus 组件二次封装的组件库，能够快速配置出表单、列表...，能够快速的构建管理页面，解放你的双手，摸鱼神器

## 安装依赖大于等于`[element-plus ^2.2.16]`

## npm 安装

```sh
npm i @fe-hl/admin-design-vue -s
```

## 注册组件

```js
import { createApp } from 'vue'
import AdminDesignVue，{ DialogForm, Form ... } from "@fe-hl/admin-design-vue";
import "@fe-hl/admin-design-vue/lib/index/style.css";
// 注册所有组件
app.use(AdminDesignVue)
// 单个注册
app.use(Form)
app.use(DialogForm)

<ad-dialog-form .../>
<ad-form .../>
```

### 使用说明文档[点击打开链接](https://fe-hl.github.io/document/)

```js
https://fe-hl.github.io/document/
```

