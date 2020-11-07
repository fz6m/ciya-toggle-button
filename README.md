# ciya-toggle-button

纯 css 实现 QQ 呲牙表情 checkbox 切换按钮实例（要我一直笑吗）

在线实例：[一键呲牙](https://fz6m.github.io/ciya-toggle-button/index.html)

### 效果

要我一直笑吗.jpg

<img src='https://cdn.jsdelivr.net/gh/fz6m/Private-picgo@moe/img/20201108054929.gif' width='30%' />

### 文件说明

向快乐出发.jpg

文件名|说明
:-:|:-
`style.scss`|核心样式文件
`_image.scss`|存放 base64 编码的表情图片
`index.html`|包含按钮节点内容

### 其他

实际使用中，如果需要使用多个请注意修改相应 label 的 `for` 和 input 的 `id` 相对应，从而取得当前按钮状态：

```js
    document.querySelector('#toggle').checked
```