# Midnight

[Midnight](htttps://github/cheetosysst/midnight) 是一個幫助您準備駕照筆試的工具

本專案中的駕照考試題目來源為[中華民國交通部公路總局](https://www.thb.gov.tw/News_Download.aspx?n=284&sms=12823)，相關細節以及最新題庫內容，請詳閱相關官方網站資訊，本工具僅供練習參考使用。

## 開發 Developing

首先，請確保您的電腦上已經安裝了 [Node.js](https://nodejs.org/) 和 [pnpm](https://pnpm.js.org/)。

接著，請下載本專案。

```bash
git clone git@github.com:cheetosysst/midnight.git
```

然後，進入專案資料夾。

```bash
cd midnight
```

再來，請安裝相依套件。

```bash
npm install -g pnpm

# or 

pnpm install
```

最後，啟動開發伺服器。

```bash
npm run dev

# or

pnpm run dev
```

### TODO

- 完整題庫
- 檢查和顯示答案
- 計算分數
- 部屬
- 多語言支援
- 無障礙

歡迎提交 PR 和 Issue
