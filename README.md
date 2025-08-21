# Concrete Compressive Strength Prediction using Machine Learning  

## Overview  
This project analyzes and predicts concrete compressive strength using multiple machine learning and deep learning models.  
The dataset, sourced from the UCI Machine Learning Repository, contains 1,030 records with 8 input features including cement, water, blast furnace slag, fly ash, aggregates, superplasticizer, and age of concrete.  

The goal is to identify the most influential factors in concrete strength and build predictive models for high-performance construction management and structural engineering applications.  

---

## Objectives  
- Apply machine learning regression models (Decision Tree, Random Forest, Gradient Boosting, KNN, SVR).  
- Evaluate performance with MAE, RMSE, and R² metrics.  
- Implement a deep learning model (Keras + TensorFlow) for comparison.  
- Conduct feature importance analysis to determine key drivers of strength.  

---

## Tech Stack  
- Languages: Python  
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow/Keras  
- Techniques: Data preprocessing (normalization, train-test split), EDA (pair plots, heatmaps, boxplots), Feature Importance, Hyperparameter Tuning  

---


## Results & Insights
	•	Random Forest performed best with R² = 0.89, RMSE = 5.44, and MAE = 3.71.
	•	Gradient Boosting closely followed with R² = 0.88; tuning improved it to R² = 0.92.
	•	Deep Learning model achieved R² = 0.86, competitive but requiring more data & tuning.
	•	Key predictors: Age and Cement (~0.35 importance each), followed by Water (~0.15).

⸻

## Impact & Applications
	•	Supports construction managers and civil engineers in optimizing concrete mix design.
	•	Enables predictive quality control in high-performance construction.
	•	Demonstrates how ML/AI techniques can enhance efficiency and safety in civil engineering.

⸻

## Future Work
	•	Expand dataset with more concrete mixtures and environmental factors.
	•	Explore advanced deep learning architectures (CNN, RNN).
	•	Apply ensemble stacking or hybrid models for improved performance.
	•	Integrate into construction workflows for real-time quality monitoring.

⸻

## References

Dataset: UCI ML Repository – Concrete Compressive Strength

⸻

## Acknowledgments
	•	Developed as part of Data Analysis in Construction Management (CNST 6308), Fall 2024.
	•	Instructor: Dr. Lu Gao

## Project Structure  
```bash
├── data/                         # UCI Concrete Compressive Strength dataset  
├── notebooks/                    # Jupyter notebooks for data analysis & modeling  
├── models/                       # Saved ML/DL models  
├── results/                      # Model performance metrics & plots  
└── README.md                     # Project documentation

--- 
