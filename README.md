# Artisan Coffee Roasters - スペシャルティコーヒーのポートフォリオサイト

ブルーボトルコーヒーのような洗練されたデザインのスペシャルティコーヒーロースターのポートフォリオサイトです。PageSpeed Insightsで80点以上を獲得できるよう最適化されています。

## 特徴

- **高性能**: PageSpeed Insightsで80点以上を目標とした最適化
- **レスポンシブデザイン**: モバイル、タブレット、デスクトップに対応
- **PWA対応**: Service Workerとマニフェストファイルによるオフライン機能
- **アクセシビリティ**: キーボードナビゲーションとスクリーンリーダー対応
- **モダンなデザイン**: ブルーボトルコーヒー風の洗練されたUI

## GitHub Pagesでの公開方法

### 1. GitHubリポジトリの作成
1. GitHubにログインして新しいリポジトリを作成
2. リポジトリ名を `coffee-portfolio` に設定
3. パブリックリポジトリとして作成

### 2. ファイルのアップロード
```bash
# リポジトリをクローン
git clone https://github.com/yourusername/coffee-portfolio.git
cd coffee-portfolio

# ファイルをコピー
cp /Users/yhinoda/Documents/coffee-portfolio/* .

# コミットとプッシュ
git add .
git commit -m "Initial commit: Coffee portfolio website"
git push origin main
```

### 3. GitHub Pagesの有効化
1. リポジトリの「Settings」タブに移動
2. 左サイドバーの「Pages」をクリック
3. Source を「Deploy from a branch」に設定
4. Branch を「main」に設定
5. 「Save」をクリック

### 4. 公開URLの確認
- サイトは `https://yourusername.github.io/coffee-portfolio/` で公開されます
- 数分後にアクセス可能になります

## 技術仕様

### パフォーマンス最適化
- CSSとJavaScriptの最小化
- クリティカルCSSのインライン化
- フォントの最適化（preload、preconnect）
- Service Workerによるキャッシュ戦略
- 画像の遅延読み込み対応
- 不要なリソースの削除

### レスポンシブデザイン
- モバイルファーストアプローチ
- CSS GridとFlexboxの活用
- タッチフレンドリーなUI
- 適応的なタイポグラフィ

### アクセシビリティ
- セマンティックHTML
- ARIA属性の適切な使用
- キーボードナビゲーション対応
- カラーコントラストの最適化

## ファイル構成

```
coffee-portfolio/
├── index.html          # メインHTMLファイル
├── styles.css          # スタイルシート
├── script.js           # JavaScriptファイル
├── sw.js              # Service Worker
├── manifest.json      # PWAマニフェスト
├── .gitignore         # Git除外ファイル
└── README.md          # このファイル
```

## 使用方法

1. ファイルをGitHubリポジトリにアップロード
2. GitHub Pagesを有効化
3. 公開URLでアクセス

## PageSpeed Insightsでのテスト

1. [PageSpeed Insights](https://pagespeed.web.dev/?hl=ja)にアクセス
2. 公開されたサイトのURLを入力
3. 「分析」ボタンをクリック
4. モバイルとデスクトップの両方でテスト

### 期待されるスコア
- **モバイル**: 80点以上
- **デスクトップ**: 90点以上

## 最適化のポイント

1. **リソースの最適化**
   - 外部フォントのpreload
   - クリティカルCSSの優先読み込み
   - 不要なリソースの削除

2. **レンダリング最適化**
   - レイアウトシフトの最小化
   - コンテンツの優先表示
   - スムーズなアニメーション

3. **キャッシュ戦略**
   - Service Workerによる静的リソースのキャッシュ
   - ブラウザキャッシュの活用
   - オフライン対応

4. **コード最適化**
   - 軽量なJavaScript
   - 効率的なCSS
   - 最小限のDOM操作

## ブラウザ対応

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## ライセンス

MIT License

## 作成者

Artisan Coffee Roasters