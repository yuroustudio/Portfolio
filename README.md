# 🚀 小程式作品集 (Mini-Apps Portfolio)

> 匯聚 6 款由 AI 輔助打造的精選前端互動小應用，涵蓋生活工具、習慣養成、任務管理、休閒娛樂與商務財務數據視覺化。

---

## 🌟 專案簡介

本專案提供一個高質感、現代化且具備響應式設計（RWD）的入口首頁 `index.html`，並整合 6 款純前端獨立運作的小程式。所有應用皆無需任何後端或建置步驟（Zero Build Step），直接以瀏覽器開啟即可暢快體驗！

---

## 📱 首頁亮點功能 (`index.html`)

- **🌌 現代深邃科技美學**：採用極光漸變光暈（Aurora Glow）與半透明毛玻璃（Glassmorphism）卡片設計。
- **📱 響應式佈局 (RWD)**：自動適應智慧型手機、平板電腦與寬螢幕電腦。
- **🔍 即時關鍵字搜尋**：支援小程式名稱、功能特色與技術標籤的即時動態過濾。
- **🏷️ 分類切換篩選**：提供「全部」、「工具生活」、「生產力」、「休閒娛樂」、「數據分析」分類導覽。
- **👁️ 內建即時預覽彈窗 (Quick View)**：無需跳轉頁面，即可直接在首頁彈窗內試玩體驗小程式。
- **↗️ 一鍵新分頁開啟**：每張作品卡片皆附帶顯著的「開啟」按鈕，快速開啟完整畫面。

---

## 🎮 收錄之 6 款小程式

| # | 小程式名稱 | 原始檔案 | 領域分類 | 主要技術與亮點 |
|:---:|---|---|---|---|
| **1** | **80s City Pop 數字時鐘** | `80s City Pop 數字時鐘.html` | 工具生活 / 復古潮流 | 80 年代日系 City Pop 霓虹美學、Synthwave 聲光特效、多款經典復古字體切換 |
| **2** | **Northern Hydro 飲水追蹤** | `Daily Water Tracker.html` | 健康生活 / 習慣養成 | 北歐極簡風格、動態水球進度環、Chart.js 趨勢統計與歷史記錄 |
| **3** | **Lively Lemon 鮮檸待辦** | `Lively Lemon To-Do App.html` | 生產力 / 任務管理 | 鮮活檸檬黃配色、Tone.js 愉悅和弦音效回饋、分類標籤與完成度動畫 |
| **4** | **台灣環島旅遊大富翁** | `台灣旅遊大富翁地圖.html` | 休閒娛樂 / 互動遊戲 | 台灣名勝景點環島大富翁、擲骰前進、機會命運隨機事件、紙花慶祝特效 |
| **5** | **現金流量與財務分析** | `現金流量表與財務數據視覺化分析工具.html` | 商業財務 / 數據視覺化 | ECharts 互動趨勢圖表、SheetJS Excel 報表上傳解析、現金流健康指標檢測 |
| **6** | **飲食紀錄** | `diet-plan/index.html` | 健康習慣 / 體態追蹤 | 新野獸派風格、熱量三大營養素追蹤、InBody 月度體態數據、連續紀錄遊戲化、PWA 離線安裝支援 |

---

## 🛠️ 技術棧 (Tech Stack)

- **核心技術**：HTML5、Vanilla CSS3、JavaScript (ES6+)
- **前端樣式庫**：Tailwind CSS (CDN)
- **圖表與視覺化**：Chart.js、Apache ECharts
- **數據解析**：SheetJS (xlsx)
- **音效與動畫**：Tone.js、Canvas Confetti
- **字體與圖示**：Google Fonts (Plus Jakarta Sans, Inter, Noto Sans TC 等)、FontAwesome 6

---

## 📂 專案目錄結構

```text
Portfolio/
├── index.html                                   # 作品集入口首頁 (RWD, 搜尋, 篩選, 預覽)
├── README.md                                    # 專案說明文件
├── .gitignore                                   # Git 忽略檔案設定
├── 80s City Pop 數字時鐘.html                     # 80 年代日系復古時鐘
├── Daily Water Tracker.html                     # 每日飲水追蹤工具
├── Lively Lemon To-Do App.html                  # 鮮檸活潑待辦清單
├── 台灣旅遊大富翁地圖.html                         # 台灣環島大富翁互動遊戲
├── 現金流量表與財務數據視覺化分析工具.html          # Excel 財務分析與數據圖表
└── diet-plan/                                   # 飲食紀錄（獨立資料夾，含自己的 PWA 離線設定）
    ├── index.html
    ├── manifest.json
    ├── service-worker.js
    ├── icon-192.png
    └── icon-512.png
```

---

## 🚀 快速開始 (Quick Start)

### 方法 1：直接開啟
在檔案總管或訪達（Finder）中，直接雙擊開啟 `index.html` 即可開始使用。

### 方法 2：使用本機靜態伺服器 (推薦)
使用 Python 啟動輕量靜態伺服器：
```bash
# 在專案目錄下執行
python3 -m http.server 8080
```
隨後在瀏覽器造訪 [http://localhost:8080](http://localhost:8080) 即可完整體驗所有功能。

---

## 📄 授權說明
本作品集由 AI 協作開發，僅供學習展示與個人作品使用。
