# 🧠 Logistic Regression Classification: Raisin Dataset

This notebook demonstrates a complete logistic regression workflow using the Raisin dataset. The goal is to classify raisin types (`Kecimen` vs. `Besni`) using logistic regression and evaluate model performance.

---

### 📁 Dataset

The dataset (`Raisin_Dataset.csv`) contains morphological features of two raisin varieties:

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Raisin+Dataset)
- Target column: `class` (`Kecimen`, `Besni`)

---

### 🧪 Workflow Steps

1. **Import Libraries**  
2. **Load and clean the dataset**  
3. **Encode target labels** (`Kecimen` → 0, `Besni` → 1)  
4. **Feature selection and train-test split**  
5. **Standardize features** using `StandardScaler`  
6. **Train logistic regression model**  
7. **Evaluate model performance** using:
   - Accuracy
   - Classification Report (Precision, Recall, F1)
   - F1 Score (macro & weighted)
   - Confusion Matrix (visualized)
8. **Predict class probabilities**

---

### 📊 Results

The logistic regression model achieved **perfect classification** on the test data:

- Accuracy: 1.00  
- Precision: 1.00  
- Recall: 1.00  
- F1 Score: 1.00  

The confusion matrix showed **zero misclassifications**, indicating the model predicted all labels correctly.

---

### ⚠️ Interpretation

While 100% accuracy is impressive, it may suggest:

- Data is too simple or linearly separable  
- The model might be overfitting  
- Possible data leakage (e.g., features too correlated with target)

Always validate results with:
- Cross-validation
- More complex/realistic datasets
- Out-of-sample testing

---

### 🧹 Next Steps

- Try cross-validation (`StratifiedKFold`)
- Add regularization (`C`, `penalty` in `LogisticRegression`)
- Compare with other models (e.g. KNN, Random Forest)

---

### 📜 License

MIT License. Educational use only.

---

### 🙋‍♀️ Author

Rudolph Haink  
[LinkedIn](https://www.linkedin.com/in/rudolph-haink-a5454564/)

