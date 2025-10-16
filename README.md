# 💬 Customer Sentiment Analysis

## 📖 Overview

This repository contains an internship project focused on **Customer
Sentiment Analysis** using the **Amazon Product Reviews dataset** from
Kaggle.\
The goal is to analyze customer feedback and classify it as
**Positive**, **Neutral**, or **Negative** based on product ratings.

------------------------------------------------------------------------

## 🧠 Project Objective

To explore customer satisfaction levels through data-driven analysis,
understand review distribution, and identify key insights that can
improve service quality and business strategy.

------------------------------------------------------------------------

## 📦 Dataset

-   **Source:** [Amazon Product Reviews by
    saurav9786](https://www.kaggle.com/datasets/saurav9786/amazon-product-reviews)\
-   **File Type:** CSV (zipped format)
-   **Size:** \~7.8 million reviews

------------------------------------------------------------------------

## 🧰 Tools and Libraries

-   **Python 3**
-   **pandas**
-   **matplotlib**
-   **zipfile**
-   **TextBlob** *(for future sentiment extension)*

------------------------------------------------------------------------

## ⚙️ Steps Performed

1.  **Data Extraction:** Unzipped and read CSV file into pandas
    DataFrame.\
2.  **Data Cleaning:** Removed null values, unnecessary columns, and
    standardized formats.\
3.  **Sentiment Classification:**
    -   Ratings 4--5 → Positive\
    -   Rating 3 → Neutral\
    -   Ratings 1--2 → Negative\
4.  **Visualization:** Summarized sentiment percentages in a table and
    optional chart.\
5.  **Insight Generation:** Observed customer satisfaction trends.

------------------------------------------------------------------------

## 📊 Key Results

  Sentiment   Percentage
  ----------- ------------
  Positive    **55.6%**
  Neutral     **27.1%**
  Negative    **17.3%**

✅ The majority of customers shared positive experiences, indicating
strong satisfaction with Amazon products.

------------------------------------------------------------------------

## 🚀 Future Improvements

-   Perform **text-based sentiment analysis** using TextBlob or VADER.\
-   Create **word clouds** for positive and negative reviews.\
-   Build a **dashboard** for interactive sentiment insights.

------------------------------------------------------------------------

## ✍🏽 Author

**Idaraobong Sammy**\
🎓 Internship Project \| 💻 Data Analyst (in training) \| 🧩 Passionate
about data-driven problem solving

------------------------------------------------------------------------

## 🗂 Repository Structure

    Customer-Sentiment-Analysis/
    │
    ├── Customer_Sentiment_Analysis_Report.md   # Detailed project documentation
    ├── sentiment_analysis.ipynb                # (Optional) Colab/Python notebook
    ├── data/                                   # Dataset folder (optional for local use)
    └── README.md                               # Overview and instructions

------------------------------------------------------------------------

## 🧾 License

This project is open-source and available for educational use.
