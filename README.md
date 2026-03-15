# 🇬🇧 BizPulse — Universal UK Business Intelligence Dashboard

Upload **any** company's Excel or CSV — the dashboard auto-builds interactive charts, KPIs, sortable tables, and AI-powered insights instantly.

## 🚀 Deploy to GitHub Pages (3 steps)

1. Create a new **public** GitHub repository
2. Upload just **`index.html`** (that's the entire app — one file!)
3. **Settings → Pages → Source: main branch / root → Save**

Live in ~60 seconds at: **`https://YOUR-USERNAME.github.io/REPO-NAME/`**

## 📁 How to use

1. Go to **Import Data** → drag & drop any `.xlsx`, `.xls`, or `.csv`
2. Or click **"Load Gallagher Bassett Example"** to explore instantly
3. The dashboard auto-builds:
   - **KPI cards** — sums & averages of all numeric columns
   - **Bar chart** — first numeric column visualised
   - **Donut chart** — auto-grouped by categorical column
   - **Multi-line trend** — all numeric columns compared
   - **Distribution histogram** — data spread visualised
   - **Interactive Chart Builder** — pick any column, any chart type
   - **Sortable Data Table** — search, filter, paginate
   - **All Sheets** — every Excel sheet previewed
4. Use **✦ AI Analyst** (bottom-right) to ask questions about your data

## ✨ Features

| Feature | Details |
|---------|---------|
| Excel & CSV upload | .xlsx, .xls, .csv — multi-sheet Excel supported |
| Auto-detection | Numeric columns, label columns, categories — all auto-detected |
| Interactive charts | Bar, Line, Donut, Scatter — change type instantly |
| Sortable table | Click headers to sort, search all columns, pagination |
| AI Analyst | Floating chatbot — answers questions about YOUR data |
| Companies House | Live UK company search |
| UK APIs | 8 UK government & financial API integrations listed |
| Reports | Export full data, numeric summary, data quality CSV |
| UK Market Ticker | FTSE 100, GBP/EUR, BoE rate, UK CPI in live ticker |
| Responsive | Desktop, tablet, and mobile |

## 🤖 AI Analyst

- Works **offline** with smart built-in responses based on your data stats
- Works **live** with Claude AI when an API key is available
- Knows your uploaded data — rows, columns, numeric summaries, categories

## 📊 Compatible Data

Any spreadsheet works:
- Insurance claims data (like Gallagher Bassett example)
- Bank statements
- P&L / financial reports
- Sales data
- Payroll exports
- CRM exports
- Any CSV or Excel file

## 🏗 Tech Stack

- **Vanilla HTML/CSS/JS** — zero build tools, works everywhere
- **Chart.js 4.4** — interactive charts
- **PapaParse 5** — CSV parsing
- **SheetJS (XLSX)** — Excel parsing
- **GitHub Pages** — free hosting
- **Anthropic Claude API** — optional AI analysis
