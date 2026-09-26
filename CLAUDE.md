# Alphaguu-blog：給 Claude 的專案說明

這是「阿發」的部落格（alphaguu.com，WordPress）的內容工作區。阿發是住在紐西蘭奧克蘭的黃金獵犬，文章一律以阿發的第一人稱書寫。
這個 repo 只放內容與寫作規則；文章審稿後由 Patricia 手動貼到 WordPress 發佈。

## 開始寫任何文章前，先讀
1. `docs/persona-ah-fa.md`：阿發的個性、口吻、開場方式
2. `docs/columns.md`：7 個專欄各自的結構
3. `docs/writing-rules.md`：事實查核、格式、檔名、圖片規則
4. 寫「阿發黃金食譜」時另讀 `docs/recipe-illustration-brief.md`

## 不可違反的規則
- **語言**：繁體中文；人名、地名、專有名詞保留英文（例如 Auckland、Kākāpō），必要時附中文。
- **不可捏造事實**：價格、營業時間、地址、法規、票價、電話一律要有來源；查不到就寫「待確認」，不要猜。
- **不直接改 `main`**：所有新文章都放在新分支，開 Pull Request 讓 Patricia 檢查後才合併。
- **新文章一律 `draft: true`**，由 Patricia 決定何時發佈。
- **不放機密**：不要提交密碼、API key、`.env`、WordPress 匯出的 `.xml` 檔、訪客或留言者資料。
- **不放家人個資**：不寫孩子全名、學校、住家地址。文章裡只用「爸爸」「媽媽」。
- **食譜由 Patricia 提供**：不可自行創造或更改食譜份量、火候。
- 圖片：不要編造圖片網址。需要圖片的位置寫 `![說明文字](TODO-圖片)` 並註明建議拍什麼。

## 目前狀態
- 已從 WordPress 匯入 18 篇（16 篇已發佈、2 篇草稿）到 `content/posts/`，圖片仍連到 alphaguu.com。
- `2025-05-01-dog-ownership-nz.md` 內文在匯出時遺失（WordPress 可重複使用區塊），待補。
- 尚未決定：Shopify 商品如何嵌入文章（規劃中，見 README）。
