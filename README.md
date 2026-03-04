# 研讀工具箱（Timothy's Bible Study Toolbox）

這是一個將我自己常用的 **jw.org / wol.jw.org 相關輔助工具** 集中在一起的入口頁面，方便在研讀時快速開啟各種小工具。  
⚠️ 本頁所列工具皆為個人製作，**與守望臺聖經書社 / jw.org 無官方關聯**。

目前收錄的工具有：

- Take URL：jw.org 影片網址批次擷取工具  
- 多影片字幕工具（Multi Video Subtitle）：jw.org 影片字幕批次下載工具  
- Take Article：守望台線上書庫文章擷取工具  
- HTML 合併工具：多個 HTML 檔案合併成單一檔案

---

## 線上頁面

這個專案是一個單純的前端頁面，部署在 GitHub Pages 上：

- 工具總覽入口頁（本專案）：  
  `https://timothy920611.github.io/Timothy-subtitle/`

### 各工具連結

- Take URL  
  `https://timothy920611.github.io/Take-URL/`

- 多影片字幕工具（Multi Video Subtitle）  
  `https://timothy920611.github.io/Multi-Video-Sutitle/`

- Take Article  
  `https://timothy920611.github.io/take-article/`

- HTML 合併工具  
  `https://timothy920611.github.io/merge-html-file/`

---

## 功能簡介

### 1. Take URL

從 jw.org 網站「多媒體圖書館」等頁面 **批次擷取影片網址** 的工具。

- 支援輸入 jw.org 類別列表頁，例如：  
  `https://www.jw.org/cmn-hant/多媒體圖書館/影片/#cmn-hant/categories/StudioMonthlyPrograms`
- 自動抓取該頁面底下所有影片的個別連結
- 適合要大量整理或下載特定分類影片連結時使用

---

### 2. 多影片字幕工具（Multi Video Subtitle）

針對多個 jw.org 影片，**一次批次擷取字幕** 的工具。

- 每一行輸入一個影片網址，一次最多 50 部
- 會自動抓取每支影片可用的字幕內容
- 可選擇下載為 `pdf`、`html`、`txt` 等格式，方便後續閱讀或整理

---

### 3. Take Article

「守望台線上書庫文章擷取閱讀器」。

- 輸入守望台線上書庫的目錄頁連結
- 自動擷取該目錄底下所有文章內容
- 可下載為 `txt` 或 `html` 檔案
- 方便離線閱讀、整理或搭配其他工具使用

---

### 4. HTML 合併工具（Merge HTML File）

將多個 HTML 檔快速合併成一個檔案的小工具。

- 支援拖曳多個 HTML 檔案
- 自動依序合併為單一 HTML 檔
- 適合將多篇文章或多個頁面整理成一本「電子小冊」保存

---

## 技術說明

- 純前端靜態頁面
- 使用 [Tailwind CSS](https://tailwindcss.com/) 做版面與樣式
- 使用 Google Fonts 的 `Noto Sans TC` 字型
- 不需要後端伺服器，使用 GitHub Pages 即可部署

---

## 聲明

- 所有工具皆為個人開發，僅供研讀與個人使用之輔助工具。
- 本專案 **並非** 守望臺聖經書社或 jw.org 官方產品，也未獲得任何官方授權。
- 使用時請遵守 jw.org、wol.jw.org 各自的使用條款與版權規定。
