# The Wild Unknown Tarot Reference — 第一版

這是一個免費靜態網站範本，第一階段收錄 Wands（權杖）14 張牌的英文與繁體中文對照。

## 本機預覽
1. 將 `index.html` 和 `cards.js` 放在同一個資料夾。
2. 直接用瀏覽器開啟 `index.html` 即可預覽。

## 免費發布到 GitHub Pages
1. 登入 GitHub，建立新的 Repository。
2. Repository 名稱可用 `wild-unknown-tarot`。
3. 可選擇 Public（GitHub Pages 免費方案通常使用公開 Repository）。
4. 將 `index.html`、`cards.js` 上傳到 Repository 根目錄。
5. 進入 Repository 的 Settings → Pages。
6. 在 Build and deployment 選擇 `Deploy from a branch`。
7. Branch 選 `main`，資料夾選 `/(root)`，按 Save。
8. 等待發布完成，GitHub Pages 會顯示網址，通常形式為 `https://你的帳號.github.io/wild-unknown-tarot/`。
   請以 Pages 頁面實際顯示的網址為準。

## 重要說明
- 牌面圖片目前是預留圖框，尚未放入原版牌圖。請只使用你有權使用或已取得授權的圖片。
- `cards.js` 存放牌義資料；修改文字時請保留合法的 JavaScript 陣列格式。
- 此版本不含會員、雲端同步、抽牌或 AI API，不需要伺服器端服務。
- 公開網站中的檔案與文字可被訪客讀取；不要放入私人資料、密碼或 API 金鑰。
- 來源文字檔中有兩處疑似文字辨識錯誤：`sin of wands` 應核對是否為 `son of wands`；`ten of wands` 的標題出現在 Father of Wands 段落前，發布前建議與原書核對。


版本 V2 更新：
- 六個主選單均可點擊並顯示牌組介紹。
- Major Arcana、Minor Arcana 介紹與 Court Cards／四個家族說明加入繁體中文翻譯。
- Wands 仍保留 14 張牌的搜尋與中英牌義閱讀。
- Cups、Swords、Pentacles 目前提供介紹文字，牌卡資料尚未加入。
- 圖片仍為預留位置，請使用有權使用或已取得授權的圖片。


## 版本更新：加入 Ten of Wands 圖片
- 已加入 ten-of-wands.png，並配對到 Ten of Wands（權杖十）。
- 上傳更新時，請把 index.html、cards.js、README.txt、ten-of-wands.png 一起放在 Repository 根目錄。


## V4 手機閱讀優化
- 手機版導覽選單改為可橫向滑動。
- 牌卡列表改為雙欄卡片，方便手機瀏覽。
- 牌義詳細頁新增繁體中文、English、中英對照切換；手機預設先顯示繁體中文，減少長頁面滑動。
- 桌機仍會同時顯示中英文。


## V5 更新：手機直向閱讀
- 手機主選單改為直向排列，不再需要左右滑動。
- 手機頁面以垂直捲動為主，選單不固定在頂部，避免佔用閱讀空間。
- 保留手機牌義閱讀版型與權杖十圖片。
- 已保留 noindex 指示，請注意這不是存取密碼保護，也不能保證搜尋引擎即時移除舊索引。


## V7：權杖牌組實拍圖整合
- 已加入 14 張權杖牌的照片，裁切桌面背景、統一比例並壓縮，以利手機載入。
- 每張圖片已配對到對應牌卡，點選牌卡可在詳情頁查看大圖。
- 上傳時請將本壓縮檔內所有檔案（index.html、cards.js、README.txt 及 14 張 JPG）一併放到 GitHub Repository 根目錄。
- 本次為裁切桌面背景與影像優化，不會改變牌面本身的繪畫內容。


V7 更新：已移除頁面中的牌名／關鍵字搜尋欄，權杖牌組改為直接顯示全部 14 張牌。
