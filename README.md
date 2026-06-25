# 腹膜透析 生活サポートツール 公開用パッケージ

このフォルダは、GitHub Pages で公開するための最小セットです。

Brain 本体や個人メモは含めず、公開してよいツールだけを入れています。

## 中身

- `index.html`
  - 入口ページ
- `pd-helper/`
  - 毎日の記録アプリ
- `pd-inventory/`
  - 在庫管理ツール

## GitHub Pages 公開後のURL例

GitHubのユーザー名が `example`、リポジトリ名が `pd-tools` の場合:

- 入口ページ
  - `https://example.github.io/pd-tools/`
- PD-Helper
  - `https://example.github.io/pd-tools/pd-helper/`
- 在庫管理ツール
  - `https://example.github.io/pd-tools/pd-inventory/`

このURLをQRコードにすると、スマホで直接開けます。

## 公開手順

1. GitHubで新しいリポジトリ `pd-tools` を作る
2. この `publish/pd-tools` フォルダの中身だけをアップロードする
3. GitHubの `Settings` → `Pages` を開く
4. `Deploy from a branch` を選ぶ
5. `main` / `root` を選んで保存する
6. 数分待って、表示されたURLをスマホで開く

## 注意

- `Ei_2nd_Brain` 全体を公開しないこと。
- 公開するのは、この `publish/pd-tools` の中身だけ。
- 入力データは各ユーザーのブラウザ内に保存されます。
- このツールは医療判断用ではなく、記録と在庫確認を補助するためのものです。
