# 📱 Web Scraping & Exploratory Data Analysis of Flipkart Mobile Data

## 📌 Project Overview

This project focuses on **web scraping mobile phone data from Flipkart** and performing **Exploratory Data Analysis (EDA)** to understand pricing patterns, brand trends, ratings, and feature distributions. The goal is to convert raw web data into meaningful business insights using Python.

---

## 🎯 Objectives

* Scrape mobile phone data from Flipkart website
* Clean and preprocess raw scraped data
* Analyze pricing, ratings, and brand-wise trends
* Perform EDA using visualizations
* Derive insights useful for customers and market analysis

---

## 🧰 Tools & Technologies Used

* **Python**
* **BeautifulSoup**
* **Requests**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 📂 Dataset Details

The dataset contains:

* Mobile Brand & Model
* Price
* Ratings
* Reviews
* RAM & Storage
* Processor / Features (if available)

*Data is scraped directly from Flipkart and stored in structured format for analysis.*

---

## 🔄 Project Workflow

1. **Website Inspection**

   * Identify HTML tags and classes using browser developer tools

2. **Web Scraping**

   * Extract mobile details using `requests` and `BeautifulSoup`

3. **Data Cleaning**

   * Handle missing values
   * Remove symbols and convert data types

4. **Exploratory Data Analysis**

   * Price distribution analysis
   * Brand-wise comparisons
   * Rating vs price analysis

5. **Visualization**

   * Bar charts, histograms, box plots, and heatmaps

6. **Insights & Conclusions**

   * Identify affordable brands
   * High-rated mobiles vs pricing
   * Market trends

---

## 📊 Key Insights

* Certain brands dominate the affordable price range
* Higher price does not always guarantee better ratings
* Mid-range mobiles show high customer satisfaction
* Strong competition exists in ₹10k–₹20k segment

---

## ▶️ How to Run This Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/flipkart-mobile-web-scraping-eda.git
```

### Step 2: Install Required Libraries

```bash
pip install requests beautifulsoup4 pandas numpy matplotlib seaborn
```

### Step 3: Run Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Open and Execute

* `web scraping project.ipynb`
* `scrapped data flipkart mobile.ipynb`

---

## 📁 Project Structure

```
├── web scraping project.ipynb
├── scrapped data flipkart mobile.ipynb
├── README.md
```

---

## 🚀 Future Enhancements

* Automate scraping for multiple pages
* Add time-based price comparison
* Build a dashboard using Power BI / Tableau
* Apply machine learning for price prediction

---

## 📌 Disclaimer

This project is created **for educational purposes only**. Data is scraped for learning and analysis.
