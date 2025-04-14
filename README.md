# 📊 YFinance Stock Analysis (5-Year Monthly)

This project uses [yfinance](https://github.com/gauravvxv/yfinance) to download 5 years of historical stock data from Yahoo Finance, resamples it to monthly frequency, and saves it to an Excel file with each stock on a separate sheet.

---

## 🚀 Features

- 📈 Download 5 years of daily stock data
- 🗓️ Resample to monthly 
- 📂 Save each stock’s data to a separate Excel sheet
- 💾 Google Colab friendly (with Google Drive support)

---

1. Open the notebook in Google Colab: [yfinance_colab.ipynb](notebook/yfinance.ipynb)
2. Mount your Google Drive
3. Upload your Excel file with stock tickers (e.g., `tickers.xlsx`)
4. Run all cells
5. Download the output Excel file (`monthly_data.xlsx`) from your Drive

---

## 🛠️ Requirements

Only needed if running outside Colab:

```bash
pip install yfinance openpyxl pandas
