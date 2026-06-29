# 亘古之约·埃及古文明16天探索 部署包

这是一个静态网页部署包，可直接上传到任意静态网站平台。

## 文件说明

- `index.html`：网页入口文件
- `assets/`：网页图片资源
- `_shared/fonts/`：网页字体资源

## 推荐部署方式

1. Netlify：登录 Netlify，选择 Add new site -> Deploy manually，将整个 `egypt-ancient-civilization-deploy` 文件夹拖入上传区域。
2. Vercel：新建项目后上传该文件夹，Framework Preset 选择 Other，部署目录保持根目录。
3. GitHub Pages：把本文件夹内容提交到仓库根目录，Pages Source 选择 main/root。
4. 任意服务器：把本文件夹内容上传到网站根目录，访问 `index.html` 即可。

注意：如果需要一个正式公网链接，需要使用你的 Netlify、Vercel、GitHub Pages、OSS/CDN 或服务器账号完成发布。
