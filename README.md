# 📚 Book Analytics using Web Scraping, EDA, Data Visualization & Sentiment Analysis

## 📌 Project Overview

This project was completed as part of the **CodeAlpha Data Analytics Internship**.

It demonstrates a complete end-to-end data analytics workflow, starting from collecting data through web scraping and ending with sentiment analysis using Natural Language Processing (NLP).

The project is divided into four independent tasks:

- Web Scraping
- Exploratory Data Analysis (EDA)
- Data Visualization
- Sentiment Analysis

---

# 📂 Project Structure

```
Book_Analytics_Project/
│
├── data/
│   ├── raw/
│   │   └── books_dataset.csv
│   │
│   └── processed/
│       ├── books_clean.csv
│       └── reviews_with_sentiment.csv
│
├── visuals/
│   ├── 01_price_distribution.png
│   ├── 02_rating_distribution.png
│   ├── 03_price_vs_rating.png
│   ├── 04_price_band_share.png
│   ├── 05_price_by_rating_boxplot.png
│   ├── 06_correlation_heatmap.png
│   ├── 07_average_price_by_rating.png
│   ├── 08_sentiment_overview.png
│   └── 09_sentiment_wordcloud.png
│
├── Task1(Web_Scraping).ipynb
├── Task2(EDA).ipynb
├── Task3(Data_Visualization).ipynb
├── Task4(Sentiment Analysis).ipynb
│
├── books_dashboard.png
├── README.md
└── requirements.txt
```

---

# 📊 Task 1 — Web Scraping

### Objective

Collect book information from the BooksToScrape website.

### Extracted Features

- Book Title
- Price
- Rating
- Availability
- Product URL

### Libraries

- Requests
- BeautifulSoup
- Pandas

### Output

```
books_dataset.csv
```

---

# 📈 Task 2 — Exploratory Data Analysis

### Objective

Clean and analyze the scraped dataset.

### Performed Analysis

- Data Cleaning
- Missing Values
- Duplicate Removal
- Price Band Creation
- Summary Statistics
- Pearson Correlation
- Outlier Detection (IQR)

### Output

```
books_clean.csv
```

---

# 📉 Task 3 — Data Visualization

Professional visualizations were created using Matplotlib and Seaborn.

### Visualizations

- Price Distribution
- Rating Distribution
- Price vs Rating
- Price Band Distribution
- Boxplot
- Correlation Heatmap
- Average Price by Rating
- Books Analytics Dashboard

---

# 😊 Task 4 — Sentiment Analysis

Customer reviews were analyzed using Natural Language Processing techniques.

### Models Used

- VADER
- TextBlob

### Visualizations

- Sentiment Distribution
- WordCloud

---

# 🛠 Technologies Used

- Python
- BeautifulSoup
- Requests
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- TextBlob
- VADER Sentiment
- WordCloud
- NRCLex

---

# 📂 Dataset Source

BooksToScrape

https://books.toscrape.com/

---

# 🚀 How to Run

### 1 Clone Repository

```bash
git clone <repository-link>
```

### 2 Install Dependencies

```bash
pip install -r requirements.txt
```

### 3 Run Notebooks

Execute the notebooks in the following order:

1. Task1(Web_Scraping).ipynb
2. Task2(EDA).ipynb
3. Task3(Data_Visualization).ipynb
4. Task4(Sentiment Analysis).ipynb

---

# 📌 Key Skills Demonstrated

- Web Scraping
- Data Cleaning
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
- Natural Language Processing
- Sentiment Analysis
- Business Insights

---

# 📌 Future Improvements

- Build an interactive Streamlit dashboard.
- Use real customer reviews.
- Apply Machine Learning for price prediction.
- Develop a recommendation system.
- Scrape multiple online bookstores.

---

# 👩‍💻 Author

Jawairia Yousaf

CodeAlpha Data Analytics Internship
