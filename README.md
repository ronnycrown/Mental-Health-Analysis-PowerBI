# Mental-Health-Analysis-PowerBI
This project followed a structured analytics workflow to transform raw mental health data into a dynamic, insight-driven dashboard. 

## Table of Contents
1. [Problem Statement](#problem-statement)
2. [Overview](#overview)
3. [Data Collection and Integration](#data-collection-and-integration)
4. [Tools](#tools)
5. [Data Modelling and Transformation](#data-modelling-and-transformation)
6. [Visualisation and Insights](#visualisation-and-insights)
7. [Conclusion](#conclusion)
8. [Recommendations](#recommendations)

# Problem Statement
Monitoring patient progress in mental health treatment can be challenging due to the complexity of symptoms, behavioural changes, and individual responses to medication or therapy. Clinicians often struggle to identify:
- Which treatment methods are most effective?
- What behavioural factors predict patient improvement?
- How adherence levels influence outcomes?
- Which patients are at risk of deterioration?
- How symptoms, stress, mood, and sleep interact over time.
Without a structured analytical system, vital patterns may remain hidden, making it difficult to optimise care or tailor interventions to patient needs.

This project aims to solve these challenges by developing a data-driven dashboard that:
- Visualises patient progress in real time.
- Highlights key predictors of positive or negative outcomes.
- Tracks behavioural indicators such as sleep, mood, stress, and physical activity.
- Shows adherence levels and their direct impact on treatment success.
- Presents AI-detected emotional insights to support decision-making.
By transforming raw data into actionable insights, the dashboard enables clinicians, mental health researchers, and healthcare managers to make more informed, evidence-based decisions that can enhance patient well-being and treatment effectiveness.

# Overview
Mental health conditions often require continuous monitoring of symptoms, behaviours, and treatment responses to ensure positive patient outcomes. This project presents an integrated Mental Health Diagnosis and Treatment Monitoring Dashboard built in Microsoft Power BI. 
The dashboard transforms raw clinical and behavioural data into clear, actionable insights that help track patient progress, understand factors influencing improvement, and evaluate the effectiveness of different treatment methods.
The dataset includes key patient attributes, such as diagnosis, symptom severity, mood score, stress level, treatment duration, adherence percentage, emotional state (as detected by AI), therapy type, medication, sleep quality, and physical activity. 
By combining these variables, the dashboard provides a holistic view of patient wellbeing and treatment performance.
The solution is designed with three pages:
1. Overview Page: A high-level summary of patient distribution, outcomes, diagnoses, and treatment trends.
2. Clinical Outcomes Page: Focused analysis of improvement, deterioration patterns, and the relationship between symptoms and progress.
3. Predictors, Behaviour & Adherence Page: In-depth exploration of behavioural indicators, predictors of treatment success, adherence impact, and AI-driven emotional insights.
This project demonstrates the use of advanced Power BI capabilities such as DAX, Key Influencers, categorisation logic, outcomes scoring, and behavioural modelling to deliver a complete mental health analytics solution.

<img width="912" height="512" alt="Screenshot 2026-01-22 194854" src="https://github.com/user-attachments/assets/70c1b4fe-a57f-4db2-829a-1ac19ab490a7" />
<img width="908" height="461" alt="Screenshot 2026-01-22 204653" src="https://github.com/user-attachments/assets/879ac766-a56e-43d8-904a-a28f1b53a11c" />
<img width="910" height="508" alt="Screenshot 2026-01-22 204715" src="https://github.com/user-attachments/assets/3f39e2a1-89fb-432b-bf72-38c4d8747c61" />

### Data Collection and Integration
---
The dataset was examined to understand field meanings, data quality, and the relationships between clinical, behavioural, and treatment-related variables. 
- Numeric columns such as Outcome were transformed into text-based. 
- Behavioural attributes like physical activity were categorised into meaningful groups.
- Missing or inconsistent entries were handled to maintain analytical accuracy.

### Tools
---
- Power BI.
- Power Query.
- DAX.

### Data Modelling and Transformation
---
Power Query and DAX were used to clean, normalise, and enrich the dataset:
- Created calculated columns (e.g., activity categories, adherence groups).
- Built measures for outcomes, improvement rates, and diagnosis frequency.
- Normalised categorical fields for consistency.
- Assigned numerical values to qualitative outcomes.
- Implemented DAX logic for trend calculations, progress measurement, and predictor evaluations.
- A star-schema-compatible structure was used to ensure efficient visuals and optimal performance.

### Visualisation and Insights
---
- Calculated measures to identify the various key performance indicators generated from the dataset.
- Developed visuals for my dashboard showing the most common diagnosis, total number of patients, rate of diagnosis by gender, diagnosis by age group, outcome by adherence, e.t.c.

### Conclusion
---
This mental health analysis and dashboard project demonstrates the power of data analytics in improving patient care and understanding treatment effectiveness. 
By combining clinical indicators, behavioural metrics, emotional insights, and treatment attributes, the dashboard enables a comprehensive view of patient health and progression. 
The solution makes it easy to identify:- 
- What drives improvement?
- Which behaviours need intervention?
- How adherence influences results?
- Which treatment methods are working?
- Where risks and deterioration patterns exist?
Through evidence-based visualization, clinicians, researchers, and health managers gain a clearer understanding of patient journeys and can make better decisions to support patient wellbeing.

### Recommendations
---
Based on the analysis of patient demographics, treatment methods, emotional states, adherence levels, and outcomes, the following recommendations are proposed to improve treatment effectiveness, patient well-being, and overall mental health service delivery:

1. Improve Treatment Adherence.
- Patients with higher adherence percentages showed better treatment outcomes.
- Introduce reminder systems, follow-up check-ins, and simplified treatment plans to support consistency.
- Utilise adherence tracking to identify at-risk patients early for targeted intervention.

2. Prioritise Early Emotional State Detection.
- The AI-detected emotional state proved useful in identifying patients at risk of deterioration.
- Integrate emotional state monitoring into routine assessments to enable early psychological support.
- Patients showing persistent negative emotional states should be prioritised for therapy review or escalation.

3. Personalise Treatment Plans.
- Different diagnoses respond differently to medication, therapy type, and duration.
- Adopt personalised care plans rather than a one-size-fits-all approach.
- Use diagnosis-specific insights to guide therapy selection and treatment duration.

4. Strengthen Stress Management Interventions.
- High stress levels were strongly associated with poor outcomes and low mood scores.
- Incorporate stress management programs such as mindfulness, relaxation techniques, and lifestyle counselling.
- Regularly monitor stress levels to assess treatment progress beyond clinical symptoms alone.

5. Encourage Physical Activity as a Supportive Intervention.
- Moderate physical activity levels were associated with better mood and sleep quality.
- Recommend structured, achievable activity plans based on patient capacity.
- Collaborate with wellness or fitness programs where possible.

6. Enhance Sleep Quality Monitoring.
- Poor sleep quality correlated with higher symptom severity and stress levels.
- Include sleep hygiene education and regular sleep assessments in treatment plans.
- Address sleep issues early as part of holistic mental health care.

7. Use Predictive Analytics for Proactive Care.
- Predictors such as adherence, stress level, emotional state, and physical activity can be used to anticipate treatment outcomes.
- Leverage these insights to identify patients likely to deteriorate and intervene proactively.
- This supports a shift from reactive care to preventive, data-driven mental health management.
