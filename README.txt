Tokyo Trip Planner PWA
======================

內容：
- index.html
- manifest.webmanifest
- sw.js
- icons/

使用方法：
1. 解壓縮後，放到任何靜態網站空間，或用本機 HTTP server 開啟。
2. 不建議直接雙擊 index.html 測試 Service Worker；請用 localhost 或 https。
3. iPhone / iPad：Safari 開啟後，用 分享 > 加入主畫面。
4. Android / Chrome：選單 > 加入主畫面 / 安裝 App。

本機測試例子（有 Python 的話）：
python -m http.server 8000
然後打開 http://localhost:8000/
