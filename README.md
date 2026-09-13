# Tengjun Chen — Academic Homepage

中英文双语学术个人主页，可直接使用 GitHub Pages 发布。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个公开仓库，例如 `tengjun-chen`。
2. 将本目录中的全部文件上传到仓库根目录并提交。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/ (root)`，然后点击 **Save**。
6. 等待 GitHub 完成部署。默认地址通常为：
   `https://你的GitHub用户名.github.io/tengjun-chen/`

如果希望网站直接位于 `https://你的GitHub用户名.github.io/`，仓库名称应设为：
`你的GitHub用户名.github.io`。

## 本地预览

可以直接双击 `index.html`，或在本目录启动任意静态文件服务器。

## 项目结构

```text
.
├── index.html
├── assets/
│   ├── tengjun-chen-candid.jpg
│   ├── tengjun-chen-presenting.jpg
│   ├── tengjun-chen-apria.jpg
│   ├── tengjun-chen-portrait.jpg
│   └── tengjun-chen-cv.pdf
├── .nojekyll
└── README.md
```

网站不需要安装依赖或执行构建命令。
