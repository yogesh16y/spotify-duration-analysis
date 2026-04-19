# spotify-duration-analysis
Inferential statistics project analyzing the relationship between song duration and popularity using Python and Spotify data.
# 🎧 Do Longer Songs Get Lower Ratings?

## 📊 Overview
This project analyzes whether song duration affects popularity using a Spotify dataset (~100,000 songs).

---

## 🎯 Objective
To determine if longer songs receive lower popularity using inferential statistics.

---

## 📁 Dataset
- Source: Spotify dataset (Kaggle)
- Features used:
  - duration_ms
  - popularity

---

## 🧹 Data Processing
- Removed null values
- Removed duplicates
- Converted duration to minutes
- Created groups: Short, Medium, Long

---

## 📊 Sampling
Used stratified sampling:
- 1000 samples from each group

---

## 🧠 Methods Used
- Z-test (hypothesis testing)
- Pearson correlation

---

## 📈 Results
- Z-value = 0.4792  
- Correlation = -0.03  

---

## 💡 Conclusion
Song duration has no significant impact on popularity.

---

## 🛠️ Tools
Python | pandas | scipy | seaborn | matplotlib

---

## 👨‍💻 Author
Yug
