# AHP-Based Candidate Ranking System for Data Scientist Hiring

## Project Overview

This project implements the **Analytic Hierarchy Process (AHP)** methodology to support a Data Science squad in selecting the most suitable candidate among six finalists for a Data Scientist role.

While all candidates passed the technical test cutoff, the final hiring decision incorporates multiple dimensions beyond technical skills — including soft skills, communication, experience, and cultural fit.

By applying AHP (developed by Thomas Saaty), the process ensures **consistency**, **objectivity**, and **transparency** in handling complex multi-criteria decision-making scenarios.

---

## Business Problem

A Data Science team needs to choose a single candidate from six finalists.Relying solely on technical test scores is insufficient; the team must also weigh:

- Professional experience
- Soft skills and adaptability
- Cultural alignment with the organization
- Communication skills

The goal is to **prioritize candidates** using a structured, justifiable, and replicable decision framework.

---

## Methodology

The project follows the classic AHP framework, including:

1. Defining the decision problem and evaluation criteria
2. Constructing the pairwise comparison matrix for criteria prioritization
3. Normalizing the matrix and calculating criteria weights
4. Performing a consistency check to ensure logical coherence (Consistency Ratio < 0.1)
5. Scoring candidates against each criterion
6. Calculating weighted aggregate scores and ranking candidates
7. Visualizing results with bar charts, heatmaps, and radar plots
8. Conducting sensitivity analysis to evaluate robustness and decision stability

---

## Evaluation Criteria

| Criterion        | Description                                           |
| ---------------- | ----------------------------------------------------- |
| Technical Skills | Coding ability, algorithmic thinking, modeling skills |
| Soft Skills      | Teamwork, adaptability, problem-solving mindset       |
| Experience       | Depth and relevance of previous professional roles    |
| Cultural Fit     | Alignment with company values, collaboration style    |
| Communication    | Effectiveness in verbal and written communication     |

---

## Data

Synthetic data simulating six candidates’ scores on each criterion, rated on a scale from 1 to 10.

---

## Results

- Final candidate ranking reflects holistic evaluation weighted by the squad’s subjective priorities.
- Visualizations including bar plots, heatmaps, and radar charts enhance interpretability and transparency.
- Consistency Ratio below 0.1 confirms a logically consistent prioritization of criteria.

> Notably, the top-ranked candidate was not the highest scorer in technical skills alone but excelled across all criteria combined.

---

## Technologies

- Python 3.10+
- NumPy, Pandas
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 👨‍💻 Author

**Thiago Guimarães**
Data Scientist | Python Developer | Enthusiast in Decision Science and Applied Mathematics

---

## License

MIT License
