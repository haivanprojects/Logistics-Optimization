# Logistics Operations Optimization & Delivery Delay Prediction

Project Overview
This project focuses on applying **Predictive Analytics** and **Prescriptive Analytics** to solve real-world logistics and supply chain challenges. The goal is to optimize delivery routes, maximize container packing efficiency, and predict potential delivery delays to improve overall operational performance.

Tools & Technologies
- Programming Language: Python
- Libraries: Pandas, Scikit-learn (Machine Learning), Google OR-Tools (Optimization), Folium (Visualization)
- Other Tools: Microsoft Excel (Linear Programming / Solver), Power BI

Key Business Problems Solved

1. Delivery Delay Prediction (Predictive Analytics)
- Objective: Predict the likelihood of delivery delays to proactively alert customers and manage resources.
- Methodology: Built, trained, and evaluated a **Decision Tree Classifier** model using historical delivery data.
- Files: `Decision tree_Delay_Data optimisation.ipynb`, `Delay.csv`

2. Vehicle Route Optimization (Prescriptive Analytics)
- Objective: Minimize total travel distance for a fleet of 4 delivery vans (Vehicle Routing Problem - VRP).
- Methodology: Formulated the problem and utilized **Google OR-Tools (CP-SAT solver)** to compute optimal routes. Visualized the physical paths on an interactive map using **Folium**.
- Files: `OR-Tools CP-SAT.ipynb`, `route_optimisation_visualize.ipynb`

3. Container Loading Optimization
- Objective: Maximize cargo profit by optimally packing a container while strictly adhering to weight and volume constraints.
- Methodology: Formulated and solved a **Linear Programming (LP)** model.
- Files: `Container_LP_calculate.xlsx - LP_ExampleStyle.csv`

Presentation & Business Context
Detailed business context, methodology explanation, and final recommendations can be found in the presentation materials:
- `DA_presentation.pptx` (Presentation Slides)
- `Scripts.pdf` (Detailed Presentation Script
