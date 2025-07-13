# src 配下

## フォルダ説明

- `assets/`  
  画像やフォントなどの静的ファイル。Vite では `public/` も活用。

- `components/`  
  汎用的で再利用可能な UI コンポーネントを配置。

- `features/`  
  機能ごとのまとまり単位で、ビジネスロジックを含むコンポーネント群。

- `hooks/`  
  カスタム React フック。API 呼び出しやフォーム制御などのロジックを切り出す。

- `layouts/`  
  ページ共通のレイアウト（ヘッダー、フッターなど）。

- `pages/`  
  React Router のルート用画面コンポーネントを配置。

- `stores/`  
  Zustand や Recoil などの状態管理ファイル。

- `schemas/`  
  データベーススキーマまとめ

- `styles/`  
  グローバル CSS やテーマ設定、Tailwind の設定ファイル。

- `types/`  
  型定義ファイル

- `utils/`  
  文字列操作、日付フォーマット、API クライアントの共通処理など。

- `App.tsx`  
  ルーティングや全体レイアウトの設定。

- `main.tsx`  
  React のエントリーポイント。DOM へのマウント処理を担当。
