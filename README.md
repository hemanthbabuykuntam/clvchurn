# CLVChurn: Customer Lifetime Value & Churn Prediction ML Project

## Project Overview
This project predicts customer lifetime value and churn using transactional data. It covers end-to-end ML lifecycle including data preparation, feature engineering, modeling, evaluation, deployment with FastAPI, versioning with DVC, and experiment tracking with MLflow.

## Project Structure
- `data/`: Raw and processed data
- `models/`: Saved ML models
- `notebooks/`: Exploratory notebooks
- `src/`: Source code modules
- `tests/`: Unit tests
- `Dockerfile`: Container config
- `requirements.txt`: Python dependencies
- `main.py`: Run pipeline
- `README.md`: This file

## How to run
1. Install dependencies: `pip install -r requirements.txt`
2. Run pipeline: `python main.py`
3. Start API: `uvicorn src.deploy:app --reload`


