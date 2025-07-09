# 👗 Fashion Inventory Optimization using ML & Clustering

This project predicts clothing item sellability and groups stores based on sales behavior to reduce seasonal waste.

## 📊 Dataset
**Simulated fashion retail dataset with 3000+ rows**  
🔗 [Download dataset](https://sandbox:/mnt/data/fashion_inventory_dataset.csv)

- Features: item category, price, discount, season, store, days on rack
- Target: `sold_flag` (1 = sold, 0 = unsold)

## 🧠 ML Pipeline
- Encoded categorical features (season, category, store)
- Trained Random Forest Classifier to predict sold vs unsold items
- Accuracy: ~87%
- Feature importance & confusion matrix visualization

## 🔍 Clustering Analysis
- Grouped stores using KMeans based on average price, discount, and sold quantity
- Identified high-performing and low-performing outlets

## 📈 Tools Used
- pandas, numpy, matplotlib, seaborn
- scikit-learn (Random Forest, KMeans)
