# Smart Irrigation
Machine learning and MLOps project for predicting irrigation needs from environmental data.
## Overview
The project combines a Python prediction pipeline, an API, a frontend and operational tooling for model versioning and monitoring.
## Technologies
- Python and scikit-learn
- FastAPI and Uvicorn
- React/Vite
- Docker Compose
- DVC for data/model versioning
- MLflow for experiment tracking
- Prometheus metrics
- pytest
## Architecture
- src/ : training and preprocessing pipeline
- api/ : prediction API
- irrigation_frontend/ : web interface
- models/ : local model artifacts
- monitoring/ : observability configuration
- tests/ : API and pipeline tests
## Local setup
Install the Python dependencies, configure the environment from .env.production.example, then start the API and frontend using the documented Docker Compose or local commands.
## Portfolio note
This repository presents Yahya Aferdi's personal Smart Irrigation project. Metrics and model performance should only be reported with a reproducible dataset and evaluation protocol.
