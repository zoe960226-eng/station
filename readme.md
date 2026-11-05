# 台中驛鐵道影展專題網頁建置計畫 (Taichung Railway Film Festival)

作者：陳柔安  
系級：行銷系大二  
課程專案：期中專題網頁設計 (台中驛影展介紹)

---

## 專案簡介

本專案為行銷專題「台中驛鐵道影展」之前端網站開發。結合國定古蹟舊台中車站（台中驛）之歷史文化背景與當代獨立電影展演，打造主題式影展介紹網頁。

網頁採用語意化 HTML5 結構、模組化 CSS 切割架構，並透過 CSS Grid System 與 RWD 響應式佈局，確保手持裝置（手機、平板）皆可流暢瀏覽完整的展演與觀影資訊。

---

## 專案檔案結構 (Directory Structure)

```text
Second-Market/
├── index.html              # 主頁面 (包含導覽列、側邊欄、影展卡片網格、觀影指南與分頁導覽)
├── history.html            # 歷史演進頁面 (台中驛百年起源與建築發展)
├── README.md               # Prompt 說明與 Vibe Coding 指令紀錄檔
├── css/
│   ├── base.css            # 全域基礎設定、Reset 與 CSS 變數定義
│   ├── layout.css          # Header, Sidebar, Grid System, Card 與 Footer 佈局
│   └── responsive.css      # RWD 斷點媒體查詢 (針對手機與平板排版優化)
└── images/
    ├── station-hero.jpg    # 國定古蹟台中驛紅磚建築與鐘樓全景 (Hero Banner)
    ├── station-building.jpg# 台中驛辰野式紅磚牆與洗石子帶飾特寫照片 (卡片 1)
    ├── station-platform.jpg# 台中驛舊站第一月台鋼骨雨棚與保留軌道實景 (卡片 2)
    └── station-track.jpg   # 從保留軌道視角眺望舊台中車站鐘樓之實景照片 (卡片 3)