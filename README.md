# Company Revenue Scraper

A Python-based web scraping tool designed to automatically extract, process, and structure financial data from Wikipedia's list of the largest companies in the United States by revenue.

## 📌 Project Overview
This repository contains an automated scraping pipeline implemented inside a Jupyter Notebook. It targets the Wikipedia page for Fortune 500 US companies, parses raw HTML formatting rules, cleans attributes like workforce counts or compound growth metrics, and saves everything neatly into a structured tabular dataset.

### Data Attributes Tracked
* **Rank**: The company's standing based on financial yield.
* **Name**: Corporate branding entity.
* **Industry**: Sector classification (e.g., Retail, Healthcare, Technology).
* **Revenue (USD millions)**: Total fiscal year revenue.
* **Revenue Growth**: The year-over-year growth rate percentage.
* **Employees**: Worldwide corporate workforce scale.
* **Headquarters**: Primary city and state operational base.

---



## 🛠️ Built With
* **Python 3** - Underlying programming runtime.
* **BeautifulSoup4** - Reliable HTML tree traversal and parser.
* **Requests** - HTTP library utilized for target source retrieval.
* **Pandas** - High-performance data framework for cleansing and CSV generation.

---

## 🚀 Getting Started

### Prerequisites
Ensure your local environment has the required dependencies installed:
```bash
pip install beautifulsoup4 pandas requests notebook
```

### Execution Steps
1. Clone this repository to your machine:
   ```bash
   git clone https://github.com
   cd Company_Revenue_Scraper
   ```
2. Start the Jupyter workspace environment:
   ```bash
   jupyter notebook
   ```
3. Open and run all cell groups inside `Company_Revenue_Scraper.ipynb` to regenerate the live data.

---

## 📊 Sample Output Preview
The output script structures individual rows directly from the wiki table matrices like this:


| Rank | Name | Industry | Revenue (USD millions) | Revenue growth | Employees | Headquarters |
|---|---|---|---|---|---|---|
| **1** | Walmart | Retail | 680,985 | 5.1% | 2,100,000 | Bentonville, Arkansas |
| **2** | Amazon | Retail and cloud computing | 637,959 | 11.0% | 1,556,000 | Seattle, Washington |
| **3** | UnitedHealth Group | Healthcare | 400,278 | 7.7% | 400,000 | Minnetonka, Minnesota |
| **4** | Apple | Technology | 391,035 | 2.0% | 164,000 | Cupertino, California |
