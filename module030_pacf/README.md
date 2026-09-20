# atlas/modules/module030_pacf/README.md
# Module 030: Partial Autocorrelation Function (PACF)

## Status: Phase 1.0 - Engine Validated

## Research Question
What is the partial autocorrelation structure of BTC returns?

## Engine
- PACF computation using Yule-Walker Modified (ywm) method
- Confidence intervals using normal approximation
- Max lag: 40 (configurable)

## Validation
- [x] White noise: small PACF values
- [x] AR(1): Lag 1 matches phi
- [x] Confidence intervals consistent
- [x] Log returns correct
- [x] BTC data integration