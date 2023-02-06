---
theme: Default
background: https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/04bd81f391524537bff81948979ac5df~tplv-k3u1fbpfcp-zoom-in-crop-mark:1304:0:0:0.awebp?
class: "text-center"
highlighter: shiki
lineNumbers: false
download: true
preload: false
---

# 学习slidev

Hello, World！[参考文档](https://cn.sli.dev/guide/)

---

# markdown语法

和原先的markdown语法一样

# 分页

用`---`符号在md文本中分开

---

# 导航

鼠标移动到左下角

---

# 动画

[参考链接](https://cn.sli.dev/guide/animations.html)

---

# 配置代码高亮

```
---
highlighter: shiki
---
```
创建 ./setup/shiki.ts 文件并添加以下代码：

```ts
/* ./setup/shiki.ts */
import { defineShikiSetup } from '@slidev/types'

export default defineShikiSetup(() => {
  return {
    theme: {
      dark: 'min-dark',
      light: 'min-light',
    },
  }
})

```


---

# 导出

看package.json文件
- npm run export为默认
- npm run export为黑色主题下



