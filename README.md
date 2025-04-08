# FootballEval: Evaluating Soccer Players with Data-Driven Metrics

This repository contains the code, data, and methodology used in the FootballEval project, which aims to evaluate soccer players' performances using various objective and interpretable metrics derived from event data.

## 📝 Project Overview

The primary objective of FootballEval is to design a comprehensive evaluation system for football players across different positions using interpretable and statistically grounded indicators. The evaluation framework is designed to support talent scouting, performance assessment, and team strategy decisions in professional football.

## 📊 Methodology

The project is divided into three main stages:

1. **Indicator Design and Data Processing**
   - Developed performance indicators aligned with player roles (e.g., strikers, defenders, midfielders).
   - Aggregated and normalized event-level data (e.g., goals, passes, duels, interceptions).

2. **Weight Calculation**
   - Applied multiple methods to determine the importance of each indicator:
     - **Principal Component Analysis (PCA)**
     - **Entropy Weight Method (EWM)**
     - **Analytic Hierarchy Process (AHP)**

3. **Scoring and Evaluation**
   - Final scores were computed using a linear weighted sum method for each position.
   - Evaluation results were compared across different weighting methods to ensure robustness.


## 📁 Data

The dataset used in this project is derived from publicly available football event logs (e.g., passes, shots, fouls, tackles). Data was aggregated and normalized by position to facilitate fair comparisons.

- Features include: goals, assists, passes, successful duels, interceptions, fouls, etc.
- Player metadata includes name, position, and team.

## 🧠 Key Insights

- **Multi-method comparison** showed consistency across PCA, EWM, and AHP, validating indicator reliability.
- Forwards with high conversion and contribution ratios scored highest, while midfielders were evaluated more holistically.
- Defensive players were assessed not just by tackles, but also by effective clearances and positioning metrics
