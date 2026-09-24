# Seer Assets

這是用來存放《賽爾號》精靈圖示的靜態資源庫，主要作為巴哈姆特論壇發文用的圖床 (CDN)。專案內包含自動將圖片清單轉換為 Markdown 表格語法的腳本。

## 📂 目錄結構

* `images/`：存放所有從 Google 試算表匯出的精靈小圖示（請確保檔名為英文或數字）。
* `generate_table.py`：負責讀取 `images/` 目錄並自動組合 Markdown 語法的執行腳本。

## 🚀 如何產生巴哈姆特表格

1. 將新的精靈圖示放入 `images/` 資料夾，並推送到 GitHub。
2. 在本地端終端機執行轉換腳本：
   ```bash
   python generate_table.py