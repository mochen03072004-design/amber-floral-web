# GitHub Pages 部署教學

## 方法一：用 GitHub 網頁上傳

1. 登入 GitHub。
2. 建立一個新的 Repository。
3. Repository 名稱可用：`amber-floral`。
4. 選擇 `Public`。
5. 建立完成後，點選 `uploading an existing file`。
6. 上傳這些檔案：
   - `index.html`
   - `styles.css`
   - `.nojekyll`
   - 整個 `assets` 資料夾
7. 點選 `Commit changes`。
8. 到 `Settings > Pages`。
9. Source 選 `Deploy from a branch`。
10. Branch 選 `main`，資料夾選 `/ (root)`。
11. 儲存後等待 1 到 3 分鐘。

## 方法二：如果之後安裝 Git

```bash
git init
git add .
git commit -m "Deploy Amber floral website"
git branch -M main
git remote add origin https://github.com/你的帳號/amber-floral.git
git push -u origin main
```

接著一樣到 `Settings > Pages` 啟用 GitHub Pages。

