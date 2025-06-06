# MBTI 沒必要但挺搞的測驗網站

## 專案目標
建立一個極具娛樂性的偽 MBTI 人格測驗網站，透過幽默的問題和結果讓使用者在輕鬆氛圍中體驗「不太準確但很好笑」的人格分析。  
本網站採用純前端技術實作，適合部署至 GitHub Pages。

## 🎯 功能清單

### 1. MBTI 人格測驗 ✅
- 從題庫中隨機抽取 10 題問題進行測驗
- 每個問題提供兩個選項，對應不同人格標籤
- 根據答題結果計算出最符合的人格類型
- 提供詳細的（但不太準確的）人格分析報告
- 每種人格類型都提供專屬建議：
  - 今日建議
  - 情感建議
  - 工作/學業建議
  - 社交建議

### 2. 人格圖鑑 ✅
- 收錄所有可能的人格類型
- 每個類型都有：
  - 專屬表情符號
  - 幽默的人格描述
  - 性格特點分析圖表

### 3. 用戶評價區 ✅
- 展示「真實」用戶的搞笑回饋
- 呈現使用者的反應和吐槽
- 線上反饋功能：
  - 讓用戶提交個人反饋
  - 提供搞笑的系統回應
  - 支援繼續留言功能

### 4. FAQ 常見問題 ✅
- 回答用戶對測驗的疑問
- 以幽默方式解釋測驗的（不）準確性

### 5. 分享功能 ✅
- 透過網址分享測驗結果
- 生成包含人格類型的分享連結
- 帶入完整測驗結果內容
- 讓其他人可直接查看結果

## 🛠️ 技術規格

### 前端技術
- HTML5、CSS3、JavaScript（純前端實作）
- 響應式設計，支援各種螢幕尺寸

### 使用套件
- `Bootstrap 5.3.0`：介面框架與排版
- `Chart.js`：繪製人格分析圖表
- `Google Fonts`：使用 Noto Sans TC 字體

### 資料存儲
- 題庫使用 CSV 檔案儲存
- 人格類型定義在前端 JavaScript 中

## 🎨 介面設計

### 配色方案
- 主要背景：#1e1e2d
- 次要背景：#2b2b3d
- 強調色：#7c3aed
- 文字顏色：#ffffff

### 頁面結構
- 導航欄：測驗、人格圖鑑、用戶評價、FAQ
- 測驗頁面：
  - 開始頁
  - 問題頁（含進度條）
  - 結果頁（含圖表）
- 響應式卡片設計
- 深色主題

## ⏳ 開發進度

- [x] 建立專案規格文件
- [x] 實作基礎頁面架構
- [x] 完成測驗功能
- [x] 實作人格圖鑑
- [x] 新增用戶評價
- [x] 完成 FAQ 區域
- [x] 美化介面與動畫
- [x] 測試與優化
- [x] 實作人格專屬建議功能
- [x] 新增線上反饋系統
- [x] 完成結果分享功能

## 📊 題庫規格

- 總題數：100 題
- 題型：雙選項
- 每題包含：
  - 問題內容
  - 選項 A 與標籤
  - 選項 B 與標籤
- 標籤類型：
  - 沒救、裝懂、自戀、懶鬼
  - 戲精、混亂

## ⚠️ 注意事項

- 本測驗純屬娛樂，結果僅供參考
- 保持幽默感但不失專業外表
- 避免使用可能冒犯他人的描述
- 鼓勵分享但提醒使用者別太認真

最後更新：2025/6/5

