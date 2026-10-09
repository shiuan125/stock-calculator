# 台股交易損益試算器 (Taiwan Stock P&L Calculator)

An interactive and lightweight web application for calculating Taiwan stock trading profits, losses, transaction fees, and breakeven prices in real time.

直覺、快速的台股交易損益試算工具，支援券商折數設定、證交稅率調整、零股與整股手續費規範，並即時計算損益兩平價與折抵省下的費用金額。

🔗 **線上試算體驗 (Live Demo)**：[https://shiuan125.github.io/stock-calculator/](https://shiuan125.github.io/stock-calculator/)

---

## ✨ 特色功能 (Features)

* ⚡ **即時動態計算**：輸入買價、賣價與股數，即時更新預估損益與報酬率 (ROI)。
* 💰 **券商折扣與省費提示**：
  * 支援自訂手續費折數（如 2.8 折、3 折、2 折等快速選單）。
  * 費用明細中標示手續費未打折的「原價」，並特別計算「折扣共省下多少錢」。
* 📊 **多種交易稅率支援**：
  * 一般股票 (0.3%)
  * 現股當沖 (0.15%)
  * ETF 交易 (0.1%)
* 🎯 **精確計價與規範**：
  * 完全遵循台股規則，採**無條件捨去**計算手續費與證交稅。
  * 自動判斷整股（基本最低手續費 20 元）與零股（未滿 1,000 股法定最低 1 元）手續費門檻。
* ⚖️ **損益兩平價與成本試算**：自動算出每股平均買進成本，以及預估需要賣在多少價格才能不虧損（損益兩平點）。
* 📱 **響應式介面 (RWD)**：簡潔現代化的 UI 設計，不論電腦或手機皆能流暢使用。

---

## 🛠️ 技術規格 (Tech Stack)

本專案採用純前端 Single File (SPA) 架構，無需架設後端伺服器或安裝建置工具：

* **Core Framework**: [React 18](https://react.dev/) (via UMD CDN)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/) (via CDN)
* **Compiler**: [Babel Standalone](https://babeljs.io/) (前端即時編譯 JSX)
* **Deployment**: [GitHub Pages](https://pages.github.com/)

---

## 🚀 如何使用與部署 (Setup & Deployment)

### 本地開啟
只需下載本儲存庫中的 `index.html` 檔案，用任何瀏覽器雙擊開啟即可運作！

### 部署至 GitHub Pages
1. 將本專案 Fork 或 Clone 至您的 GitHub 帳號。
2. 確保 `index.html` 放在儲存庫的根目錄 (Root Directory)。
3. 進入 GitHub 儲存庫的 **Settings** > **Pages**。
4. 在 **Build and deployment** > **Source** 選擇 `Deploy from a branch`。
5. 將 Branch 設為 `main` (或 `master`)、資料夾設為 `/ (root)` 並儲存。
6. 等待 1~2 分鐘即可完成上線。

---

## ⚠️ 免責聲明 (Disclaimer)

* 本工具之計算結果僅供參考與交易規劃使用，實際交割金額、手續費與證交稅請以您開戶券商之每日對帳單為準。
* 券商手續費最低門檻與計算規則可能依各家券商規定或活動優惠而有所不同。

---

⭐️ 如果這個工具對你有幫助，歡迎點個 **Star** 鼓勵支持！
