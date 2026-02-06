# OpenClaw Ops Radar

靜態單頁儀表板（不用 server）。

## 打開方式
直接在瀏覽器開：
`/media/cw/Data/AI_Playground/projects/ops-radar/index.html`

## 資料來源
預設顯示內建 fallback。
若存在以下檔案則會讀取：
`/media/cw/Data/AI_Playground/logs/ops_radar.json`

## 之後可加的自動化
- 用 cron 產生 `ops_radar.json`
- 讀 cron.runs 統計成功率與延遲
- 讀 logs/self_improve.md 取近期重點
