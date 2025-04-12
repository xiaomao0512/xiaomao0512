# 去中心化房屋租賃平台 Dapp

> 專題作品 ｜ 黃贊倫  
> 致理科技大學 資訊管理系（預計 115 年畢業）

## 📌 專案介紹
打造去中心化的房屋租賃平台，模擬房東房客流程，實現房源上鏈、交易透明、用戶驗證等核心功能。專案包含前端 UI/UX 設計、錢包串接、鏈上交易與憑證驗證流程。

## 🛠 技術棧
- **前端框架**：React, TypeScript, TailwindCSS v3
- **區塊鏈技術**：Solana Web3.js, SPL Token, Phantom Wallet
- **工具鏈**：Vite v6, Node.js Polyfill, ESLint, React DevTools
- **其他**：Switchboard 預言機（模擬）, FastAPI（待接入）

## 🎯 我的角色
專案前端開發負責人，主要負責：
- 規劃與實現完整平台 UI/UX，打造響應式使用者體驗
- 整合 Phantom 錢包，實現用戶錢包連接與 SOL 測試代幣交易
- 解決 Vite v6 開發環境兼容性問題，確保 Web3.js + SPL Token 成功執行
- 設計「租房前驗證」模擬流程，串接模擬後端 FastAPI 接口
- 規劃前後端數據互動架構，預留上鏈存證與預言機交互接口

## 💡 成果亮點
- ✅ 成功解決開發環境 Polyfill 問題，Web3.js + SPL Token 完整運行
- ✅ 完成用戶驗證 → 錢包支付 → 租賃流程，符合實戰 Dapp 應用場景
- ✅ 良好的專案架構，具備後續擴展實際後端與上鏈功能的能力

## 🔗 專案代碼庫
[GitHub Repository](https://github.com/xiaomao0512)

## 🖼️ 預覽畫面
- 房源列表頁面（桌面端 / 手機端適配）
- 房源詳情彈窗 + 錢包支付簽名流程
- 用戶驗證流程畫面（模擬）
