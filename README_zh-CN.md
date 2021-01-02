<p align="center">
    <a href="http://www.form-create.com">
        <img width="200" src="http://file.lotkk.com/form-create.png">
    </a>
</p>

# form-create V2

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/xaboy/form-create)
[![github](https://img.shields.io/badge/Author-xaboy-blue.svg)](https://github.com/xaboy)
[![version](https://badge.fury.io/js/@form-create%2Fcore.svg)](https://www.npmjs.com/package/@form-create/core)
[![npm](https://img.shields.io/npm/dt/@form-create/core.svg)](https://www.npmjs.com/package/@form-create/core)
[![document](https://img.shields.io/badge/Doc-welcome-red.svg)](http://www.form-create.com/v2/)

**form-create 是一个可以通过 JSON 生成具有动态渲染、数据收集、验证和提交功能的表单生成器。并且支持生成任何 Vue 组件。结合内置 17 种常用表单组件和自定义组件，再复杂的表单都可以轻松搞定。**

## 支持

- **iViewUI 2.13.0+**
- **iViewUI 3.x**
- **iViewUI 4.x**
- **ElementUI 2.8.2+**
- **Ant-design-vue 1.5.3+**

如果您有适合 form-create 的表单组件, 欢迎[点击这里留言](https://github.com/xaboy/form-create/issues/124)

> 如果对您有帮助，您可以点右上角 "Star" 支持一下 谢谢！本项目还在不断开发完善中,如有任何建议或问题[请在这里提出](https://github.com/xaboy/form-create/issues/new)
> 本项目 QQ 讨论群[28963712](https://jq.qq.com/?_wv=1027&k=54aKUVw)

> [更新日志](http://www.form-create.com/v2/guide/update.html)

- **预览**

![demo1](https://raw.githubusercontent.com/xaboy/form-create/dev/images/demo-live3.gif)

<details>
<summary><b>更多</b></summary>

- **操作表单**

![demo2](https://raw.githubusercontent.com/xaboy/form-create/dev/images/demo-live2.gif)

- **`group` 组件**

![demo3](https://raw.githubusercontent.com/xaboy/form-create/dev/images/demo-group.gif)

- **`control` 配置项**

![demo2](https://raw.githubusercontent.com/xaboy/form-create/dev/images/demo-live4.gif)

</details>

## 文档

<p>
    <a href="http://www.form-create.com/v2/">
        <strong>简体中文</strong>
    </a>
    <a href="http://www.form-create.com/en/v2/">
        <strong>English</strong>
    </a>
</p>

## 包说明

| 包名                        | 说明                                                             |
| --------------------------- | ---------------------------------------------------------------- |
| @form-create/iview          | [iview 版本](http://form-create.com/v2/iview/)                   |
| @form-create/iview4         | [iView V4 版本](http://form-create.com/v2/iview/)                |
| @form-create/element-ui     | [ElementUI 版本](http://form-create.com/v2/element-ui/)          |
| @form-create/ant-design-vue | [Ant-design-vue 版本](http://form-create.com/v2/ant-design-vue/) |

## 示例

- [CRMEB 客户管理+电商管理系统](https://gitee.com/ZhongBangKeJi/CRMEB) ([演示站](http://demo25.crmeb.net) 账号：demo 密码：crmeb.com)

- [实战案例](https://github.com/HeyMrLin/fc-demo) ([演示站](http://jeekweb.pro/form-create-demo))

- [使用生成器生成](https://jsrun.net/NQhKp/edit)

- [使用 json 生成](https://jsrun.net/NQhKp/edit)

- [各种示例](https://jsrun.net/user/xaboy)

<details>
<summary><b>图例</b></summary>

![https://raw.githubusercontent.com/xaboy/form-create/dev/images/sample110.jpg](https://raw.githubusercontent.com/xaboy/form-create/dev/images/sample110.jpg)

</details>

## 安装

iview 2.x|3.x

```shell
npm install @form-create/iview
```

iview 4.x

```shell
npm install @form-create/iview4
```

elementUI

```shell
npm install @form-create/element-ui
```

ant-design-vue

```shell
npm install @form-create/ant-design-vue
```

## 引入

**CDN:**

iview

```html
<!-- import Vue.js -->
<script src="//vuejs.org/js/vue.min.js"></script>
<!-- import stylesheet -->
<link rel="stylesheet" href="//unpkg.com/iview/dist/styles/iview.css" />
<!-- import iView -->
<script src="//unpkg.com/iview/dist/iview.min.js"></script>
<!-- import form-create/iview -->
<script src="//unpkg.com/@form-create/iview/dist/form-create.min.js"></script>
```

elementUI

```html
<!-- import Vue.js -->
<script src="//vuejs.org/js/vue.min.js"></script>
<!-- import stylesheet -->
<link
  rel="stylesheet"
  href="https://unpkg.com/element-ui/lib/theme-chalk/index.css"
/>
<!-- import element -->
<script src="https://unpkg.com/element-ui/lib/index.js"></script>
<!-- import form-create/element -->
<script src="//unpkg.com/@form-create/element-ui/dist/form-create.min.js"></script>
```

ant-design-vue

```html
<!-- import Vue.js -->
<script src="//vuejs.org/js/vue.min.js"></script>
<!-- import stylesheet -->
<link
  href="https://unpkg.com/ant-design-vue@1.5.3/dist/antd.min.css"
  rel="stylesheet"
/>
<!-- import moment -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.24.0/moment.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.24.0/locale/zh-cn.js"></script>
<!-- import ant-design-vue -->
<script
  defer
  src="https://unpkg.com/ant-design-vue@1.5.3/dist/antd.js"
></script>
<!-- import form-create -->
<script src="//unpkg.com/@form-create/ant-design-vue/dist/form-create.min.js"></script>
```

**NodeJs:**

iview

```js
import formCreate from "@form-create/iview";
Vue.use(formCreate);
```

ElementUI

```js
import formCreate from "@form-create/element-ui";
Vue.use(formCreate);
```

ant-design-vue

```js
import formCreate from "@form-create/ant-design-vue";
Vue.use(formCreate);
```

## 使用

```html
<form-create
  ref="fc"
  v-model="fApi"
  :rule="rule"
  :option="option"
></form-create>
```

NodeJs

```javascript
import { maker } from "form-create";
export default {
  data() {
    return {
      fApi: {},
      model: {},
      //表单生成规则
      rule: [
        maker.input("商品名称", "goods_name"),
        maker.date("创建时间", "created_at"),
      ],
      //组件参数配置
      option: {
        //表单提交事件
        onSubmit: function(formData) {
          alert(JSON.stringify(formData));
        },
      },
    };
  },
  mounted: function() {
    this.model = this.fApi.model();
  },
};
```

Browser

```javascript
new Vue({
  el: "#app1",
  data: {
    fApi: {},
    model: {},
    rule: [
      formCreate.maker.input("商品名称", "goods_name"),
      formCreate.maker.date("创建时间", "created_at"),
    ],
    option: {
      onSubmit: function(formData) {
        alert(JSON.stringify(formData));
      },
    },
  },
  mounted: function() {
    this.model = this.fApi.model();
  },
});
```

## 示例

下载项目

```sh
$ git clone https://github.com/xaboy/form-create.git
$ cd form-create
```

安装依赖

```sh
$ npm run bootstrap
```

查看 Iview 2.x|3.x 示例

```sh
$ npm run dev:iview
```

查看 Iview 4.x 示例

```sh
$ npm run dev:iview4
```

查看 ElementUI 示例

```sh
$ npm run dev:ele
```

查看 ant-design-vue 示例

```sh
$ npm run dev:antd
```

## 感谢

[时光弧线](https://github.com/shiguanghuxian) | [wxxtqk](https://github.com/wxxtqk) | [williamBoss](https://github.com/williamBoss) | [HeyMrLin](https://github.com/HeyMrLin) | [djkloop](https://github.com/djkloop) | [JetBrains](https://www.jetbrains.com/?from=form-create)

## 捐赠

![donation.jpg](https://raw.githubusercontent.com/xaboy/form-create/dev/images/donation.jpg)

## 联系

##### email : xaboy2005@qq.com

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2018-present xaboy
