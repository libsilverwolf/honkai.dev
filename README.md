# honkai.dev

[@libsilverwolf](https://github.com/libsilverwolf)'s intro & blog site. Powered by hugo & notion.

[honkai.dev](https://honkai.dev)

## Requirements

- [hugo](https://github.com/gohugoio/hugo)
- [go-task](https://taskfile.dev/)
- [notion-site](https://github.com/nonacosa/notion-site)

## TODO

- [x] RSS Generator
- [x] TOC开关 *配置`toc`这个param*
- [x] Banner是否正常生效 *配置了`frontmatter`*
- [x] 当notion侧撤掉post时同步进行撤下 *没必要，目前每次都是从头重新生成所有，不去单独处理了*

## 生成网站

```
$ task
```

## Github action secrets

- `NOTION_SECRET`
- `NOTION_DATABASE_ID`
- `CLOUDFLARE_API_TOKEN`
- `CLOUDFLARE_ACCOUNT_ID`
- `CLOUDFLARE_PAGES_PROJECT_NAME`