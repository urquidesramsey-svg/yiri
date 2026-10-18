# 一日 · 饮食、运动与身体日记

这是可直接部署到 GitHub Pages 的静态网站，不需要服务器。

## GitHub Pages 发布
1. GitHub → New repository，仓库名建议 `yiri`，选择 **Public**，创建。
2. 进入仓库 → Add file → Upload files，将压缩包内的 `index.html`、`app.js`、`style.css`、`manifest.webmanifest`、`yiri-icon-v2.png`（可包括 README）全部上传到**仓库根目录**并提交（Commit）。不要上传 zip 本身。
3. Settings → Pages → Build and deployment → Source 选 Deploy from a branch → Branch 选 `main`，文件夹 `/ (root)`，保存。
4. 等待发布，打开 `https://你的GitHub用户名.github.io/yiri/`（实际以 Pages 页面的地址为准）。手机 Safari 中「分享」→「添加到主屏幕」。

## 运动记录
在底部「运动」标签添加运动项目、时长（分钟）和补充说明；可以一天添加多条，支持删除。最近7天统计在「趋势」内。当天的运动内容会加入每日长图报告。

## 数据保存与备份
数据只在当前浏览器的 IndexedDB 内，不会因上传 GitHub 而自动云同步。上传的代码不包含你的私人记录。换域名/旧网站的数据不会自动迁移：旧网站「⋯」→「导出完整备份」，新网站「⋯」→「恢复备份」。更新版本前也请备份。新版本的备份仍为 version 1，并兼容原有备份。

## 说明
部署后的 HTTPS 站点需要联网首次加载；GitHub Pages 本身不是离线安装包。如需彻底离线使用，需要另外实现离线缓存。代码和图标公开可见，**不要上传含饮食、身体照片等隐私数据的 JSON 备份文件**。
