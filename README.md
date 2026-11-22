# 光影相簿 Lumina Gallery

給 Android 平板／手機與 iPad 用的相簿 + 影片播放器。這裡只提供安裝檔，程式碼不公開。

👉 **[下載最新版本](../../releases/latest)**

## 功能

- **瀏覽**：時間軸網格（雙指縮放）、多種排序與照片／影片篩選、日期分組（可不分組讓畫面更緊密）、快速捲動、瀏覽時影片自動播放、相簿、影片分頁、照片地圖、HEIC／RAW／GIF／360° 全景
- **影片播放器**：亮度／音量／快轉手勢、倍速、字幕與音軌（含外掛字幕）、續播、播放模式（單部循環／循序／隨機）、雙指放大、音量增強、字幕大小顏色與時間差、A-B 重複、子母畫面、離開 App 時自動子母畫面或只播聲音（通知列控制）、截圖
- **管理**：多選、我的最愛、自訂相簿、標籤、隱藏、回收桶、加密私密相簿（PIN + 指紋／Face ID）、App 上鎖、動態照片／原況照片播放、備份與還原、App 內檢查更新
- **編輯與工具**：裁切旋轉、調色與濾鏡、無損影片剪輯、重複照片清理、幻燈片
- **本機 AI**（完全離線，照片不上傳）：用中文搜尋照片內容、人臉分群、自動回憶

介面：繁體中文／English。

## 安裝

### Android（Android 11 以上）

1. 下載 `Lumina-Gallery-x.x.x-android-arm64.apk`（舊型 32 位元裝置用 `armv7`）。
2. 點開檔案，依提示允許「安裝不明來源的應用程式」。
3. 若 Google Play 安全防護跳出警告，選「仍要安裝」（App 未上架商店，所以沒有商店驗證）。

### iPad／iPhone（iPadOS 16 以上）

iOS 版未簽名，需要用 Windows 或 Mac 電腦上的 [Sideloadly](https://sideloadly.io) 搭配自己的 Apple ID 安裝：

1. 安裝 iTunes（Windows 請用 Apple 官網版本）和 Sideloadly。
2. 下載 `Lumina-Gallery-x.x.x-ios-unsigned.ipa`。
3. iPad 用傳輸線接電腦並信任，把 `.ipa` 拖進 Sideloadly，輸入 Apple ID，按 Start。
4. iPad：「設定 → 一般 → VPN 與裝置管理」信任你的 Apple ID；並開啟「設定 → 隱私權與安全性 → 開發者模式」。

免費 Apple ID 安裝的 App 每 7 天要重新安裝一次（資料不會消失）。

## 注意事項

- AI 功能第一次使用時會下載模型（約 196 MB）。
- 人臉辨識模型（EdgeFace）授權為 CC BY-NC-SA 4.0，僅限非商業使用。
- 開源元件授權可在 App 的「設定 → 關於 → 開放原始碼授權」查看。
- 本 App 為個人作品，不提供任何保證。
