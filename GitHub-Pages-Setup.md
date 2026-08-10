# 🚀 GitHub Pages 設定指南

## 📋 您已完成：
- ✅ 建立了 GitHub repository: `LON`
- ✅ Google 表單整合已設定完成

---

## 🎯 接下來的步驟

### 步驟 1：上傳檔案到 GitHub

#### 方法 A：使用 Git 指令（推薦）

1. **開啟終端機**（在專案資料夾中）

2. **初始化 Git（如果還沒有的話）**
```bash
git init
```

3. **添加遠端 repository**
```bash
git remote add origin https://github.com/您的用戶名/LON.git
```
**注意：** 將「您的用戶名」替換成您的 GitHub 用戶名

4. **添加所有檔案**
```bash
git add index.html records.html script.js styles.css
```

5. **提交變更**
```bash
git commit -m "Initial commit: LON landing page with Google Forms integration"
```

6. **推送到 GitHub**
```bash
git branch -M main
git push -u origin main
```

---

#### 方法 B：使用 GitHub 網頁介面（簡單）

1. **前往您的 repository**
   - 網址：`https://github.com/您的用戶名/LON`

2. **上傳檔案**
   - 點擊「Add file」→「Upload files」
   - 拖曳以下 4 個檔案：
     - ✅ `index.html`
     - ✅ `records.html`
     - ✅ `script.js`
     - ✅ `styles.css`

3. **提交**
   - 在底部輸入 commit 訊息：`Add landing page files`
   - 點擊「Commit changes」

---

### 步驟 2：啟用 GitHub Pages

1. **前往 Settings**
   - 在 repository 頁面，點擊「Settings」標籤

2. **找到 Pages 設定**
   - 左側選單點擊「Pages」

3. **設定來源**
   - **Source**: 選擇「Deploy from a branch」
   - **Branch**: 選擇「main」
   - **Folder**: 選擇「/ (root)」
   - 點擊「Save」

4. **等待部署**
   - 等待 1-2 分鐘
   - 頁面會顯示：「Your site is live at...」

---

### 步驟 3：取得網址

您的網站網址會是：
```
https://您的用戶名.github.io/LON/
```

例如，如果您的 GitHub 用戶名是 `john123`，網址就是：
```
https://john123.github.io/LON/
```

---

### 步驟 4：測試網站

1. **開啟網址**
   - 在瀏覽器開啟 `https://您的用戶名.github.io/LON/`

2. **測試表單**
   - 點擊「我要優惠」
   - 填寫測試資料
   - 提交

3. **確認 Google 表單**
   - 開啟 Google 表單
   - 查看「回應」
   - 確認資料有進入

---

### 步驟 5：分享給客戶

#### 📱 直接分享網址
```
https://您的用戶名.github.io/LON/
```

#### 🔗 縮短網址（可選）
使用以下服務縮短網址：
- [bit.ly](https://bitly.com)
- [reurl.cc](https://reurl.cc)
- [tinyurl.com](https://tinyurl.com)

例如：`https://bit.ly/my-ai-sales`

#### 📲 建立 QR Code（可選）
1. 前往 [QR Code Generator](https://www.qr-code-generator.com)
2. 輸入您的網址
3. 下載 QR Code
4. 可以印在名片、傳單上

---

## 🔄 更新網站

當您修改程式碼後，重新上傳：

### 使用 Git：
```bash
git add .
git commit -m "Update website"
git push
```

### 使用網頁介面：
1. 前往 repository
2. 點擊檔案
3. 點擊編輯圖示（鉛筆）
4. 修改內容
5. Commit changes

**更新後等待 1-2 分鐘，網站會自動更新**

---

## 📊 查看網站狀態

### 檢查部署狀態
1. 前往 repository 主頁
2. 點擊「Actions」標籤
3. 查看最新的部署狀態
4. 綠色勾勾 = 部署成功

---

## 🎯 完整工作流程

```
1. 客戶收到您的網址
   ↓
2. 客戶開啟網站（GitHub Pages）
   ↓
3. 客戶填寫表單
   ↓
4. 資料自動傳送到您的 Google Sheets
   ↓
5. 您收到通知（如果有設定）
   ↓
6. 您查看 Google Sheets 聯繫客戶
```

---

## ⚠️ 重要提醒

### ✅ 要做的事：
- ✅ 定期檢查 Google Sheets
- ✅ 設定 Google Sheets 通知
- ✅ 備份客戶資料
- ✅ 測試網站在不同設備上的顯示

### ❌ 不要做：
- ❌ 不要把 repository 設為 Private（GitHub Pages 需要 Public）
- ❌ 不要分享 GitHub repository 連結（分享 GitHub Pages 網址）
- ❌ 不要忘記測試表單功能

---

## 🆘 常見問題

### Q: 為什麼看不到網站？
**A:** 
1. 確認已啟用 GitHub Pages
2. 等待 1-2 分鐘讓部署完成
3. 檢查 Actions 標籤的部署狀態

### Q: 網址是什麼？
**A:** 
```
https://您的GitHub用戶名.github.io/LON/
```
用戶名要全小寫

### Q: 可以用自己的網域嗎？
**A:** 可以！
1. Settings → Pages
2. Custom domain
3. 輸入您的網域
4. 設定 DNS

### Q: 如何更新網站？
**A:** 
1. 修改檔案
2. 重新 push 到 GitHub
3. 等待 1-2 分鐘自動部署

### Q: 網站是免費的嗎？
**A:** 是的！GitHub Pages 完全免費

---

## 🎉 完成檢查清單

部署前確認：
- [ ] 所有 4 個檔案已上傳
- [ ] GitHub Pages 已啟用
- [ ] 網站可以正常訪問
- [ ] 表單提交功能正常
- [ ] Google 表單收到測試資料
- [ ] 已設定 Google Sheets 通知
- [ ] 已測試手機版顯示

全部完成後：
- [ ] 取得完整網址
- [ ] 縮短網址（可選）
- [ ] 建立 QR Code（可選）
- [ ] 開始分享給客戶！

---

## 📞 需要協助？

如果遇到問題：
1. 檢查 GitHub Actions 的錯誤訊息
2. 確認所有檔案都已上傳
3. 等待幾分鐘再重試
4. 清除瀏覽器快取

---

祝您使用愉快！🚀

