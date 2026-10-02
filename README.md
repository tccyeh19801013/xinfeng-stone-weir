# 新豐石滬網站

新竹縣新豐鄉石滬文化發展協會官方網站（靜態網頁）。

## 檔案
- `index.html`：網站首頁（單一檔案，CSS 與 JavaScript 已內嵌）
- `images/`：放置照片（例如 `images/hero.jpg`）

## 發布到 GitHub Pages
1. 在 GitHub 建立新的 repository（例如 `xinfeng-stone-weir`），設為 Public。
2. 上傳 `index.html` 與 `README.md`（Add file → Upload files → Commit changes）。
3. 進入 Settings → Pages，Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
4. 約 1–2 分鐘後，網址為 `https://<帳號>.github.io/xinfeng-stone-weir/`。

## 待補內容
搜尋 `[` 可找到所有待補的位置：主視覺照片、協會會址、Facebook 連結、其他夥伴、報名按鈕連結（目前為 `href="#"`）。

### 換上主視覺照片
把照片放到 `images/hero.jpg`，再將 index.html 中寫著「[主視覺照片…]」的那個 `<div>` 換成：
```html
<img src="images/hero.jpg" alt="退潮時的坡頭石滬群" style="width:100%;height:360px;object-fit:cover;border-radius:20px">
```
