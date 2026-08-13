# Grus QR

VRChatアバター「Grus」用に作った、社員証認証風のジョークWebページです。QRコードから開くことを想定し、黒い画面にターミナル風の認証メッセージをタイプライター表示します。

## 内容

- 社員証認証風のテキスト演出
- Grus用IDの表示
- 「対象は仮想存在です」というエラーメッセージ
- GitHub Pagesでそのまま公開できる単一HTML構成

## 使い方

ビルドは不要です。`index.html`をブラウザで開くか、GitHub Pagesを有効にして公開URLをQRコードへ設定します。

## カスタマイズ

`index.html`内の次の箇所を編集できます。

- `message` — 表示する文章やID
- `normalSpeed` / `slowSpeed` — タイプ表示の速度
- CSSの`background-color` / `color` — 画面と文字の色

## 技術

- HTML
- CSS
- Vanilla JavaScript
- GitHub Pages

## ステータス

VRChat向けに作った個人の遊びプロジェクトです。
