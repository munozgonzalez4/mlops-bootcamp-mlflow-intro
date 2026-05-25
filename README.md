# mlops-bootcamp-mlflow-intro

Open source MLOps platform, end-to-end

1) Core MLflow components for Data Science

- Experiment tracking -> versioning considered + Hypothesis testing / Statistical analysis
- Code structuring -> building pipelines
- Model packaging and dependency management -> setup.py 
- Evaluating hyperparameter tuning. Strongest feature of MLflow. -> Tracker
- Compare results of model's versioning over time

2) Core MLflow components for MLOps / ML Engineer

- Manage the lifecycle of trained models, both pre and post deployment
- Deploy models securely to the production environment
- Manage deployment dependencies

3) Core MLflow components for Prompt engineers

- Evaluate and experiment with LLMs
- Create custom prompts and experiments
- Deciding on the best base model

Good tool for collaborative projects due to the UI.

# Creating environment

- conda create -p venv python==3.10 -y
- conda activate venv/
- requirements.txt
- pip install -r requirements.txt

# Tracking server

- See tracking server: Terminal: mlflow ui
- Details in src/getting_started.ipynb

# ML Project

- Details in src/ml_project