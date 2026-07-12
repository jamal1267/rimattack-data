# rimattack-data

RimAttack 多人聯賽的賽季資料(公開,GitHub Pages 托管),前端 https://playrimattack.com 以 `fetch` 讀取。

- `index.json` — 賽季/週/時段清單 + latest 指標
- `<season>/slots/<slot>/games.json` — 該時段所有比賽(seed + 兩隊 + 比分)
- `<season>/standings/<range>.json` — 累計排名(週 / 季)
- `teams/<teamId>.json` — 合格隊伍快照(供單場重放)

資料由聯賽引擎自動產出(只增不改)。schema 權威見主專案 `league/SCHEMA.md`。
目前為 **fixture 示範資料**,待定時排程 Action 上線後由真實投稿替換。
