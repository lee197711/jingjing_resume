# 个人简历网站部署指南

## 已完成的工作

1. **修改了下载链接**：将简历下载链接指向了正确的PDF文件 `李晶晶-PM-15708707398.pdf`
2. **初始化了Git仓库**：创建了Git仓库并提交了所有文件

## 部署步骤

### 方法一：使用 Vercel 部署（推荐）

Vercel 是一个免费的静态网站托管服务，支持自动部署和HTTPS。

1. **访问 Vercel 官网**：https://vercel.com
2. **登录或注册**：使用 GitHub 账号登录
3. **创建新项目**：
   - 点击 "New Project"
   - 选择 "Import Git Repository" 或 "Drag and Drop"
   - 如果选择拖放方式，直接将整个 `PM_resume` 文件夹拖放到指定区域
4. **部署设置**：
   - 项目名称：可以使用默认名称或自定义
   - 构建命令：留空（静态网站不需要构建）
   - 输出目录：留空（默认为根目录）
5. **点击 "Deploy"**：Vercel 会自动部署你的网站
6. **获取访问链接**：部署完成后，Vercel 会提供一个公开的 URL，例如 `https://your-project.vercel.app`

### 方法二：使用 GitHub Pages 部署

1. **创建 GitHub 仓库**：
   - 访问 https://github.com/new
   - 仓库名称：可以使用 `yourusername.github.io`（如果是个人主页）或其他名称
   - 选择 "Public"
   - 勾选 "Initialize this repository with a README"
   - 点击 "Create repository"

2. **上传文件**：
   - 进入创建的仓库
   - 点击 "Add file" → "Upload files"
   - 选择 `PM_resume` 文件夹中的所有文件（`lijingjing-resume.html`、`李晶晶-PM-15708707398.pdf` 和 `.gitignore`）
   - 点击 "Commit changes"

3. **启用 GitHub Pages**：
   - 进入仓库的 "Settings"
   - 点击 "Pages" 选项卡
   - 在 "Source" 部分，选择 "main" 分支
   - 点击 "Save"
   - 等待几分钟，GitHub 会生成访问链接

### 方法三：使用 Netlify 部署

1. **访问 Netlify 官网**：https://www.netlify.com
2. **登录或注册**：使用 GitHub、GitLab 或 Bitbucket 账号登录
3. **创建新项目**：
   - 点击 "Add new site"
   - 选择 "Deploy manually"
   - 拖放 `PM_resume` 文件夹到指定区域
4. **部署**：Netlify 会自动部署你的网站
5. **获取访问链接**：部署完成后，Netlify 会提供一个公开的 URL

## 验证部署

部署完成后，访问生成的 URL，确保：

1. 网页正常加载
2. 导航栏可以正常切换标签
3. 点击 "简历 PDF" 按钮可以成功下载简历文件

## 注意事项

- 所有部署方法都是免费的
- 部署完成后，你的简历网站会有一个公开的 URL，可以分享给他人
- 如果后续需要更新内容，只需重新上传修改后的文件即可