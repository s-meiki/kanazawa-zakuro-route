# 金沢駅 鼓門 → ざくろ 金沢駅前 道案内

医療薬学会（2026年11月）にあわせた懇親会の会場「ざくろ 金沢駅前」（セントラルアークビル3F）まで、
金沢駅 兼六園口（東口）の鼓門からの徒歩ルートを写真つきで案内する1ページの静的サイトです。

**公開URL** https://s-meiki.github.io/kanazawa-zakuro-route/

- 約350m / 徒歩約5分、曲がるのは1回（堀川町の交差点で左折）
- スマホでの閲覧と、A4での印刷の両方に対応

## 出典

- 写真: Google ストリートビュー（© Google）
- 地図: © OpenStreetMap contributors
- ルート・距離: Googleマップ、OpenStreetMap の徒歩ルート検索（2026年10月15日時点）

写真は撮影当時のものです。看板や工事の状況が現在と異なる場合があります。

## 更新のしかた

このリポジトリの `index.html` は生成物です。編集元は別管理の
`懇親会_金沢_20261122/道案内/template.html` で、次のコマンドで再生成します。

```
python3 build_pages.py /Users/meiki/Developer/kanazawa-zakuro-route
```

そのうえで、このリポジトリで `git add -A && git commit && git push` すれば公開ページに反映されます。
