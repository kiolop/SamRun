# 🌐 政策页面发布指南（2 分钟版）

> 目标：把 `references/privacy-policy.html` 和 `references/user-agreement.html` 变成两个公开可访问的链接，填入华为申请表。

## 方式一：GitHub Pages（推荐，如你有 GitHub 账号）

1. 打开 https://github.com/new 新建仓库
   - 名称建议：`runningsam-pages`
   - 可见性：Public（必须公开，Pages 免费版不支持私有）
2. 上传两个文件（仓库首页 "uploading an existing file" 链接，直接拖入）：
   - `references/privacy-policy.html`
   - `references/user-agreement.html`
3. 仓库 Settings → 左侧 Pages → Build and deployment → Source 选 `Deploy from a branch` → Branch 选 `main` / `(root)` → Save
4. 等 1 分钟，得到两个链接：
   - `https://<你的用户名>.github.io/runningsam-pages/privacy-policy.html`
   - `https://<你的用户名>.github.io/runningsam-pages/user-agreement.html`
5. 浏览器打开确认能访问 → 把两个链接发给 AI 填入申请表

## 方式二：任意静态主机（Vercel / Netlify Drop / 你自己的服务器）

- Netlify Drop：https://app.netlify.com/drop 直接拖文件夹（需注册）
- 或部署到你已有的任何网站路径下

## 方式三：临时方案（不推荐用于正式提交）

如果暂时不方便发布，可先用语雀/飞书文档的"公开分享"链接（把 HTML 内容粘进去或作为附件页面），后续再换正式域名链接 —— 华为审核时链接必须可访问。

---

**填表位置**：申请表第二页「隐私政策链接」+「协议链接」两个必填框。
**发布完成后**：把两个链接发给 AI，AI 会填入表单并截图给你做最终提交确认。
