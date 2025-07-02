 Money Talks — Predicting FIFA 23 Player Wages ⚽💶

Applied-stats project (STATS 401, Univ. of Michigan).

## Problem
Estimate weekly wages using publicly available FIFA 23 ratings to identify undervalued talent.

## Data
- FIFA 23 player database (~7 k rows, 30+ skill metrics)

## Methodology
1. Log-transform wages to correct right skew  
2. Stepwise multiple regression + interaction (crossing × footedness)  
3. Diagnostics: residual plots, VIF, RMSE  
4. Interpretation: skill elasticities and wage premiums

## Key Findings
- Passing & dribbling explain the bulk of wage variation (Adj R² ≈ 0.34)  
- Left-footed crossers receive a premium salary multiplier  
- Pace alone is not a statistically significant determinant
