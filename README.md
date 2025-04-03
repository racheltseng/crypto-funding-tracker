# crypto-funding-tracker
這是一個自動收集區塊鏈領域每日最新融資情況的工具，幫助用戶篩選：  有名牌投資機構（如 a16z、Sequoia、Paradigm）參與的項目  可能有激勵空投 的潛力項目
crypto-funding-tracker/
│── data/                     # 存放每日的 JSON/CSV 數據
│── scripts/                   # 爬取 & 分析的腳本
│   ├── scraper.py             # 爬取最新區塊鏈投資數據
│   ├── filter.py              # 篩選知名投資機構的項目
│   ├── airdrop_detector.py    # 分析哪些項目可能有空投
│── api/                       # API 端（如果需要）
│── frontend/                  # 前端（如果需要）
│── README.md                  # 項目介紹
│── requirements.txt           # 依賴（Python）
│── package.json               # 依賴（Node.js，如果用 JS）
│── .github/workflows/         # CI/CD（可選）
