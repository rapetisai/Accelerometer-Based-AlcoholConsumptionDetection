# Accelerometer-Based Alcohol Consumption Detection

This project explores the use of accelerometer data and advanced machine learning methods to detect heavy drinking behavior. The ultimate goal is to enable a mobile application that can provide individuals with insights into their drinking habits while ensuring user privacy and data security.

## 🔍 Problem
Heavy alcohol consumption is a major public health concern. By leveraging motion data captured via smartphone accelerometers, this project investigates whether machine learning algorithms — specifically permutation entropy and complexity measures — can effectively differentiate between **sober** and **heavy-drinking states**.

## 📦 Repository Contents
- `Project2.ipynb` — notebook with data preprocessing, analysis, and model implementation
- `data/` — (https://archive.ics.uci.edu/dataset/515/bar+crawl+detecting+heavy+drinking)

## 📊 Dataset
- **Source**: [UCI Machine Learning Repository: Bar Crawl — Detecting Heavy Drinking](https://archive.ics.uci.edu/dataset/515/bar+crawl+detecting+heavy+drinking)  
- Contains accelerometer readings and transdermal alcohol content (TAC) data collected during bar crawl experiments.  
- Target: Differentiate between **sober** vs. **heavy drinking** episodes.  

## 🧰 Tech Stack
- Python 3.x  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `tsfresh` (for time-series features), `scipy`
