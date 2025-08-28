# 使用说明

本项目是一个简单的告白页面，打开 `index.html` 即可预览。

## 必改：顶部漂浮文字（“修改文字”）
- 文件：`index.html`
- 位置：`<div class="container">` 内，紧跟 `<!-- 修改文字 -->` 的若干个 `<span>`。
- 操作：每个 `<span>` 放一个字符；可增减 `<span>` 个数或替换其字符为你的内容。

示例：
```html
<div class="container">
	<!-- 修改文字 -->
	<span>i</span>
	<span>z</span>
	<span>h</span>
	<span>o</span>
	<span>u</span>
</div>
```
效果展示
<img width="1667" height="910" alt="dispaly" src="https://github.com/user-attachments/assets/4253cbce-5918-49e9-aa6d-c5fdd9838360" />


## 可选：首屏文案（打字机）
- 在 `index.html` 中搜索 `firstMsg`，将字符串替换为你的句子：
```js
const firstMsg = '遇见你之后，星河有了名字，晚风也有了归期。做我的TA，好吗？';
```

## 预览与发布
- 预览：直接双击 `index.html` 打开。
- 发布：将整个文件夹上传至任意静态空间（如 GitHub Pages/Netlify/Vercel 等）。

