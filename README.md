# dj_system-docs
MC支援サービス「DJ System」の資料

## リポジトリ

- https://github.com/lit-kansai/dj_system-portal
- https://github.com/lit-kansai/dj_system-api

## 技術選定

|  | 内容 | 技術 |
| --- | --- | --- |
| Portal Site | Webアプリケーションフレームワーク | Nuxt.js |
|  | CSSフレームワーク | Tailwind CSS |
|  | アーキテクチャ | API Gateway<br>Vuex（ページ間を跨ぐもののみ） |
|  | 動作環境 | Vercel |
|  | 要件 | レスポンシブ対応<br>楽曲の検索 |
| DJ API | メイン言語 | Ruby |
|  | 開発環境 | AWS |
|  | フレームワーク | Sinatra |
|  | 動作環境 | Heroku |
|  | その他 | WebSコース最新の推奨環境 |
|  | 要件 | Portal Siteチームが使いたいAPIを提供 |

## 設計

### APIリファレンス

[https://lit-kansai.github.io/dj_system-docs/api](https://lit-kansai.github.io/dj_system-docs/api)

### DB設計

![](https://lit-kansai.github.io/dj_system-docs/db/dj.svg)
