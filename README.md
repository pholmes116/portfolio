# Data Science
#### Technical Skills: Python, R, Stata, Machine Learning, Artificial Intelligence, Statistical Analysis, Causal Inference

## Education
- The London School of Economics and Political Science (_August 2025_)
  - M.Sc. in Data Science
- Duke University (_May 2021_)
  - B.S. in Economics
  - B.A. in Mathematics

## Projects
### Evaluating Synthetic Data for Financial Applications (Collaboration with Mastercard)
#### _Capstone Project, M.Sc. in Data Science at LSE | November 2024 - August 2025_

This project was completed in collaboration with Mastercard as the final Capstone Project for my M.Sc. in Data Science. Due to a Non-Disclosure Agreement, I am unable to share the full report or code repository. However, the project involved work in Python (Pandas, Scikit-learn, AIF360), statistical bias assessment, fairness-aware preprocessing, and performance benchmarking across classification pipelines. This experience deepened my skills in designing reproducible evaluation frameworks, aligning data science methods with real-world business constraints, and working under strict data governance protocols.

### Predicting Player Trajectories in the National Football League Using Deep Learning
![NFL Trajectories](/assets/img/Predicted-NFL-play.png)
- [Research Report](/projects/NFL-player-trajectories.pdf)
- [GitHub Repo](https://github.com/pholmes116/NFL-player-trajectories-public)

This research involved applying deep learning methods to the NFL’s player tracking data to predict the movement of all 22 players and the ball during plays. Project components included developing a scalable data pipeline using Polars for preprocessing, feature scaling, and event encoding, and creating custom dataset generators with TFRecord export to support efficient Transformer training. We trained architectures capable of capturing complex spatiotemporal dynamics and designed visualization tools to compare predicted and actual player trajectories across the field. Through this work, I gained experience building scalable data pipelines, training deep learning models for sequential prediction, and analyzing high-dimensional, real-world datasets.

### Exploring the Economic and Vehicle-Level Factors That Influence Used-Car Prices in the United Kingdom
![UK Used Cars](/assets/img/UK-unemployment-vs-CPIH.png)
- [GitHub Repo](https://github.com/pholmes116/UK-used-car-prices-public)

This research involved analyzing datasets from the UK Office of National Statistics and a Kaggle sample of 100,000 used cars to understand what drives pricing in the UK used-car market. Project components included data cleaning, feature engineering, and exploratory visualization to examine market trends alongside vehicle-level attributes. We applied statistical plots, time-series analyses, and correlation studies to identify how factors such as mileage, transmission, engine size, and fuel type influence resale prices. Through this work, I gained experience integrating heterogeneous data sources, applying visualization as a tool for storytelling, and managing end-to-end data workflows that link exploratory analysis with predictive modeling.

### Comparing Distributed Machine Learning Models for Patient Cost Prediction Using Synthetic Electronic Health Records
- [Research Report](/projects/Predicting-healthcare-costs.pdf)
- [GitHub Repo](https://github.com/pholmes116/predicting-healthcare-costs-public)

This research investigated how distributed machine learning could be used to predict patient-incurred healthcare costs from synthetic electronic health records generated with Synthea. Project components included building a scalable pipeline in PySpark on Google Cloud Platform with HDFS for distributed storage to preprocess large encounter-level datasets, engineer features, and train regression models including Linear Regression, Random Forest, and Gradient Boosted Trees. We also applied Latent Dirichlet Allocation (LDA) for topic modeling to uncover patient subgroups based on encounter descriptions and combined these insights with regression models to improve predictions. Results highlighted the trade-offs between accuracy and scalability, with Gradient Boosted Trees offering the highest accuracy but at significant computational cost, while ensembles provided a practical middle ground. Through this project, I gained experience with distributed data pipelines, scalable cloud infrastructure, and applying predictive and topic modeling techniques to complex, high-volume healthcare data.

### Evaluating Classical Artificial Intelligence Algorithms on Standard and Variant Forms of Connect Four
- [Research Report](/projects/Connect-four-ai.pdf)
- [GitHub Repo](https://github.com/pholmes116/connect-four-ai-public)

This research involved implementing and comparing three classical AI algorithms for Connect Four: Monte Carlo Tree Search, Alpha-Beta Pruning, and Alpha-Beta Pruning with a heuristic evaluation function. After hyperparameter tuning on the standard 7x6 board, we tested the algorithms in tournaments that included rule variations such as larger and smaller boards, a three-player setup, and the introduction of blocker stones. These modifications allowed us to evaluate how each approach balanced win rate and computational efficiency across increasingly complex environments. Results showed that while Monte Carlo Tree Search performed well with large branching factors, Alpha-Beta with evaluation was the most consistent and adaptable agent overall. Through this project, I gained experience in implementing game-tree search algorithms, designing controlled experiments for AI evaluation, and analyzing the trade-offs between accuracy, efficiency, and adaptability in algorithmic decision-making.

## Work Experience
### Bates White Economic Consulting - Washington, D.C.
#### _Senior Consultant | September 2021 - August 2024_
At Bates White, I worked in the Mass Torts and Antitrust practices on projects involving high-profile litigation and liability valuation. My work included building and analyzing large databases of historical tort claims in Stata and R, developing dynamic insurance allocation models, and supporting expert testimony with statistical and forecasting analyses. I also contributed to evaluating competitive effects in a multibillion-dollar admixture merger. These projects deepened my experience in data engineering, statistical modeling, and applied econometrics within a rigorous consulting environment.
