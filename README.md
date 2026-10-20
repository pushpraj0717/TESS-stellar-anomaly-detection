# TESS-stellar-anomaly-detection

Overview:
This project investigates unsupervised machine-learning methods for identifying potentially anomalous stellar variability in NASA Transiting Exoplanet Survey Satellite (TESS) light-curve data. The analysis was developed as part of the BRICS Astronomy Data Analysis Program.

Methodology:
The analysis pipeline uses:
Feature engineering to represent stellar variability numerically.
Principal Component Analysis (PCA) for dimensionality reduction.
K-Means clustering to identify groups of similar observations.
DBSCAN to investigate density-based structure and potential outliers.
Cross-validation of anomaly candidates across the two clustering approaches.

Results:
The analysis reduced a 14-dimensional feature space to two principal components while retaining 89% of the variance.
Potential anomaly candidates were compared across K-Means and DBSCAN. Their astrophysical significance requires interpretation and, where appropriate, further validation.

Tools:
Python, NumPy, pandas, Matplotlib, scikit-learn, and Jupyter Notebook.

Reproducibility:
The notebook and supporting files will document the analysis workflow, preprocessing choices, model parameters, and visualisations.

Limitations:
Unsupervised algorithms can identify unusual patterns without establishing their astrophysical cause. Candidate anomalies should not be interpreted as discoveries without further investigation.

Author:
Pushprajsinh Rathod
B.S. Physics, Pandit Deendayal Energy University (PDEU)
