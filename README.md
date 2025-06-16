# Contingency Risk Index for Civil Engineering Projects

This repository contains a structured methodology to define contingency levels for large-scale civil construction projects, especially when historical data is limited.

It combines:

- Monte Carlo simulation to estimate risk probabilities
- Fuzzy logic to evaluate impact levels using linguistic variables
- Benchmark comparison to test competitiveness of contingency values

## Use case

You have a risk matrix with mapped cost and schedule threats, but no historical contingency baseline. This model helps calculate a contingency index based on quantifiable parameters.

## Inputs

- Risk matrix with ~65 entries
- Impact values:
  - Cost impact (low/medium/high)
  - Schedule impact (low/medium/high)
  - Combined impact (IFAC)
- Probability of occurrence (from MC simulation)

## Files

- `simulação MC.py`: Monte Carlo simulation
- `simulação IC fuzzy logic.py`: fuzzy evaluation
- `CASE IC.ipynb`: explanation and results
- `dados base.xlsx`: input data
- `output.xlsx`: result sheet
- `relatório final.pdf`: formatted report

## Dependencies

- Python 3.x
- pandas, numpy, scipy
- matplotlib
- scikit-fuzzy
- jupyter (optional)

## Disclaimer

All data in this repo is illustrative. Replace inputs and adjust membership functions as needed for your project or company use case.
