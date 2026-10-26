# Problem Set 2 — The Survey That Wasn't Random

ECON 3916 · Applied Data Analytics · Northeastern University

## What this is
A simulation study of a product survey. After a redesign, the survey mean rose
by about 0.7 points while true satisfaction rose by only 0.1. The notebook shows
why: response depends on satisfaction itself (non-response bias).

## Contents
- `Econ_3916_PS2.ipynb`: the full analysis
  - Phase 1: simulated population and response mechanism
  - Phase 2: bootstrap intervals and coverage check
  - Phase 3: two-sample test and power analysis
  - Phase 4: inverse-probability weighting attempt (AI-assisted, transcript included)

## How to run
Open the notebook in Google Colab and run Runtime › Restart and run all.
Requires numpy, pandas, scipy, statsmodels and scikit-learn.
