# Solitude ParticleS

「Solitude ParticleS」の開発ログとアップデート情報を発信するブログです。

## 「Solitude ParticleS」？
- 「もくもくと作業をしたいけど、ちょっと人の存在を感じたい」時にふらりと立ち寄れるアプリです。
- 図書館の自習室や、カフェで本を読むときのようなコンセプトで作っています。

> SNSを開けば人がいるのはわかるけど、ついつい時間を消費してしまい...

という状況から、個人的に欲しくて作ったアプリです。

ただいまこちらでテストリリース中です：https://solitude-particles.carrd.co/#



## 環境
- GitHub Pages
- Jekyll（minimaテーマ）
- Replit（開発環境）

## 投稿手順

1. 変更状態の確認
```bash
git status
```

2. 新規・変更された投稿の追加
```bash
git add _posts/*.md
```

3. 変更の確定
```bash
git commit -m "Update posts"
```

4. GitHubに反映
```bash
git push origin main
```

## 注意事項

- 開発時は_config.ymlのbaseurlが"/solpar"になっていることを確認
- 投稿ファイルは_postsディレクトリにYYYY-MM-DD-title.mdの形式で配置
- フロントマターは以下の形式を使用：

```
---
layout: post
title: "タイトル"
description: "概要"
date: YYYY-MM-DD
categories: カテゴリ
---
```

