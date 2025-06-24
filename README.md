# Quantum Risk Analysis in Finance

This project explores quantum algorithms for financial risk analysis, specifically focusing on the computation of key risk metrics such as **Value at Risk (VaR)** and **Conditional Value at Risk (CVaR)** using **Quantum Amplitude Estimation (QAE)** and **Quantum Signal Processing (QSP)**.

## Overview

The project includes:

- A literature review of quantum approaches to risk modeling.
- Reproduction and explanation of QAE and QSP-based algorithms.
- A proposed **hybrid quantum-classical framework** for generating realistic market scenarios using a **quantum GAN (qGAN)**.
- Analysis of resource costs and conditions for achieving quantum advantage.

## Key Concepts

- **Quantum Amplitude Estimation (QAE):** Used to estimate expected loss, VaR, and CVaR.
- **Quantum Signal Processing (QSP):** Efficient polynomial-based filtering for threshold comparison.
- **qGAN:** Quantum generator adversarially trained against a classical discriminator to learn empirical scenario distributions.
- **Scenario Loading Bottleneck:** Addressed using native quantum state preparation via a trained VQC.

## File Structure

├── main.pdf # Final project report
├── slides.pdf # Presentation slides
├── README.md # This file
├── FinalProject_guideline.pdf # Spec
└── docs/ # Papers I reference

