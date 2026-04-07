# Multimodal Music Analysis
Τεχνικές Εξόρυξης Δεδομένων - Εργασία Εξαμήνου

## Team
- Member 1: [Name]
- Member 2: [Name]

## Setup
```bash
pip install -r requirements.txt
```

## Project Structure
```
├── data/
│   ├── raw/           # Original files from eclass (not tracked by git)
│   └── processed/     # Cleaned/merged datasets
├── notebooks/
│   └── Part_A_Preprocessing_Embeddings_EDA.ipynb
├── src/               # Shared helper functions (optional)
├── outputs/
│   ├── plots/         # Saved figures
│   └── models/        # Saved models (Word2Vec, PCA, etc.)
├── requirements.txt
└── .gitignore
```

## Data Files (place in data/raw/)
Download from eclass and place these files:
- `id_genres.csv`
- `id_lyrics.csv` (or .gz)
- `id_tags.csv`
- `id_metadata.csv`
- `id_audio_stats.csv` (or .gz)

## Deadlines
- **Part A:** 19/04/2026
