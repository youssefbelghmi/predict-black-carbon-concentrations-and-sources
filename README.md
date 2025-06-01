# Prediction of Black Carbon Concentrations and Potential Sources

## Project Overview

Black Carbon (BC) and Elemental Carbon (EC) are key carbonaceous pollutants used as indicators of air quality and combustion emissions. Despite their similar physical meanings, BC and EC are often measured with different instruments and protocols, leading to inconsistencies in reported concentrations. Additionally, environmental factors such as aerosols and mineral dust can further bias these measurements, especially when using optical methods.

The objective of this project was to:

- Clean and standardize a large, heterogeneous dataset of BC and EC measurements across Europe.
- Analyze how protocols, instruments, and atmospheric conditions (e.g., secondary aerosols and dust) influence the BC–EC relationship.
- Provide a robust foundation for future harmonization models, to make BC and EC data more comparable across sites and studies.

---

## Notebooks

### `01_data_preparation_and_bias_analysis.ipynb`

This notebook includes:

- Dataset cleaning, normalization and log-transformation.
- Outlier detection using Interquartile Range (IQR), Isolation Forest, and Quantile Regression.
- Statistical analysis of protocol and instrument biases:
  - Distribution analysis of EC/BC ratios
  - ANOVA and linear regression models
  - Median quantile regressions by protocol and instrument type

---

### `02_environmental_factors_analysis.ipynb`

This notebook explores how atmospheric conditions contribute to measurement bias:

- Comparison of BC and secondary aerosol behavior with respect to EC
- Median quantile regression of BC and aerosol concentrations
- Modeling the effect of total secondary aerosols and specific compounds (NO₃⁻, SO₄²⁻)
- Polynomial and spline regression models
- Dust impact analysis on the BC/EC ratio

---

## Final Report

The full LaTeX report provides detailed methodology, results, figures, and interpretations.

Key sections include:

- Introduction and scientific context
- Description of the dataset and preprocessing strategy
- Detection and quantification of protocol/instrument biases
- Environmental influences (aerosols, dust) on concentration estimates
- Conclusion, limitations, and future directions

---

## Supervisors and Acknowledgments

This project was conducted in collaboration with:

- **Swiss Data Science Center (SDSC)**  
- **Paul Scherrer Institute (PSI)**  
- **EPFL**

See the Acknowledgments section of the report for full credits and gratitude.

---

## Contact

For questions, feedback or collaboration inquiries:

**Author**: Youssef Belghmi 
**Affiliation**: Master in Data Science, EPFL  
**Email**: [youssef.belghmi@epfl.ch]

---