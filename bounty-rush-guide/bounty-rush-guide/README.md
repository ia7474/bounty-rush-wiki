# バウンティラッシュ 攻略サイト（サンプル）

見やすくわかりやすい攻略サイトのサンプルです。

## ページ構成

| ページ | ファイル | 内容 |
|--------|----------|------|
| ホーム | `index.html` | トップページ・各コンテンツへの導線 |
| 最強ランキング | `ranking.html` | Tier表（キャラクリックで個別ページへ） |
| リセマラ | `reroll.html` | リセマラ手順と終了ライン |
| 初心者ガイド | `beginner.html` | 序盤の進め方・毎日やること |
| キャラ個別 | `characters/*.html` | 各キャラの評価ページ |

## ファイル構成

```
bounty-rush-guide/
├── index.html
├── ranking.html
├── reroll.html
├── beginner.html
├── style.css
├── README.md
├── characters/
│   ├── nika.html
│   ├── nasujurou.html
│   └── ...（他キャラ）
└── images/          ← キャラ画像を入れるフォルダ
```

## 使い方

1. `index.html` をブラウザで開く
2. ナビゲーションやカードから各ページへ移動
3. Tier表のキャラ画像をクリック → 個別評価ページへ

## カスタマイズのヒント

- **キャラ画像を差し替える**  
  `images/` に画像を置き、HTML内の `.char-placeholder` を `<img>` タグに変更

- **新しいキャラを追加**  
  `characters/` にHTMLをコピーして作成し、`ranking.html` の該当Tierにリンクを追加

- **デザイン変更**  
  `style.css` を編集

※現在の評価文やTierはサンプルです。実際の環境に合わせて更新してください。
