# misaka310.github.io

YouTubeチャンネル「[ローカルAIと自作PC](https://www.youtube.com/@localai_pc)」の運営者が使う、
**個人用の動画アップロードツール**の公開ページです。

Google OAuth（YouTube Data API v3 / `youtube.upload` スコープ）の同意画面に登録する
「ホームページ」と「プライバシーポリシー」を置くために公開しています。

- ホームページ: https://misaka310.github.io/
- プライバシーポリシー: https://misaka310.github.io/privacy/

## 内容

| ファイル | 用途 |
|---|---|
| `index.html` | ツールの説明（OAuth同意画面のホームページ） |
| `privacy/index.html` | プライバシーポリシー（YouTube API Services・データの扱い・連絡先） |

静的HTMLだけです。ビルド処理、依存パッケージ、アクセス解析、Cookieはありません。
秘密情報・APIキー・トークンは置いていません。
