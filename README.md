# Predicting 30-Day Patient Readmission

BrightLearn Machine Learning case study (Programming, Python).

## Files
- `Surname_Initials_Readmission_Report.pdf` - the written report
- `Surname_Initials_Readmission_Notebook.ipynb` - all code, runs top to bottom

## How to run
1. Put `Expanded_Patient_Readmission_Data_1.csv` in the same folder as the notebook.
   The dataset is not included in this repository (course rule: do not share it outside the course).
2. Install: `pip install pandas numpy matplotlib seaborn scipy scikit-learn imbalanced-learn jupyter`
3. Run: `jupyter notebook` and choose Run All.

## Result in one line
No model predicted readmission better than chance (test ROC-AUC 0.516 for the final decision tree).
The report explains why and what the hospital should do instead.
