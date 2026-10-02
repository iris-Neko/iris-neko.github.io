# iris-Neko · 技术笔记

使用 GitHub Pages 与 Jekyll 发布的中文技术笔记。

- 网站：https://iris-neko.github.io/
- 第一篇文章：Windows 11 的文件关联为何“设置成功”却不生效：一次 PotPlayer 自动化排查

## 发布文章

在 `_posts/` 新建 `YYYY-MM-DD-slug.md`，添加 `layout`、`title`、`date`、`description` 和可选的 `tags` 前置信息，再提交到 `main` 分支。GitHub Pages 会自动构建和发布。

页面布局位于 `_layouts/`，样式位于 `assets/css/style.css`。站点不加载第三方字体、统计脚本或其他前端依赖。

## 发布配置

GitHub Pages 的发布源为 `main` 分支的根目录 `/`，通过 GitHub 原生 Jekyll 构建流程生成站点。