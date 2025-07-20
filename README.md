# 我的Hexo博客

这是一个使用Hexo + NexT主题构建的个人博客，部署在GitHub Pages上。

## 项目特色

- 🎨 **NexT主题**：现代化设计，类似Dream2主题风格
- 📱 **响应式布局**：完美支持移动端和桌面端
- ⚡ **快速加载**：优化的性能表现
- 🔍 **搜索功能**：支持本地搜索
- 📊 **数据统计**：支持访问统计
- 💬 **评论系统**：支持多种评论插件

## 技术栈

- **框架**：Hexo 6.x
- **主题**：NexT 8.x
- **部署**：GitHub Pages
- **包管理**：Yarn

## 本地开发

### 环境要求
- Node.js 14+
- Yarn 或 npm

### 安装依赖
```bash
yarn install
```

### 本地预览
```bash
# 生成静态文件
yarn hexo generate

# 启动本地服务器
yarn hexo server
```

### 创建新文章
```bash
yarn hexo new "文章标题"
```

### 部署到GitHub Pages
```bash
yarn hexo clean
yarn hexo generate
yarn hexo deploy
```

## 主题配置

### NexT主题特性
- 多种配色方案（Muse、Mist、Pisces、Gemini）
- 支持数学公式（KaTeX、MathJax）
- 代码高亮（Prism.js、highlight.js）
- 图片懒加载
- 页面动画效果
- 社交链接
- 友情链接
- 标签云
- 归档页面

### 自定义配置
编辑 `_config.next.yml` 文件来自定义主题设置。

## 文章写作

### 文章格式
```markdown
---
title: 文章标题
date: 2025-07-20 12:00:00
tags: [标签1, 标签2]
categories: [分类]
---

文章内容...
```

### 支持的Markdown扩展
- 数学公式
- 代码高亮
- 图片处理
- 表格
- 任务列表
- 脚注

## 部署说明

1. **GitHub Pages**：自动部署到 `https://legeling.github.io/Page/`
2. **分支策略**：使用 `gh-pages` 分支存储静态文件
3. **自动构建**：每次推送到master分支时自动构建

## 访问地址

- **本地预览**：http://localhost:4000
- **在线地址**：https://legeling.github.io/Page/

## 维护说明

### 更新主题
```bash
yarn upgrade hexo-theme-next
```

### 备份数据
- 文章：`source/_posts/`
- 配置：`_config.yml`
- 主题配置：`_config.next.yml`

## 许可证

MIT License

## 联系方式

- 邮箱：your-email@example.com
- GitHub：[legeling](https://github.com/legeling) 