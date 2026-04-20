# 網站專案背景：明心櫞 主頁

## 我是誰

我叫黃家盈 Shirley，香港心理學會（HKPS）註冊輔導心理學家，現正修讀輔導心理學博士。超過十年臨床經驗，專注兒童及青少年心理、情緒輔導、生涯規劃、親職諮詢、輔導督導與培訓。我現時**不接受新個案**，此網站定位為個人專業品牌展示及文章發佈平台。

## 網站結構

此 repo（`shirleycounpsy.github.io`）係**主頁**，獨立於文章知識庫。

```
shirleycounpsy.github.io/   ← 你而家喺呢度
├── index.html              ← 主頁
├── images/
│   ├── hero.jpg
│   ├── book1.jpg
│   ├── book2.jpg
│   ├── book3.jpg
│   └── profile.jpg     ← 個人照片，只用於「關於我」頁面
└── CLAUDE.md

/Users/shirley/quartz/      ← 另一個 repo，Quartz 文章知識庫（分開的）
```

主頁入面「閱讀文章」等按鈕，將來會連結去 Quartz 知識庫的 GitHub Pages URL。

## 設計方向

**色調：** 溫暖大地色系
- 主色：玫瑰粉 `#C9A99A`
- 輔色：鼠尾草綠 `#8FAF8A`
- 底色：暖米白 `#FBF6F0`
- 深色文字：`#3D3330`

**字款：**
- 標題：Shippori Mincho B1（Google Fonts）
- 內文：Zen Maru Gothic（Google Fonts）

**風格：** 溫暖、文青、專業、以文字為主、配圖為輔。避免大張相片佔滿頁面的設計，因為中文字密，英文網站那種全圖 hero 排版換成中文會顯得擠。

**語言：** 繁體中文（香港書面語），唔係廣東話口語，唔係簡體中文。

## 主頁內容區塊

1. **導航欄**：網站名「明心櫞」、連結去知識庫
2. **介紹區**：簡短自我介紹
3. **專業範疇**：兒童及青少年心理、情緒輔導、生涯規劃與自我探索、親職諮詢、輔導督導與培訓
4. **著作**：三本書（book1-3.jpg），連結去購買頁
   - 《一念間》（2025）萬里機構
   - 《與孩同行》（2023）新雅
   - 《心理學家的工具箱》（2021）萬里機構
5. **文章庫入口**：連去 Quartz 知識庫
6. **頁尾**：Instagram 連結 [@shirley.counsellingpsy](https://www.instagram.com/shirley.counsellingpsy)

## 重要限制

- **唔加聯絡表單或預約功能**（現時不接新個案）
- **主頁唔放個人照片**，用植物或輔導室風格圖片；個人照片（`images/profile.jpg`）只放喺「關於我」頁面，搭配個人簡介使用
- 所有文字用繁體中文，避免簡體字及台灣用語（例如用「特質」唔用「素質」）

## 技術細節

- 純 HTML + CSS，唔用任何框架
- 字款從 Google Fonts 載入
- 圖片放喺 `images/` folder
- Deploy 去 GitHub Pages：`https://shirleycounpsy.github.io`
- 改完記得 `git add . && git commit -m "描述" && git push`
