# Evaluating AI-Assisted News Discovery for Yle

Feasibility analysis for a Business Analytics final assignment.

**Research question:** Would investing in AI-assisted news discovery help
Yle get more value from the content it already publishes?

## Structure
- `notebooks/` – data analysis in Jupyter notebooks
- `charts/` – charts used in the presentation
- `presentation/` – slides and video script
- `data/` – dataset (not included, see below)

## Data
This project uses the Microsoft News Dataset (MIND-small),
available at https://msnews.github.io under Microsoft's license terms.
The data is not included in this repository. To reproduce the analysis,
download MIND-small and place `news.tsv` and `behaviors.tsv` in `data/`.

## Setup
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
