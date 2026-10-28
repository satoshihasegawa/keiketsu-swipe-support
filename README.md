# 経穴スワイプ サポートサイト

iPhoneアプリ「経穴スワイプ」の公開用サポートページです。HTMLとCSSだけで構成し、アプリの経穴データや個人情報は含みません。

## ページ

- `index.html`：アプリの案内
- `privacy.html`：プライバシーポリシー（App Store Connect の「プライバシーポリシーURL」）
- `support.html`：操作方法、よくある質問、お問い合わせ（App Store Connect の「サポートURL」）
- `styles.css`：共通スタイル（ツボ変換辞書のサポートサイトと共通の作り）
- `icon.png`：アプリアイコン（256px）

## 公開先

`https://satoshihasegawa.github.io/keiketsu-swipe-support/`

GitHub Pages（`main` ブランチのルート）から公開しています。

## ローカル確認

このフォルダで次を実行し、表示されたURLをブラウザで開きます。

```sh
python3 -m http.server 8080
```

## お問い合わせ先の変更

`support.html` 内の `CONTACT_LINK` コメントの直後にあるリンクを変更します。現在は次のGitHub Issuesを案内します。

`https://github.com/satoshihasegawa/keiketsu-swipe-support/issues/new`
