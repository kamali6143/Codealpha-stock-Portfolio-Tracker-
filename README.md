📈 Stock Portfolio Tracker

A simple Python program to track your stock investments.
This project helps you add, update, and manage stock holdings, while keeping track of shares and their latest prices.

🚀 Features
Add stocks with ticker symbol, number of shares, and price.

Update existing stock prices.

Track total shares held for each stock.

View your portfolio summary.

🛠️ Installation

1. Clone the repository:

git clone https://github.com/your-username/stock-portfolio-tracker.git
cd stock-portfolio-tracker


2. Make sure you have Python 3.8+ installed.

📊 Example Usage

portfolio = StockPortfolio()

# Add stocks
portfolio.add_stock("AAPL", 10, 150)
portfolio.add_stock("GOOGL", 5, 2800)

# Update stock
portfolio.add_stock("AAPL", 5, 155)

# View portfolio
portfolio.view_portfolio()

Output:

10 shares of AAPL added at $150 each.
5 shares of GOOGL added at $2800 each.
5 shares of AAPL added at $155 each.
Portfolio:
AAPL: 15 shares at $155 each
GOOGL: 5 shares at $2800 each
