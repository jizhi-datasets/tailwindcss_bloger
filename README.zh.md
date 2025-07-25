# TailwindCSS Blogger

[English Version: README.md](README.md)

一个基于TailwindCSS的在线编辑器，提供实时预览功能，所有资源通过CDN加载，无需复杂配置。

## 安装 (Install)

由于这是一个纯静态HTML页面，您只需要安装一个简单的HTTP服务器即可运行：

```bash
# 全局安装http-server（如果尚未安装）
npm install -g http-server
```

## 使用 (Use)

1. 在项目目录下启动HTTP服务器：
   ```bash
   http-server -p 8080
   ```

2. 打开浏览器，访问以下地址：
   ```
   http://localhost:8080
   ```

## 特点
- 实时预览TailwindCSS效果
- 无需安装额外依赖，所有资源通过CDN加载
- 简洁易用的编辑器界面
- 支持响应式设计预览