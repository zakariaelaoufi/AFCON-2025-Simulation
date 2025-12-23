# 🇲🇦 AFCON 2025 Morocco — Tournament Simulation

This project simulates the **AFCON 2025 tournament hosted in Morocco** using probabilistic modeling and Monte Carlo simulations.  
It predicts **group stage standings, qualification probabilities, and knockout stage outcomes**, including the final winner.

---

## Project Overview

- Group stage simulation with qualification probabilities  
- Full knockout stage prediction (Round of 16 → Final)  
- Probabilistic match outcome modeling  
- Official AFCON 2025 tournament structure respected  

---

## Data & Resources

- Historical international football match data  
- Team statistics (rankings, performance indicators, form)  
- Engineered match features (rank difference, host flag, recent form)  

**Tech stack**

- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn, Plotly

---

## Methodology

1. **Data preprocessing**
   - Cleaning and aligning team-level statistics  
   - Feature engineering for match prediction  

2. **Modeling**
   - Train probabilistic models for match outcomes (Win / Draw / Loss)  
   - Evaluate and calibrate predicted probabilities  

3. **Monte Carlo Simulation**
   - Run multiple simulations per match  
   - Estimate group qualification and progression probabilities  

4. **Tournament Simulation**
   - Apply AFCON 2025 group and knockout rules  
   - Generate full tournament brackets automatically  

5. **Visualization**
   - Group stage probabilities  
   - Knockout stage predictions  

---

## Results Visualization

### Group Stage Predictions
<img width="4320" height="2400" alt="qualification_probabilities" src="https://github.com/user-attachments/assets/4b1fbdf9-850d-413a-a003-0880e82ae35b" />

### Knockout Stage Predictions
<img width="978" height="600" alt="newplot" src="https://github.com/user-attachments/assets/657172a6-a4b1-4d31-b3c9-086d16eee84e" />

## Disclaimer

This project is a **simulation based on probabilistic models**.  
Results represent **estimated probabilities**, not guaranteed outcomes.
