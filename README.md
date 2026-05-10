# 家族相冊 📷

一個復古懷舊風格的家族老照片網站，支援分類瀏覽與幻燈片播放。

## 功能

- 📸 **照片格網** — 復古相框樣式，滑鼠懸停可放大預覽
- 🗂️ **年代分類** — 依年代篩選照片
- 🎞️ **幻燈播放** — 全螢幕幻燈片，支援自動播放
- 🖼️ **Lightbox** — 點擊照片放大查看
- 📱 **響應式設計** — 手機平板均可正常瀏覽

## 如何新增照片

### 1. 建立照片資料夾

```
family-gallery/
├── index.html
├── photos.js
├── README.md
└── photos/
    ├── 1950s/
    ├── 1960s/
    ├── 1970s/
    └── ...
```

### 2. 編輯 `photos.js`

```js
const PHOTOS = [
  {
    src:   "photos/1960s/grandma.jpg",  // 照片路徑
    title: "阿嬤的青春",                // 照片標題
    year:  "1965",                      // 拍攝年份
    era:   "1960年代",                  // 年代分類（用於篩選）
    desc:  "攝於台南老家門口"            // 說明文字（選填）
  },
  // ... 更多照片
];
```

### 3. 上傳至 GitHub Pages

1. 建立 GitHub Repository
2. 上傳所有檔案（含 `photos/` 資料夾）
3. 進入 **Settings → Pages**
4. Source 選擇 **Deploy from a branch**，Branch 選 `main`
5. 幾分鐘後即可透過 `https://你的帳號.github.io/repository名稱` 訪問

## 照片格式建議

| 項目 | 建議 |
|------|------|
| 格式 | JPG（壓縮率高） |
| 寬度 | 1200–2000px |
| 檔案大小 | 單張不超過 2MB |
| 掃描解析度 | 300 DPI |
| 命名方式 | `1965_grandma_wedding.jpg`（避免中文、空格） |

GitHub Pages 免費空間為 1GB，足夠存放數百張高畫質照片。

---

*歲月如歌，記憶永存。*
