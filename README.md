# 阅间书房 · Book Nook

一个用于测试 GitHub + Supabase + 公网部署的中文阅读发现网站。

## 本地运行

直接用任意静态服务器打开项目即可，例如：

```bash
npx serve .
```

如果已创建 Supabase 项目，在 `supabase-config.js` 中填入项目 URL 和 anon key，然后执行 `supabase/schema.sql`。页面会从 `books` 表读取数据；未配置时会自动使用内置演示数据。

## 技术栈

- 原生 HTML / CSS / JavaScript
- Supabase Postgres（公开只读 RLS）
- GitHub Pages 静态部署
