# Assignment 5 — Encoding Amazon Reviews

[Open in Google Colab](https://colab.research.google.com/github/manoai2007-lgtm/ass5-amazon-encoding/blob/main/Ass5_Amazon_Reviews_Encoding.ipynb)

Principles of AI, Lab 4 Part 2. English explanations and line-by-line comments follow the course's **sec5_answers** material (Eng. Samaa Abdelmohsen). The notebook includes the section's preparation steps and applies its encodings to all nine columns.

## Run

Open the Colab link and choose **Runtime → Run all**. The original Kaggle dataset downloads automatically. No Drive mount, personal credentials, API key, or manual upload is needed. Execution requires internet access to the public Kaggle download endpoint. The repository contains the notebook and its real saved outputs, not a copy of the source CSV.

## Verified results

- Original dataset: 21,214 rows, 9 columns.
- Exact duplicates removed: 2.
- Rows missing essential fields removed: 157.
- Cleaned dataset: 21,055 rows.
- Final encoding: **21,055 × 142**, all numeric and no missing cells.
- All **14 code cells** executed successfully; English explanation precedes each cell.
- 18 negative review delays are explicitly flagged and retained, as described in the notebook.
- Saved outputs were produced through a real local Python/Jupyter execution; they are not a claim of execution on a Google-hosted runtime.

`verification.json` records validation results; `requirements.txt` records the versions used for that execution. The methods use standard pandas/scikit-learn APIs available in Colab; installing the exact local pins is not required for normal Colab use.

## Data and scope

Original source: [Dongre Laxman — Amazon Reviews Dataset](https://www.kaggle.com/datasets/dongrelaxman/amazon-reviews-dataset).

The exact downloaded CSV SHA-256 is recorded in the executed notebook and verification file. The notebook avoids displaying raw reviewer names, links, or complete reviews in public outputs.

The assignment also requires a student video explaining every line. A video speaking guide is included, but this notebook does not replace that recording. This repository is a publication of the notebook, **not a Moodle submission**.

This is a lab encoding demonstration, not a trained ML pipeline. Future modelling should split data before fitting preprocessing and separate the target and arbitrary identifiers from predictive inputs.
