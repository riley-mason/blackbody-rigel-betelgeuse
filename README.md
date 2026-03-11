# Blackbody Radiation: Rigel vs. Betelgeuse

This project compares the blackbody energy distributions of two famous stars in the constellation Orion.

## Overview
- Implemented Planck's law from fundamental constants
- Compared a hot blue supergiant (Rigel, 11,000 K) with a cooler red supergiant (Betelgeuse, 3,500 K)
- Used log-scale plotting to visualize the wide range of intensities

## Physics
The blackbody energy distribution is given by:
B(λ,T) = (2hc²/λ⁵) × 1/(e^(hc/λkT) - 1)

where:
- λ = wavelength
- T = temperature
- h = Planck's constant
- c = speed of light
- k = Boltzmann's constant

## Results
The plot shows how hotter stars peak at shorter wavelengths (Rigel in blue) and cooler stars peak at longer wavelengths (Betelgeuse in red)—consistent with Wien's displacement law.

## Files
- `blackbody_analysis.ipynb`: Main Jupyter notebook with complete code and visualization
- `README.md`: This file

## Dependencies
- numpy
- matplotlib
- scipy (for physical constants)
