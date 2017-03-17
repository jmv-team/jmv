![Alt text](https://avatars2.githubusercontent.com/u/26159884?v=3&s=200)

# jmv [![jmv](https://img.shields.io/npm/v/jmv.svg?style=flat-square)](https://www.npmjs.org/package/jmv) [![NPM downloads](https://img.shields.io/npm/dm/jmv.svg?style=flat-square)](https://npmjs.org/package/jmv) 

Mobile web UI Components based on Vue@2.x

## 文档

- [中文文档](docs/README.md)

## 演示

[Demo地址](http://demo.jr.jd.com/finance/mobile/base/jmv/1.0.9/index.html)

## 安装

```bash
$ npm install jmv --save
```

如果您还没有构建`vue`项目，不放试试使用[jmv-cli](https://github.com/jmv-team/jmv-cli)

[快速开始传送门](docs/QuickStart.md)

## 使用

修改`src/components/Hello.vue`如下：

```html
<template>
    <div class="hello">
        <h1>{{ msg }}</h1>
        <p>It's a webpack&vue&vuex&vue-router project.</p>
        <list :title="'Tabs:'">
            <list-item :title="'Tab'" arrow></list-item>
        </list>
    </div>
</template>

<script>
    import {List, ListItem} from 'jmv';
    export default {
        name: 'hello',
        data () {
            return {
                msg: 'Welcome to use jmv to build your Vue.js App'
            }
        },
        components: {
            List,
            ListItem
        }
    }
</script>
```

## 开发进度

- ~~ActionSheet~~
- Address
- ~~Checkbox~~
- :white_medium_square: Dialog
- ~~Form~~
- ~~List~~
- :white_medium_square: Loading
- ~~Overlay~~
- ~~Radio~~
- ~~Tab~~
- ~~Toast~~

## 贡献

- [McChen](https://github.com/ChenJiaH)

- [Eastwinter](https://github.com/Eastwinter)

- [wanzhichao](https://github.com/wanzhichao)

- 如果您也想参与进来，请遵循开发原则

## 更新日志

v1.0.9

- 正式投入使用
- 已初步拥有`11`个基础组件

## 协议

MIT
