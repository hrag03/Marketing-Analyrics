 # Bass Model PDF File ReadMe

This ReadMe file provides instructions on how to use the Bass Model PDF file generated from the R Markdown code.

## Overview
The Bass Model PDF file contains analysis of sales data for Amazon Echo speakers from 2014-2023 using the Bass diffusion model. It estimates the coefficients of innovation (p) and imitation (q) from real sales data and uses these values to predict potential sales of a new product (Sonos Era 300 speaker).

## Instructions
1. Open the Bass Model.pdf file. It contains 6 pages of analysis.
2. Page 1 provides an introduction and justification for choosing Amazon Echo as the past look-alike innovation. 
3. Page 2 loads and visualizes the Echo sales data, then fits the Bass diffusion model to estimate p, q, and m parameters.
4. Page 3 plots the Bass model cumulative and instantaneous functions using the estimated p and q values.
5. Page 4 predicts potential sales of the Sonos speaker using the Bass model and estimated parameters. 
6. Page 5 visualizes a comparison of actual Echo sales vs predicted Sonos sales. 
7. Page 6 estimates the potential market size for the Sonos speaker using Fermi estimation logic.

## Code
The R Markdown code that generated the PDF file is also provided. It contains the necessary R code chunks to:
- Load and visualize the Echo sales data
- Fit the Bass diffusion model 
- Estimate the p, q, m parameters
- Define the Bass model functions
- Make predictions and plots

The code is commented to help understand each step. You can modify and run the code as needed.

## LaTeX
$$
F(t) = 1 - e^{-(p+q)t}
$$
is the Bass model cumulative distribution function, where $p$ is the coefficient of innovation and $q$ is the coefficient of imitation.