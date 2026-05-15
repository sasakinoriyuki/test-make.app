# Test Make App

穴埋め問題作成・解答ウェブサイト

## 概要

このアプリケーションは、穴埋め問題を簡単に作成・管理・解答できるウェブサイトです。無料プランの制限（30問まで）に縛られず、無制限に問題を作成できます。

## 機能

- ✅ 穴埋め問題の作成・編集・削除
- ✅ 複数の問題セット管理
- ✅ リアルタイム解答チェック
- ✅ 成績管理・分析（計画中）
- ✅ シェア機能（計画中）

## スタック

- **フロントエンド**: Next.js 14 + React 18 + TypeScript
- **バックエンド**: Next.js API Routes
- **スタイリング**: Tailwind CSS
- **データベース**: PostgreSQL
- **デプロイ**: Vercel

## セットアップ

### 前提条件

- Node.js 18+
- npm または yarn
- PostgreSQL

### インストール

1. リポジトリをクローン
```bash
git clone https://github.com/sasakinoriyuki/test-make.app.git
cd test-make.app
```

2. 依存関係をインストール
```bash
npm install
```

3. 環境変数を設定
```bash
cp .env.example .env.local
```

`.env.local` を編集して、適切な値を設定してください。

4. 開発サーバーを起動
```bash
npm run dev
```

ブラウザで [http://localhost:3000](http://localhost:3000) を開きます。

## ディレクトリ構成

```
test-make.app/
├── src/
│   ├── app/              # Next.js App Router
│   ├── components/       # React コンポーネント
│   ├── pages/           # API ルート
│   ├── styles/          # グローバルスタイル
│   └── types/           # TypeScript型定義
├── public/              # 静的ファイル
├── package.json
├── tsconfig.json
├── tailwind.config.js
└── README.md
```

## 開発

### スクリプト

- `npm run dev` - 開発サーバー起動
- `npm run build` - 本番ビルド
- `npm run start` - 本番サーバー起動
- `npm run lint` - ESLint実行

### コードスタイル

このプロジェクトは ESLint を使用しています。

```bash
npm run lint
```

## デプロイ

### Vercel へのデプロイ

1. [Vercel](https://vercel.com) にログイン
2. 「New Project」をクリック
3. このリポジトリを選択
4. 環境変数を設定
5. デプロイを開始

詳細は [Vercel ドキュメント](https://vercel.com/docs) を参照してください。

## ライセンス

MIT

## 貢献

プルリクエストを歓迎します。大きな変更の場合は、まずissueを開いて変更内容を議論してください。

## サポート

問題や質問がある場合は、[GitHub Issues](https://github.com/sasakinoriyuki/test-make.app/issues) で報告してください。
