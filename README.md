# Intro to Statistical Learning with Python / ML Specialization (CU Boulder Coursera)

Lily Holmes
Summer 2026 
not for credit

## Overview

This repository contains my code alongs, excercises, and lab notes for studying statistical learning and machine learning over Summer 2026

Main resources are:
- *An introduction to Statistical Learning with Applications in Python* 
- ISLP Python labs
- CU Boulders Machine Learning specialization on Coursera

> The goal of this repository is to build fluency with statistical learning concepts and Python workflows 

## Repository Structure

```text
.
├── coursera_ML/
│   └── Coding practice from the ML course on Coursera
│
├── islp_exercises/
│   └── My own implementations and exercise work from ISLP chapters
│
└── islp_labs_official/
    └── ISLP lab notebooks downloaded from the official ISLP GitHub repository
        https://github.com/intro-stat-learning/ISLP_labs/tree/stable 

```

## Notes

This repository is for personal study. Some material is adapted from pubic course or textbook resources, while my own work appears in the excersize and code-along folders.

## Reproducibility 

```bash
git clone <rhttps://github.com/lily-harper/intro_to_statlearning_wPython>
cd <intro_to_statlearning_wPython>

python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt
jupyter lab
```

Notes

- Dependencies are pinned in `requirements.txt`.
- The virtual environment folder `.venv/` is ignored and should be recreated locally.
- Some notebooks may depend on datasets downloaded or provided by the ISLP package/labs.