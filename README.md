# sorag20 portfolio

GitHub Pages で公開しているポートフォリオサイトです。

- 公開 URL: https://sorag20.github.io/

## 構成

ビルド不要の静的サイトです。

```
.
├── index.html          # ページ本体
├── style.css           # スタイル（ライト / ダークモード対応）
├── assets/
│   └── aws-infra.png   # video-stream の AWS 構成図
└── .nojekyll           # Jekyll の処理を無効化
```

## ローカルでの確認

```bash
python3 -m http.server 8000
# http://localhost:8000 を開く
```
