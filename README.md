# w-zkc: 用 Vue 写一个 UI 组件库

w-zkc UI 是一个好用的 UI 框架，提供了一些常用组件，适合 PC 端和移动端使用。

组件：按钮、输入框、网格、布局、Toast、Tabs、Popover、手风琴

## 介绍

这是我在学习 Vue 的过程中尝试写的一个 UI 框架（造的轮子），希望对你有用。

## 开始使用

1. 添加 CSS 样式
   使用本框架前，请在 CSS 中开启 border-box

   ```
   *，*::before,*::after{ box-sizing: border-box }
   ```

   IE 8 及以上浏览器支持此样式。

2. 引入 w-zkc

   ```
   import { Button } from 'w-zkc'
   import 'w-zkc/dist/index.css'

   export default {
       name: 'app',
       components: {
           'w-button': Button
       }
   }
   ```

## 文档

[官方文档](https://keyingfu0.github.io/w-zkc/)

## 联系方式

邮箱：461354358@qq.com
