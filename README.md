# Climate Projection Emulator

This project explores climate emulation using machine learning, aiming to reproduce outputs of complex Earth system models (ESMs) like NorESM2 with significantly lower computational cost. We reimplemented benchmark models from ClimateBench in PyTorch and improved their architectures.

## Key Features

- Implementation of CNN-GRU models for spatio-temporal prediction
- Integration of climate data (CO₂, CH₄, SO₂, BC) on a global grid
- Use of Gaussian Processes with PCA for uncertainty estimation
- Evaluation on scenario SSP245 using NRMSE metrics
- Architecture optimizations: Ridge regularization, GRU, loss weighting, encoder-decoder

## Dataset

- ClimateBench v1.0: inputs from CMIP6 scenarios
- Outputs: temperature (TAS), precipitation (PR), PR90, diurnal temperature range (DTR)

## Frameworks

- PyTorch for deep learning models
- GPyTorch for Gaussian Process regression

## Contributors

Mattéo André, Brahim Benali, Nathanaël Jacquier, Julien Laborde-Peyré, Mattéo Pégard, Paul Thibon

**May 2025**
