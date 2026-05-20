# India Q-Commerce Expansion

Analysis and modeling workspace for India quick-commerce expansion strategy.

## Project structure

```
india-qcommerce-expansion/
├── data/
│   ├── raw/          # Source datasets (unchanged)
│   ├── cleaned/      # Cleaned, validated data
│   └── processed/    # Feature-ready / aggregated data
├── sql/
│   ├── schema/       # DDL and table definitions
│   ├── queries/      # Reusable SQL queries
│   └── exports/      # Query output exports
├── notebooks/        # Jupyter analysis notebooks
├── dashboard/        # Dashboard assets and configs
├── excel_model/      # Financial / scenario Excel models
├── ppt/              # Presentation decks
├── reports/          # Final reports and deliverables
└── docs/             # Documentation and references
```

## Setup

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Workflow

1. Place raw inputs in `data/raw/`
2. Run cleaning pipelines → `data/cleaned/`
3. Build features and aggregates → `data/processed/`
4. Document logic in `sql/` and `notebooks/`
5. Publish outputs to `reports/`, `dashboard/`, and `ppt/`
