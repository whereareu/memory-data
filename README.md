# Memory Data

技术文章爬虫生成的数据文件。

## 数据说明

- `articles.json` - 技术文章数据
- 更新频率：每小时

## 数据结构

```json
{
  "version": "1.0",
  "last_updated": "2026-03-26T17:19:40.488549",
  "sources": [...],
  "articles": [...]
}
```

## 使用方式

直接通过 GitHub Raw URL 访问：

```
https://raw.githubusercontent.com/whereareu/memory-data/main/articles.json
```

## 自动更新

通过 GitHub Actions 每小时自动更新数据。