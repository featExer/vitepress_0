# page two

markdown grammer 介绍

在 github 风格基础上进行了增强

[home](/index)

## toc

[[toc]]

## 表格

| Tables        |      Are      |  Cool |
| ------------- | :-----------: | ----: |
| col 3 is      | right-aligned | $1600 |
| col 2 is      |   centered    |   $12 |
| zebra stripes |   are neat    |    $1 |

## 图片

![An image](./cat1.jpg)

## 转义为 Emoji

:100:

## Custom Containers

::: tip this is tip
This is a tip
:::

::: warning this is warning
This is a warning
:::

::: danger this is dander
This is a dangerous warning
:::

## Code Blocks

### Syntax Highlighting 语法高亮

所谓高亮就是以颜色区分词性

采用了 prism 包，详细[支持的语言类型](https://prismjs.com/#languages-list)

```js{1,4,6-7}
export default { // Highlighted
  data () {
    return {
      msg: `Highlighted!
      This line isn't highlighted,
      but this and the next 2 are.`,
      motd: 'VitePress is awesome',
      lorem: 'ipsum',
    }
  }
}
```

### Import Code Snippets 引入代码片段

<<< @/snippets/clip1.js{1,4,6-7}

## vue 功能的使用（暂时忽略）
