# Siyu Huang 的学术主页

仓库：https://github.com/huang-siyu/huang-siyu.github.io

主页：https://huang-siyu.github.io/

本仓库 fork 自 [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io)，保留上游 MIT 许可证。个人简介、研究方向、教育、奖项和学术服务依据用户提供的学术资料更新，联系方式与照片沿用原有个人主页。

## 修改内容

- `_config.yml`：姓名、邮箱、GitHub、头像及网站地址。
- `_pages/about.md`：简介、动态、教育、实习、奖项和学术服务。
- `_data/navigation.yml`：顶部导航，使用页内锚点兼容项目路径。
- `images/me.jpg`：个人照片。
- `images/hcp_logo.jpg`：实验室标志。

Google Scholar 个人主页链接已配置。引用统计由 `_config.yml` 的 `google_scholar_stats_enabled` 控制，当前关闭；引用抓取工作流保持禁用，需要引用统计时可按上游 README 配置后启用。Google Analytics 尚未配置。

## GitHub Pages

发布方式为 `Deploy from a branch`，分支 `main`，目录 `/(root)`，由 GitHub Pages 构建 Jekyll 网站。

本配置用于 GitHub 账号 `huang-siyu` 下的同名主页仓库 `huang-siyu.github.io`，`baseurl` 为空。必须在账号改名及仓库改名完成后发布本配置。

后续可在 `_pages/about.md` 按实际进展更新个人信息和实习经历。各节使用图标标题，导航使用独立锚点。
