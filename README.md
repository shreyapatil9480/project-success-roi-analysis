# Project Success & ROI Analysis

This repository contains a self‑contained data science project designed for **Business Analyst**, **Program Manager**, and **Data Analyst** roles. It demonstrates how to create a synthetic dataset, perform exploratory data analysis (EDA), and build predictive models to estimate project success and return on investment (ROI).

## Contents

- `synthetic_project_data.csv` — synthetic dataset with 500 project records.
- `analysis.ipynb` — Jupyter notebook containing EDA, visualizations, and predictive modeling.
- `requirements.txt` — list of Python dependencies to reproduce the analysis.

## Dataset

The dataset simulates project management metrics. Each row represents a project with the following columns:

| Column | Description |
|-------|------------|
| **Project_ID** | Unique identifier for each project |
| **Department** | Department responsible for the project (Sales, Marketing, IT, HR, Finance) |
| **Team_Size** | Number of team members on the project |
| **Budget** | Allocated budget (USD) |
| **Duration_Months** | Planned project duration in months |
| **Risk_Rating** | Risk assessment (“Low”, “Medium”, or “High”) |
| **Client_Priority** | Priority assigned by the client (“Low”, “Medium”, or “High”) |
| **Project_Success** | Binary indicator (1 = success, 0 = failure) |
| **Completion_Time** | Actual project completion time in months |
| **ROI** | Return on investment (continuous value representing profitability) |

## Getting Started

To explore or extend this project on your local machine:

1. **Clone the repository** (after it has been published).

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook** to run the analysis:
   ```bash
   jupyter notebook analysis.ipynb
   ```

The notebook provides step‑by‑step code for EDA, visualization, and predictive modeling using logistic regression, random forest classifiers, and regression models.

## Usage

Feel free to modify the dataset generation process, experiment with different modeling techniques, or extend the analysis for your own learning and portfolio. This repository is intended as a starting point for demonstrating practical data‑science skills relevant to business analytics and program management roles.

## License

This project is released under the [MIT License](LICENSE).
