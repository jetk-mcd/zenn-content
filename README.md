# zenn-content

[Zenn](https://zenn.dev/) の記事を管理するリポジトリ。GitHub連携により、`main` へのpushで自動的にZennへ反映される。

## 運用

- 記事は `articles/*.md`。frontmatter の `published: false` で下書き、`true` で公開
- 新規記事のslug（ファイル名）は12〜50文字の半角英数字とハイフン
- 執筆・pushはClaude Codeが行い、公開の最終判断（`published: true` への変更）は内容確認後に行う

## 初回セットアップ（手動・1回のみ）

1. [zenn.dev/dashboard/deploys](https://zenn.dev/dashboard/deploys) を開く
2. このリポジトリ（jetk-mcd/zenn-content）を連携する

## ローカルプレビュー（任意）

```bash
npx zenn-cli preview
```
