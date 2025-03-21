# RAF_EPL
A project to try and introduce a new metric to analyse the bias or (Ref Adjusted Factor) in the analysis of EPL matches.


## 📊 Dataset: Mock Referee RAF

This dataset simulates 200 football matches and is designed to test models involving referee behavior, VAR impact, and Referee Adjustment Factor (RAF) calculations in football analytics.

### 📁 File:
`mock_referee_raf_dataset.csv`

### 🔢 Columns and Descriptions:

| Column               | Description |
|----------------------|-------------|
| `Match_ID`           | Unique match identifier |
| `Referee`            | Referee assigned to the match |
| `Home_Team`          | Home team name |
| `Away_Team`          | Away team name |
| `Fouls_Home`         | Number of fouls given against the home team |
| `Fouls_Away`         | Number of fouls given against the away team |
| `Cards_Home`         | Total yellow/red cards for the home team |
| `Cards_Away`         | Total yellow/red cards for the away team |
| `Pens_Home`          | Penalties awarded to the home team |
| `Pens_Away`          | Penalties awarded to the away team |
| `VAR_Reviews`        | Total VAR incidents in the match |
| `VAR_Overturns`      | Number of on-field decisions overturned by VAR |
| `VAR_Missed`         | Incidents missed by the referee but caught by VAR |
| `Avg_Review_Time`    | Average time per VAR review (in seconds) |
| `VAR_Acceptance_Rate`| Proportion of VAR decisions accepted by the referee |
| `xG_Home`            | Expected goals for the home team |
| `xG_Away`            | Expected goals for the away team |
| `Match_Result`       | Outcome of the match (Home Win / Away Win / Draw) |

### 🔍 Use Cases

This mock dataset is ideal for:
- Calculating **Referee Adjustment Factor (RAF)** and **Ref-Team Bias Index (RTBI)**
- Modeling **referee influence** on expected goals, penalties, or match outcomes
- Running **SHAP analysis** for feature importance and interpretability
- Generating **radar charts** or bias heatmaps for referee profiles

> ⚠️ Note: This dataset is synthetic and created for experimental or educational purposes only. It does not reflect real-world match outcomes or refereeing behavior.
