# Solubility-prediction-ML
Machine learning project predicting aqueous solubility of drug-like molecules using molecular descriptors and scikit-learn. Implements regression models on the Delaney (ESOL) dataset with comprehensive notebooks, data, and results for drug discovery applications.

Molecular Aqueous Solubility Prediction Using Machine Learning

Overview
This project aims to develop and evaluate machine learning models for predicting the aqueous solubility (logS) of small molecules based on molecular descriptors. Accurate solubility prediction is crucial in drug discovery, as it significantly impacts absorption, bioavailability, and pharmacokinetics.
The study uses the Delaney (ESOL) solubility dataset and applies multiple regression algorithms, including Random Forest and Linear Regression, to predict the logS values. Feature importance analysis highlights the key molecular properties that influence solubility. This repository includes data processing, model training, evaluation, and visualisation scripts implemented in Python with libraries such as RDKit, scikit-learn, pandas, and matplotlib.

Table of Contents
	•	Requirements
	•	Usage
	•	Data
	•	Methodology
	•	Results
	•	Future Work
	•	Contributing
	•	License


Requirements
	•	Python 3.10 or higher
	•	Conda or Miniforge package manager
	•	Required libraries: RDKit, scikit-learn, pandas, numpy, matplotlib, seaborn

# Install dependencies
conda install -c conda-forge jupyter pandas numpy scikit-learn matplotlib seaborn rdkit
	
# Usage
	•	Launch Jupyter Notebook to run the full analysis pipeline:
	•	The notebook covers data loading, exploratory data analysis, feature engineering, model training and evaluation, and visualization.

# Data
	•	The Delaney solubility dataset with molecular descriptors is loaded from a public GitHub URL.
	•	Molecular descriptors include molecular weight, topological polar surface area (TPSA), LabuteASA surface area, BalabanJ and BertzCT complexity indices, and more.

# Methodology
	•	Train-test split with 80-20 ratio and fixed random state for reproducibility.
	•	Models trained and compared: Linear Regression, Random Forest Regressor.
	•	Evaluation metrics: R², RMSE, MAE.
	•	Feature importance derived from Random Forest to interpret model drivers of solubility.

# Results
	•	Detailed performance metrics for each model are provided.
	•	Visualizations include histograms of solubility, pairwise descriptor plots, and predicted vs actual scatter plots.
	•	Feature importance identifies key molecular properties impacting solubility prediction.

# Future Work
	•	Extend with additional machine learning models (Ridge, Lasso, SVR, Gradient Boosting).
	•	Incorporate advanced feature engineering and molecular descriptor sets.
	•	Explore model explainability tools (SHAP, LIME).
	•	Package as a reproducible workflow for cheminformatics applications.

Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements or additional functionality.

License
This project is licensed under the MIT License.
