# 数据分析作品集网站

这是一个用于展示数据分析项目和技能的个人作品集网站模板。网站采用响应式设计，适配各种设备显示，包含多个展示数据分析项目、技能和个人介绍的部分。

## 网站结构

```
project-webside/
├── index.html              # 主页
├── css/
│   └── styles.css          # 样式表
├── js/
│   └── main.js             # JavaScript脚本
├── images/                 # 图片资源目录
├── projects/               # 项目详情页面
│   └── project1.html       # 销售数据分析项目详情页示例
└── README.md               # 本文档
```

## 功能特点

- 响应式设计，适配各种设备显示
- 现代化的UI设计，展示专业形象
- 平滑滚动和交互动画效果
- 详细的项目展示页面
- 技能展示部分
- 联系表单

## 使用指南

### 基本设置

1. 克隆或下载本仓库到本地
2. 根据需要修改`index.html`文件中的内容
3. 在`images`目录中替换示例图片为你自己的图片
4. 自定义`css/styles.css`中的颜色和风格

### 添加新的项目

1. 在`projects`目录中创建新的HTML文件，可以复制`project1.html`作为模板
2. 在主页的作品展示部分添加新项目的卡片
3. 确保新项目的图片放在`images`目录中
4. 更新链接和描述

### 自定义样式

主要颜色变量在`styles.css`文件开头:

```css
:root {
    --primary-color: #4a6baf;
    --secondary-color: #6c8cd5;
    --dark-color: #1e293b;
    --light-color: #f8fafc;
    --success-color: #28a745;
    --danger-color: #dc3545;
    --max-width: 1200px;
}
```

修改这些变量可以轻松更改整个网站的配色方案。

## 图片替换指南

网站需要以下图片资源:

- `images/hero-bg.jpg`: 首页顶部背景图片 (建议尺寸: 1920x1080px)
- `images/profile.jpg`: 个人照片 (建议尺寸: 400x400px)
- `images/project1.jpg`, `images/project2.jpg`, `images/project3.jpg`: 项目缩略图 (建议尺寸: 600x400px)
- `images/project1-bg.jpg`: 项目详情页顶部背景 (建议尺寸: 1920x400px)
- `images/sales_trend.jpg`, `images/customer_segments.jpg`: 数据可视化图表 (建议尺寸: 800x500px)

## 本地开发

你可以使用任何本地服务器来预览网站，例如:

```bash
# 使用Python搭建简单的本地服务器
# Python 3.x
python -m http.server

# Python 2.x
python -m SimpleHTTPServer
```

然后在浏览器中访问 `http://localhost:8000` 即可预览网站。

## 部署

本网站是纯静态网站，可以部署在任何支持静态网站托管的平台，如:

- GitHub Pages
- Netlify
- Vercel
- 传统虚拟主机

## 自定义内容

请确保替换以下内容为你自己的信息:

1. 个人介绍和技能
2. 项目描述和图片
3. 联系信息
4. 社交媒体链接

## 浏览器兼容性

网站兼容所有现代浏览器，包括:

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## 许可

本模板可自由用于个人和商业用途。 