# 🎨 提示词模板库

一个使用 Astro 搭建的静态网站，展示 AI 提示词模板。

## 添加新提示词

1. 编辑 `data/prompts.json` 文件
2. 按照以下格式添加新条目：

```json
{
  "title": "标题",
  "content": "提示词内容...",
  "category": "分类",
  "tags": ["标签1", "标签2"],
  "date": "2026-03-09"
}
```

3. 提交并推送到 GitHub，网站会自动更新

## 本地开发

```bash
npm install
npm run dev
```

## 部署

已连接到 Vercel，自动部署。
