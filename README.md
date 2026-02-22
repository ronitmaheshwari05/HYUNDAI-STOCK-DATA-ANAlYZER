# 📈 Hyundai Stock Data Analysis

Hyundai Stock Data Analysis is a beginner-friendly financial data exploration project built using Python, Pandas, NumPy, Matplotlib, and Seaborn. This project analyzes historical stock price data of Hyundai Motor Company and applies core data analysis techniques to understand price behavior, trading volume patterns, volatility trends, and correlations between financial variables.

This project was developed as part of my **Python Essentials for MLOps** learning journey and focuses on practical implementation of core data analytics concepts including time-series preprocessing, return calculation, rolling volatility, correlation analysis, and financial trend visualization.

---

## 🚀 Project Overview

This notebook performs structured exploratory data analysis (EDA) on historical stock data. It demonstrates practical implementation of:

- Loading CSV data using Pandas
- Cleaning and preparing financial time-series data
- Converting date columns into datetime format
- Setting date as index for time-based analysis
- Calculating Moving Averages (20-day MA)
- Computing Daily Returns
- Measuring Volatility using rolling standard deviation
- Performing Correlation Analysis
- Visualizing price and volume trends using Matplotlib & Seaborn

The project intentionally focuses on clarity of logic and fundamental understanding rather than complex financial modeling.

---

## 📊 Key Analysis Performed

**Price Movement Analysis**
Understanding how Open, High, Low, and Close values move together during the same trading day.

**Volume Trend Analysis**
Observing how trading volume behaves during price increases or decreases and identifying weak or strong rallies.

**Daily Returns Calculation**
Measuring percentage change in closing prices to evaluate day-to-day stock performance.

**Volatility Estimation**
Calculating rolling standard deviation of returns to identify unstable price periods.

**Correlation Matrix**
Visualizing relationships between stock variables using a heatmap.

---

## 🔍 Key Insights

- Open, High, Low, and Close prices show strong positive correlation because they belong to the same trading session.
- Volume does not always increase proportionally when price rises, indicating weak rallies in some periods.
- Volatility increases during heavy trading activity.
- Daily returns fluctuate around zero with occasional sharp movements.

---

## 🛠 Technologies Used

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Jupyter Notebook` `VS Code`

---

## 📁 Project Structure

```
STOCK-DATA-ANALYZER/
│
├── stock_analysis.ipynb
├── hyundai_stock.csv
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/ronitmaheshwari05/STOCK-DATA-ANALYZER.git
cd STOCK-DATA-ANALYZER
```

### Step 2: Create Virtual Environment (Recommended)

**Mac / Linux**
```bash
python3 -m venv venv
source venv/bin/activate
```

**Windows (PowerShell)**
```bash
python -m venv venv
venv\Scripts\activate
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

If `requirements.txt` does not exist, install manually:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

## ▶️ How to Run the Project

**Option 1: Run in VS Code**
1. Open the project folder in VS Code
2. Make sure your virtual environment is selected as the Python interpreter
3. Open `stock_analysis.ipynb`
4. Click "Run All" or run each cell step by step

**Option 2: Run Using Jupyter Notebook (Terminal)**
```bash
jupyter notebook
```
Then open `stock_analysis.ipynb` in the browser and run the cells.

---

## 📦 requirements.txt

```
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## 🤝 How to Contribute (Pull Request Guide)

Contributions and improvements are welcome.

**Step 1: Fork the Repository** — Click the "Fork" button on GitHub.

**Step 2: Clone Your Fork**
```bash
git clone https://github.com/ronitmaheshwari05/STOCK-DATA-ANALYZER.git
```

**Step 3: Create a New Branch**
```bash
git checkout -b feature-name
```

**Step 4: Make Changes and Commit**
```bash
git add .
git commit -m "Added new analysis feature"
```

**Step 5: Push Changes**
```bash
git push origin feature-name
```

**Step 6: Create Pull Request** — Go to GitHub → Open your fork → Click "Compare & Pull Request" → Submit PR.

Meaningful improvements are welcome, such as additional financial metrics, better visualization, improved data cleaning, feature engineering, or risk metrics.

---

## 📌 Learning Outcome

This project helped reinforce practical Pandas operations, time-series data handling, financial metric calculations, data visualization techniques, and logical interpretation of stock market behavior. It serves as a foundational data analytics project within my broader MLOps and AI learning journey.

---

## 👨‍💻 Author

**Ronit Maheshwari**
B.Tech Computer Science (AI & ML) — Python & Data Analytics Enthusiast

---

⭐ If you found this project helpful, consider giving it a star!
