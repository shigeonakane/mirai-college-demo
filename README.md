# 未来創造専門学校 デモサイト

CampusSite Partner 営業用デモサイトです。

## 概要

日本の専門学校向けウェブサイトパッケージ「CampusSite Partner」のデモンストレーション用に作成された架空の専門学校サイトです。

## ページ構成（MVP）

| ページ | URL |
|--------|-----|
| トップページ | `/index.html` |
| 学科一覧 | `/courses/index.html` |
| ITエンジニア学科 | `/courses/it.html` |
| オープンキャンパス | `/opencampus/index.html` |
| 就職・資格 | `/career/index.html` |
| 学校案内 | `/about/index.html` |

## 技術スタック

- HTML5
- Tailwind CSS v3.4
- JavaScript (Vanilla)
- Google Fonts (Noto Sans JP)

## ローカル開発

```bash
# 依存パッケージをインストール
npm install

# CSSをビルド
npm run build:css

# 開発サーバー（CSSの変更を監視）
npm run dev
```

## デザインガイドライン

- 日本の専門学校サイトにふさわしい、信頼感・清潔感のあるデザイン
- プライマリカラー: #2563EB（青）
- セカンダリカラー: #F97316（オレンジ）
- アクセントカラー: #10B981（緑）

詳細は `CLAUDE.md` を参照してください。

## 画像素材

Unsplash、Pexelsからのフリー素材を使用しています。

## ライセンス

MIT License

---

CampusSite Partner - 専門学校向けウェブサイト構築サービス
