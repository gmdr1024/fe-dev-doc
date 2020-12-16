---
marp: true
theme: gaia
header: "fe_dev"
footer: "by ＠gmdr1024"
---

## フロントエンド開発環境をつくってみた

***@gmdr1024***

---
## 1. 自己紹介
- https://github.com/gmdr1024

---
## 2. つくったもの  
- https://github.com/gmdr1024/fe_dev
- フロントエンド開発環境

  - MPA(Multi-Page Application)向け
    - JavaScript FWを使わない

  - 初心者向け
    - 設定ファイルが少ない
    - シンプルな機能

---
## 3. できること
- **Lint** (構文チェック)

  ↓

- **Build** (ソースコード変換)

  ↓

- **Serve** (ローカルサーバー起動)

  ↓

- **Watch** (ソースコード変更監視)

---
## 3. できること

### Lint (構文チェック) 
- CSS/JavaScriptの構文をチェックする。
- 構文エラーを検知する。 

### Build (ソースコード変換)
- HTML/CSS/JavaScriptの構文を変換する。
- 分割されたソースファイルを1つにまとめる。

---
## 3. できること

### Serve (ローカルサーバー起動) 
- ローカルサーバーを起動。
- ローカルのHTML/CSS/JavaScriptを
  ブラウザで表示/確認する。 

### Watch (ローカルコード変更監視)
- ローカルのHTML/CSS/JavaScriptの修正を監視する。
- 修正すると、ブラウザが自動で再読み込みされる。

---
## 4. 技術
### Node.js
- JavaScriptの実行環境
- CLIやサーバーサイドでJavaScriptを実行できる

### npm
- Node.jsのパッケージ管理ツール
- オープンソースの便利なパッケージ群を取得できる

---
## 4. 技術
### ESLint
- JavaScriptの構文チェック
### StyleLint
- CSSの構文チェック


---
## 4. 技術
### Nunjucks
  - HTMLテンプレートエンジン
  - 分割したHTMLファイルをincludeで読み込める
  - extendsで
    「一部分だけ異なるHTMLファイル」を
    簡単に増やせる

---
## 4. 技術
### PostCSS
  - CSSポストプロセッサ
  - プラグインで便利な処理を色々行える
  - 分割したCSSファイルをimportで読み込める
  - ベンダープレフィックスを自動付与できる

---
## 4. 技術
### Parcel
  - JavaScriptモジュールバンドラー
  - 分割したJSファイルを1つにまとめてくれる
  - IE用の構文に自動で変換してくれる

---
## 4. 技術
### Browsersync
- ローカルサーバー起動、ソース変更と同期

### chokidar
- ローカルソースコード変更監視

---
# Thank you!