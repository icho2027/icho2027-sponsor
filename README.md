# IChO 2027 企業贊助與認養計畫

單頁網站，以純 HTML + Tailwind CSS (CDN) + Lucide Icons (CDN) + 原生 JavaScript 撰寫，無須建置工具。

## 檔案結構
- `index.html`：頁面全部內容與程式
- `assets/`：Logo 圖檔與 100 國國旗拼圖 (flags-sprite.webp，10×10，順序同 RAW_COUNTRIES)

## 常改的設定（都在 index.html 的 <script> 開頭）
- `DEMO_STATUS`：各國認養狀態，例 `jp:{ status:'adopted', sponsor:'企業名稱' }`
- `SPONSORS`：已贊助企業名單與金額；`SHOW_AMOUNTS` 控制是否顯示個別金額
- `GOOGLE_FORM_PREFILL_URL`：Google 表單預先填寫連結（送出意向用）
- `VENUES`、`SCHEDULE`、`TIERS`、`TIER_ROWS`、`BUDGET`、`ITEMS`：場館、賽程、贊助等級、預算、認養項目

## 修改注意
- 這是靜態網站，請維持單一 index.html，不要改寫成 React 或加入後端。
- 新增國家時，國旗拼圖需同步更新。
