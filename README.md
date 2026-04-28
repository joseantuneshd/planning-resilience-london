# Planning Resilience in London

This repository contains the data pipeline and modelling framework used to construct a borough–month panel of planning performance in London and to evaluate forecasting models for resilience-related outcomes.

## Repository structure

- `notebooks/`
  - `01_download_and_qa_cleaned.ipynb`: data extraction and initial quality assessment
  - `02_preprocessing.ipynb`: preprocessing and panel construction
  - `03_descriptive_analysis.ipynb`: descriptive analysis of the panel
  - `04_modeling_framework.ipynb`: modelling, evaluation, and interpretability

- `data/`
  - `processed/borough_month_panel_resilience_inputs.csv`: final processed borough–month analytical dataset
  - `geo/london_boroughs.geojson`: borough boundaries used for mapping


## Workflow

1. Extract and assess data quality
2. Apply preprocessing and construct the borough–month panel
3. Explore descriptive patterns
4. Train and evaluate forecasting models
