# Steam Game Popularity Prediction

An end-to-end machine learning project for the 2026 Bamboo Summer AI Competition, predicting game popularity scores ($0 - 1$) using robust feature engineering and multi-stage regression-classification ensembles.

## Repository Structure
- `01_eda.ipynb`: Exploratory data analysis, feature correlation checks, and target distribution insights.
- `02_pipeline.py`: Integrated end-to-end pipeline handling data preprocessing, multi-hot encoding, model training (LightGBM classifier & regressor ensemble), and submission generation.

## How to Run
1. Place `train.csv`, `test.csv`, and `sample_submission.csv` in the data directory.
2. Run the pipeline script:
   python 02_pipeline.py
