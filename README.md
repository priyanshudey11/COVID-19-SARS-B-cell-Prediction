# Epitope Prediction Project

This repository contains the analysis and modeling efforts for predicting B-cell epitopes using the COVID-19/SARS B-cell Epitope Prediction dataset. The project is structured in two main parts:

- **Generalized Linear Models (GLMs):** Development and evaluation of GLMs to predict epitope presence.
- **Multilevel Modeling:** Implementation of hierarchical models to account for data grouped at multiple levels.

## Repository Structure

- `data/`: Contains the dataset files used in the analysis.
- `scripts/`: Includes R scripts for data processing, analysis, and modeling.
- `reports/`: Holds the final reports and presentation materials.
- `README.md`: This file, which provides an overview of the project.

## Dataset

The dataset comprises sequences and associated information pertinent to B-cell epitope prediction. For detailed information, refer to the dataset's [Kaggle page](https://www.kaggle.com/datasets/futurecorporation/epitope-prediction).

## Project Components

1. **Generalized Linear Models (GLMs)**
   - **Exploratory Data Analysis (EDA):** Initial examination of data distributions and relationships among variables.
   - **Model Building:** Construction of GLMs suitable for binary outcomes, such as logistic regression models.
   - **Model Evaluation:** Assessment of model performance using metrics like accuracy, precision, recall, and AUC-ROC.

2. **Multilevel Modeling**
   - **Hierarchical Data Structuring:** Identification of nested data structures to inform model design.
   - **Model Specification:** Definition of fixed and random effects to capture both population-level and group-level variations.
   - **Model Assessment:** Evaluation of model fit and comparison with non-hierarchical models to determine the added value of multilevel modeling.

## Getting Started

### Clone the Repository:

```bash
git clone https://github.com/priyanshudey11/COVID-19-SARS-B-cell-Prediction.git
```

Navigate to the project directory:

```
cd COVID-19-SARS-B-cell-Prediction
```
Install Nessary R packages
```
install.packages(c("tidyverse","dplyr","ggplot2","car"))
```
### Update the Repository with New Changes
Add New Files: Add any new or modified files to the staging area:
```
git add .
```
Commit Changes: Commit the changes with a descriptive message:
```
git commit -m "Descriptive message about changes made"

```
Push Changes to GitHub: Push your changes to main branch
```
git push origin main
```
## Contributions
This project was completed as part of the STAT 400 Statistical Modeling II course. Under the guidance and instructions of Dr. Mattew Slifko (mds6457@psu.edu)

Group members include:

- Priyanshu Dey: pkd5228@psu.edu
- Elizabeth Marchini: erm5580@psu.edu
- Adam Torres Encarnacion : art5809@psu.edu

Each member contributed to data analysis, model development, and report preparation.

## Acknowledgments
We extend our gratitude to the creators of the COVID-19/SARS B-cell Epitope Prediction dataset for providing the data that made this analysis possible.

For any questions or further information,please contact any of the group members.
