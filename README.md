📈 Real-Time Stock Dashboard
A dynamic web application built using Streamlit that allows users to monitor real-time stock data, analyze price charts, and apply technical indicators — all in one place.

🚀 Features
🔎 Search for any stock using its ticker symbol (e.g., AAPL, GOOGL, AMZN)

📊 Choose between Candlestick and Line chart types

⏱️ Select from various time periods: 1d, 5d, 1mo, 3mo, 6mo, 1y, 5y, max

📐 Add technical indicators:

Simple Moving Average (SMA 20)

Exponential Moving Average (EMA 20)

Relative Strength Index (RSI 14)

📉 View historical OHLC (Open, High, Low, Close) and volume data

🔄 Real-time mini price tracker for popular stocks in the sidebar

🌐 Timezone-aware formatting for better clarity

🧰 Built With
Streamlit — Python web app framework

Plotly — Interactive charting

yFinance — Yahoo Finance API wrapper

Pandas — Data manipulation

TA-Lib via ta — Technical indicators

Datetime — Time manipulation and formatting

🖥️ How to Run Locally
Clone the Repository

bash
Copy
Edit
git clone https://github.com/tushant687/tushant687-Real-Time-Stock-Market-Dashboard.git 
cd stock-dashboard
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the App

bash
Copy
Edit
streamlit run stock_dashboard.py
📷 Screenshots
Add optional screenshots here to showcase the dashboard UI.

📁 File Structure
bash
Copy
Edit
stock_dashboard.py      # Main Streamlit app script
requirements.txt        # Python dependencies (you should create this)
README.md               # Project overview (you're reading it!)
📦 Example requirements.txt
Here’s what you might include:

nginx
Copy
Edit
streamlit
yfinance
pandas
plotly
ta
pytz
📝 License
MIT License. See LICENSE for details.
