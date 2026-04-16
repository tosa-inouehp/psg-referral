# PSG検査入院 受け入れ案内サイト

高知脳神経外科からの紹介患者（簡易SAS検査でSAS疑い）を、井上病院でPSG入院検査として受け入れるための案内ページ群です。

## GitHub Pages URL

> 設定後に記入: `https://[username].github.io/psg-referral/`

## ファイル構成

```
docs/                        # GitHub Pages 公開ディレクトリ
├── index.html               # 受け入れ案内トップ（フロー図含む）
├── checklist.html           # 予約・入院前・退院時チェックリスト
├── contact.html             # 担当窓口・連絡先
└── assets/
    ├── style.css            # 共通スタイル
    └── flow.svg             # 予約〜退院フロー図
documents/                   # 送付用文書（Word原稿）置き場
README.md
```

## GitHub Pages の設定方法

1. このリポジトリを GitHub にプッシュ
2. リポジトリの **Settings → Pages**
3. Source: **Deploy from a branch**
4. Branch: `main` / Folder: `/docs`
5. Save → 数分後に公開URL発行

## 要確認事項（石黒先生へ）

- [ ] 医事課の FAX 番号（contact.html に記入）
- [ ] 予約受付の対応時間（contact.html に記入）
- [ ] 担当窓口の部署名・担当者名（contact.html に記入）
- [ ] GitHub アカウント（病院用 or 個人）の確認
