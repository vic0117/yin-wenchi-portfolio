# 殷文琪Portfolio

平面設計作品集網站。單一 `index.html`，不需後端，用 GitHub Pages 發布。

## 結構
- `index.html`：整個網站（首頁、作品格線、點擊彈窗、關於區）
- `images/`：作品圖片，在 `index.html` 的 `projects` 陣列用相對路徑引用，例如 `images/01-cover.jpg`

## 編輯內容
打開 `index.html`，找到 `projects` 陣列，每個專案填：
- `title`：縮圖下方的小標題
- `cover`：縮圖圖片路徑（留空會顯示佔位圖）
- `date`：彈窗左側日期
- `text`：彈窗右側說明，一個字串一段
- `images`：彈窗內圖片，`{ src:"路徑", full:true }` 的 full 會佔滿整排

首頁文字、關於區與聯絡資訊直接在 HTML 內修改。

## 圖片建議
JPG 或 WebP，每張盡量控制在幾百 KB 以內。GitHub Pages 網站總大小上限 1 GB。

## 目前狀態
所有作品、名稱、聯絡資訊仍是範例內容，待換成正式資料。
