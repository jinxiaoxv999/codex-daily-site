# Codex日报公开页面

这是给 TikTok App 配置使用的静态官网草稿，包含：

- `index.html`：产品介绍页
- `terms.html`：服务条款
- `privacy.html`：隐私政策

## 发布前检查

当前页面已填写运营者：金笑旭，联系邮箱：244402907@qq.com。发布前请再次确认这些信息准确，并确认你愿意公开该邮箱。

## GitHub Pages 发布

1. 新建一个 GitHub 仓库，例如 `codex-daily-site`。
2. 上传本目录中的 4 个文件。
3. 在仓库的 **Settings → Pages** 中选择 `Deploy from a branch`、`main`、`/ (root)`。
4. 保存后等待 GitHub 生成 `https://你的用户名.github.io/codex-daily-site/`。
5. 打开该地址，逐一检查首页、`terms.html` 和 `privacy.html`。
6. 在 TikTok Sandbox 中填写对应的公开 HTTPS 地址。

GitHub Pages 会提供 HTTPS；不要把账号密码、Client Secret 或任何客户数据放进仓库。
