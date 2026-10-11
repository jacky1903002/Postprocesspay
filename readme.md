\# 後處理論件計酬金額統計系統 (Post-Process Piece-Rate Statistics System)



\[!\[Status](https://img.shields.io/badge/Status-Production%20Ready-success)]()

\[!\[Firebase](https://img.shields.io/badge/Backend-Firebase%2010-orange)]()

\[!\[Bootstrap](https://img.shields.io/badge/UI-Bootstrap%205-purple)]()

\[!\[License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)



一個專為製造業與工廠後處理產線設計的\*\*企業商業版論件計酬與財務管理系統\*\*。本系統整合了雲端即時協作、動態試算表、自動化公式運算、多維度商業圖表分析及完整的 Excel 雙向匯入匯出功能。



\---



\## 🚀 核心特色 (Key Features)



\* \*\*🔐 Firebase 雲端即時同步與驗證\*\*\[cite: 1]：

&#x20; \* 支援帳號密碼安全登入控制。

&#x20; \* 結合 Realtime Database，實現多使用者、多工位同時檢視與即時儲存狀態追蹤\[cite: 1]。

\* \*\*⚡ 雙擊即時編輯與自動化公式\*\*\[cite: 1]：

&#x20; \* 支援表格儲存格\*\*雙擊（DblClick）即時編輯\*\*與快速鍵儲存\[cite: 1]。

&#x20; \* 內建自動化商業邏輯：後處理工時變動時自動換算單價（$\\text{單價} = 250 \\times \\text{工時}$）、即時計算預計/實際總價與完成率\[cite: 1]。

\* \*\*📊 6 大商業分析圖表\*\*\[cite: 1]：

&#x20; \* 內建互動式 Chart.js 儀表板，提供品號數量、實際發放金額、作業人員分佈（具備 DataLabels 數值標籤）、各週完成率及累計工時統計\[cite: 1]。

&#x20; \* 支援單張圖表或\*\*一鍵批次匯出所有 6 張圖表為高畫質 PNG 檔案\*\*\[cite: 1]。

\* \*\*📁 靈活的工作表與入金管理\*\*\[cite: 1]：

&#x20; \* 支援動態新增與刪除工作表分頁（如 `W1`, `W2`...）\[cite: 1]。

&#x20; \* 獨立「入金與剩餘金額管理」分頁，精準追蹤企業預先入金總額與實際發放金額之差額，資金流向一目了然\[cite: 1]。

\* \*\*📥 Excel 雙向相容\*\*\[cite: 1]：

&#x20; \* 完整支援透過 SheetJS (`xlsx`) 匯入現有 Excel 試算表，或一鍵將所有分頁與簽收欄位匯出為正式報表\[cite: 1]。



\---



\## 💻 技術架構 (Tech Stack)



\* \*\*前端介面\*\*：HTML5, CSS3, JavaScript (ES6+ Module)

\* \*\*UI 框架\*\*：Bootstrap 5, FontAwesome 6 圖標庫\[cite: 1]

\* \*\*資料庫與驗證\*\*：Firebase v10 (Auth \& Realtime Database)\[cite: 1]

\* \*\*資料視覺化\*\*：Chart.js \& Chart.js DataLabels Plugin\[cite: 1]

\* \*\*試算表處理\*\*：SheetJS (XLSX)\[cite: 1]



\---



\## ⚙️ 快速上手與部署 (Quick Start)



1\. \*\*Clone 本專案\*\*：

&#x20;  ```bash

&#x20;  git clone \[https://github.com/你的帳號/post-process-payment-system.git](https://github.com/你的帳號/post-process-payment-system.git)

