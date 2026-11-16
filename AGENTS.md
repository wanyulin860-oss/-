# Japan Travel Memoir Project Guidelines (AGENTS.md)

## 1. 專案目的 (Project Purpose)
本專案是一個個人「日本旅遊回憶錄」網站，採用溫柔、粉嫩的日系美學風格（Sakura & Pastel Theme），記錄在日本各地（如大阪、京都等）的美食、景點與心情點滴。網站需支援響應式設計（RWD），並能順利部署至 GitHub Pages。

## 2. 網頁整體風格與設計規範 (Design System)
- **主色調 (Color Palette):**
  - 背景色：柔和的櫻花粉白（`#fdf2f4`）搭配奶茶色與米白色。
  - 主視覺/標題色：溫柔的玫瑰粉（`#d46a7e`）。
  - 字體色：柔和的深咖啡灰（`#4a4041`），營造溫暖感。
- **排版與圓角 (Typography & Shape):**
  - 區塊與卡片必須使用大圓角（`rounded-2xl` 或 `rounded-3xl`）與柔和陰影（`shadow-sm`）。
- **圖標與裝飾:**
  - 善用日系可愛的小裝飾（如 🌸、🍡、✨、📸、🍵 等 Emoji）。

## 3. 頁面結構 (Page Structure)
- `index.html`：首頁。包含浪漫的 Banner、關於這次旅程的簡介、精選景點與美食縮圖。
- `spots.html` (或後續擴充)：景點散步記錄。
- `food.html` (或後續擴充)：美食地圖記錄。

## 4. 檔案命名與放置規則 (File Naming & Directory)
- HTML 檔案放在專案根目錄。
- 圖片統一放在 `images/` 資料夾下，命名規則為英文小寫加連字號（例如 `kyoto-bamboo.jpg`）。
- CSS 樣式主要透過 Tailwind CSS (CDN) 快速建構。

## 5. AI 修改與新增內容規則 (AI Contribution Rules)
- 當要求新增一個景點或文章時：
  1. 必須維持上述的**粉嫩溫柔風格**與大圓角卡片設計。
  2. 結構需包含：小圖標、標題、日期/地點、簡短溫柔的心情描述。
  3. 確保程式碼乾淨、有適當的 RWD 響應式排版。
