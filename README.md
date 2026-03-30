# 退步生 · Slow is Best

一个苹果风格的中文个人主页，倡导"慢即是快"的生活理念。

## 预览结构

- **Hero** — 大标题 + 呼吸动画背景环
- **理念** — 左右双栏，文字 + 引言
- **践行** — 三张卡片，展示三个慢习惯
- **节律** — 深色背景，数字统计展示
- **关于** — 个人介绍 + 装饰性视觉区块
- **宣言** — 全屏居中引言
- **联系** — 邮件 CTA + Footer

## 技术栈

- 纯 HTML + CSS + 少量 JavaScript，无任何依赖
- 字体：Google Fonts（Cormorant Garamond + Noto Serif SC + Noto Sans SC）
- 滚动入场动画：IntersectionObserver API
- 响应式：支持移动端（≤800px）

## 使用方法

直接在浏览器中打开 `slow.html` 即可，无需构建步骤。

## 定制

| 内容 | 位置 |
|------|------|
| 姓名 / 标语 | Hero 区块的 `hero-name` / `hero-tagline` |
| 三个习惯 | `pillars-grid` 内的三张 `.pillar-card` |
| 数字统计 | `rhythm-stats` 内的 `.stat-item` |
| 关于介绍 | `about-content` 区块 |
| 联系邮箱 | `contact-cta` 的 `href` 属性 |
| 主题色 | CSS 变量 `--accent`（默认墨绿 `#2d5a3d`） |
