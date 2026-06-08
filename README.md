# AI Usage & Student Academic Performance — Exploratory Data Analysis

## ⚠️ Data disclaimer

This dataset is synthetic (generated, not collected from real students). The goal of this project is to demonstrate analytical workflow and sound reasoning, not to draw real-world conclusions about the student population.

## Data source (provenance)

- Kaggle dataset URL: _(to be completed)_
- Download date: _(to be completed)_
- Dataset version: _(to be completed)_
- File: `ai_student_impact_dataset__1_.csv` (expected ~50,000 rows, 16 columns)

## Research questions

_(to be completed)_

## Project structure

```
ai-student-impact-analysis/
├── data/
│   ├── raw/            # raw data (frozen snapshot), git-IGNORED
│   └── processed/      # cleaned data, git-IGNORED
├── notebooks/          # Jupyter — exploration
├── scripts/            # .py scripts
├── reports/
│   └── figures/        # saved charts
├── .gitignore
├── .env.example
├── requirements.txt
└── README.md
```

## Setup

1. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   source .venv/bin/activate        # Windows: .venv\Scripts\activate
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure secrets. Copy the example file and fill in your own Kaggle credentials:

   ```bash
   cp .env.example .env
   ```

   Then edit `.env` and set `KAGGLE_USERNAME` and `KAGGLE_KEY`.
   `.env` is ignored by git and must never be committed.

4. Place the dataset in `data/raw/` (this folder is git-ignored).

## Methodological notes

_(to be completed)_
