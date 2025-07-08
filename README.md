# 🛒 Amazon Product Reviews – Python Case Study

This project analyzes an Amazon product reviews dataset to extract insights that can help retailers understand customer satisfaction, product performance, and behavioral patterns.

---

## 📊 Objective

To analyze product data, pricing, discount, and customer reviews using Python and answer key business questions to help improve product positioning, marketing, and customer experience.

---

## 🧰 Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Basic NLP (no external libraries required)

---

## 📁 Dataset

- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/ahmedsayed564/amazon-sales-dataset)
- **File**: `Amazon.csv`
- **Rows**: 1,465  
- **Columns**: 16 (Product ID, Name, Category, Price, Rating, Review, etc.)

---

## ❓ Business Questions & Answers

### 🔹 Q1: How does the discount percentage affect the rating of a product?
- **Correlation**: `-0.15` (very weak negative)
- **Conclusion**: High discounts do not guarantee higher customer ratings.

### 🔹 Q2: Which category has the highest average rating?
- **Top Category**: `OfficeProducts` (Avg. Rating: `4.31`)
- **Conclusion**: Office, Toys, and Home Improvement top the list.

### 🔹 Q3: Is there a correlation between product price and rating?
- **Correlation**: `0.12` (very weak positive)
- **Conclusion**: Higher-priced products are slightly better rated, but not significantly.

### 🔹 Q4: What is the most common word in positive and negative reviews?
- **Positive Words**: `good`, `product`, `quality`, `cable`, `price`
- **Negative Words**: `battery`, `working`, `use`, `price`
- **Conclusion**: Quality and price are central to both good and bad reviews.

### 🔹 Q5: What is the distribution of ratings across all products?
- **Observation**: Right-skewed; most ratings are between `4.0` and `4.5`
- **Conclusion**: Customers tend to rate products positively.

### 🔹 Q6: Which product has the highest number of reviews and what is its rating?
- **Product**: `AmazonBasics HDMI Cable`
- **Reviews**: `853,945` | **Rating**: `4.4`
- **Conclusion**: Most trusted & high-volume product.

### 🔹 Q7: Identify the top 5 users who have given the most reviews?
- **Top Users**: 5 users with `10–11` reviews each
- **Conclusion**: No heavy reviewers; most users review occasionally.

### 🔹 Q8: Is there a correlation between review length and rating?
- **Correlation**: `0.077` (very weak positive)
- **Conclusion**: Longer reviews are not necessarily better-rated.

### 🔹 Q9: Does having an image link affect the product rating?
- **Observation**: All products had images.
- **Conclusion**: Can’t compare, but average rating with image: `4.10`

### 🔹 Q10: Can the length of the product description be correlated to the rating?
- **Correlation**: `0.028` (no correlation)
- **Conclusion**: Description length doesn't impact ratings.

---

## 📈 Key Skills Demonstrated

- Data Cleaning (`₹`, `%`, `,` handling)
- Feature Engineering (`review_length`, `description_length`, `has_image`)
- Correlation Analysis
- Word Frequency Analysis (without external NLP libraries)
- Visualizations: Scatterplots, Histograms, Bar Charts
- Insights Summary for Business Impact

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/amazon-product-reviews-analysis.git
Amazon_Review_Analysis.ipynb
```
