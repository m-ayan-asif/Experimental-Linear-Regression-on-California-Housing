 Muhammad Ayan Asif, 22i-1097

# Experimental Linear Regression on California Housing
**Short description.**  
Reproducible experiments analyzing the `sklearn.datasets.fetch_california_housing` dataset with Linear Regression and SGD-based regressors. The project contains EDA, single- and multi-feature experiments, polynomial feature expansions (degree 2 and 3), diagnostics (residuals, influence), and a LaTeX report summarizing conclusions and recommendations.

---

## Highlights / takeaways (TL;DR)
- **Median Income (MedInc)** is the strongest single predictor ($r\approx0.688$).  
- **Linear Regression (OLS)** is the most stable and interpretable model in this setup (mean CV $R^2 \approx 0.6014$, low variance).  
- **Polynomial expansions** improve in-sample fit (deg 3 → $R^2 \approx 0.7287$) but risk overfitting and increased dimensionality.  
- **SGD diverged** for multi-feature polynomial models without aggressive tuning/regularization — results flagged as `Diverged` in the report/table.

---

## Neccessary tools
- Python, Jupyter Notebook, scikit-learn, numpy, seaborn, matplot lib. 

Simply downlaod the .ipynb file and open it in the code editor of your choice. Note that due to personal choice, the previous cell is necessary to run to run any cell as the compilation carries over. 
