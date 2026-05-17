# 🎊 婚禮問答遊戲

## 檔案說明
- `host.html` — 主持人控制台（出題、控制進度、排行榜）
- `player.html` — 賓客作答畫面（手機開啟）

## 使用方式

### 方式一：直接開啟（本機測試）
直接用瀏覽器開啟 `host.html` 即可測試。
但賓客無法從其他裝置連線，需要部署到網路。

### 方式二：部署到 GitHub Pages（免費，推薦）
1. 在 GitHub 建立新 repo（例如 `wedding-quiz`）
2. 把 `host.html` 和 `player.html` 上傳
3. 到 repo Settings → Pages → 選 main branch
4. 網址會是：`https://你的帳號.github.io/wedding-quiz/host.html`
5. 賓客連結：`https://你的帳號.github.io/wedding-quiz/player.html?quiz=題組ID`

## 流程
1. 主持人開啟 host.html
2. 填寫題組名稱，點「建立題組」
3. 新增題目（選擇題/是非題）
4. 賓客掃描 QR Code 或點連結，輸入名字加入
5. 主持人點「開始第一題」
6. 賓客即時作答，主持人點「顯示答案」
7. 繼續下一題，最後點「結束遊戲」顯示排行
