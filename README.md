# World Music History｜世界音樂歷史博物館

以繁體中文探索世界音樂的歷史、文化脈絡、流派與代表人物。網站使用原生 HTML / CSS / JavaScript，可直接部署至 GitHub Pages。

## 本機預覽

直接用瀏覽器開啟 `index.html` 即可。若要使用本機伺服器，可在專案資料夾執行：

```bash
python -m http.server 8000
```

再開啟 `http://localhost:8000`。

## 網站頁面

- `index.html`：首頁
- `timeline.html`：互動時間軸與搜尋
- `eras.html`：音樂歷史時期
- `genres.html`：世界音樂流派
- `people.html`：音樂人物

## GitHub Pages 部署

1. 將整個資料夾內容上傳至 GitHub repository 根目錄。
2. 進入 repository 的 **Settings → Pages**。
3. 在 **Build and deployment → Source** 選擇 **GitHub Actions**。
4. 推送到 `main` 分支後，workflow 會自動部署。
5. 部署完成後，在 Settings → Pages 查看網站網址。

## 專案規則
請先閱讀 [`AGENTS.md`](AGENTS.md)。未來要新增年代、人物或流派時，依照其中的內容、設計與驗證規則執行。

## 內容與來源
網站是入門導覽與選例，不是完整或排名式的世界音樂史。重要脈絡參考 Smithsonian、Carnegie Hall、Oxford University Press 等公開教育資源；個別事件與年代應以頁面所列來源進一步查證。
網站部署測試。
