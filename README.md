日程助手 — 部署说明

## 5分钟部署到 Vercel

1. 去 [vercel.com](https://vercel.com) 注册免费账号（用 GitHub 登录最快）
2. 点 **Add New → Project**
3. 选 **Upload** 标签页
4. 把这整个文件夹（scheduler-app）拖进去上传
5. 点 **Deploy** → 等 30秒
6. 得到网址，例如 `your-app.vercel.app`

## 添加到 iPhone 主屏幕（变成 App）

1. Safari 打开你的 Vercel 网址
2. 点底部分享按钮 □↑
3. 选「添加到主屏幕」
4. 名称改成「日程助手」→ 添加
5. 主屏幕出现绿色图标，点开就是全屏 App！

## 文件说明
- `public/index.html — 主应用
- `public/manifest.json` — PWA 配置（图标、名称、颜色）
- `public/sw.js` — 离线缓存
- `public/icon-192.png` / `icon-512.png` — App 图标
- `vercel.json` — Vercel 配置
