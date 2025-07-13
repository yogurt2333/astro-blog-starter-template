# Astro Starter Kit: Blog

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/cloudflare/templates/tree/main/astro-blog-starter-template)

![Astro Template Preview](https://github.com/withastro/astro/assets/2244813/ff10799f-a816-4703-b967-c78997e8323d)

<!-- dash-content-start -->

使用 Astro 创建一个博客，并将其作为 [静态网站](https://developers.cloudflare.com/workers/static-assets/).部署到 Cloudflare Workers 上。

功能:

- ✅ 极简风格（可自定义！）
- ✅ Lighthouse 性能评分 100/100
- ✅ 支持 SEO，包含规范 URL 和 OpenGraph 数据
- ✅ 支持站点地图
- ✅ 支持 RSS 订阅
- ✅ 支持 Markdown 和 MDX

<!-- dash-content-end -->

## 快速开始

在此仓库之外，您可以使用 [C3](https://developers.cloudflare.com/pages/get-started/c3/) (即 `create-cloudflare` 命令行工具)基于此模板启动一个新项目:

```bash
npm create cloudflare@latest -- --template=cloudflare/templates/astro-blog-starter-template
```

此模板的公开部署示例可在 [https://astro-blog-starter-template.templates.workers.dev](https://astro-blog-starter-template.templates.workers.dev)查看

## 🚀 项目结构

Astro 会在 `src/pages/` 目录中查找`.astro` 或 `.md` 文件。 每个页面会根据其文件名作为路由暴露。

`src/components/` 目录没有特殊之处，但我们通常将 Astro/React/Vue/Svelte/Preact 组件放在这里。

`src/content/` 目录包含相关的 Markdown 和 MDX 文档的“集合”。 
使用 `getCollection()` 从 `src/content/blog/`获取文章, 并通过可选模式对 frontmatter 进行类型检查. 更多信息请参阅 [Astro 的内容集合文档](https://docs.astro.build/en/guides/content-collections/).

任何静态资源（如图片）可以放在 `public/` 目录中。

## 🧞 命令

所有命令均从项目的根目录在终端中运行:

| 命令                              | 操作                                             |
| :-------------------------------- | :----------------------------------------------- |
| `npm install`                     | 安装依赖项                                        |
| `npm run dev`                     | 启动本地开发服务器，地址为 `localhost:4321`         |
| `npm run build`                   | 构建生产环境站点到 `./dist/`                       |
| `npm run preview`                 | 在部署前本地预览构建结果                            |
| `npm run astro ...`               | 运行 Astro CLI 命令，如 `astro add`, `astro check` |
| `npm run astro -- --help`         | 获取 Astro CLI 的使用帮助                           |
| `npm run build && npm run deploy` | 将生产环境站点部署到 Cloudflare                     |
