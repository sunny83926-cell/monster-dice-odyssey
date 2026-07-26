# Monster Dice Odyssey v0.71 — GitHub Pages / Mobile

這個資料夾可直接放到 GitHub repository 的根目錄。

## GitHub Pages 發布
1. 建立新的 GitHub repository，例如 `monster-dice-odyssey`
2. 上傳本資料夾中的 `index.html`
3. GitHub repository → Settings → Pages
4. Build and deployment 選 `Deploy from a branch`
5. Branch 選 `main`、資料夾選 `/ (root)`，按 Save
6. 發布完成後網址通常為：
   `https://你的GitHub帳號.github.io/monster-dice-odyssey/`

## 本版修改
- 保留原 v0.71 單檔 HTML 與遊戲核心邏輯
- 移除手機上 1000–1260px 強制桌面寬度的實際影響
- 手機棋盤自適應 13×13
- 手機隱藏左右戰況 HUD，保留核心戰場
- 骰子、控制列、候補怪獸與編成畫面改為手機排列
- 增加觸控操作與 iOS Safari 點擊處理
- 不需要額外 assets，GitHub Pages 只放 `index.html` 即可

桌面版仍沿用原本版面；手機版透過最後一層 responsive CSS 覆蓋。
