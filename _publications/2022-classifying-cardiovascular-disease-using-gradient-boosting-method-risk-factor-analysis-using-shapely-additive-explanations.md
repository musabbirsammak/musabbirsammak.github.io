---
title: "Classifying Cardiovascular Disease Using Gradient Boosting Method Risk Factor Analysis using Shapely Additive exPlanations"
collection: publications
category: conferences
permalink: /publication/classifying-cardiovascular-disease-using-gradient-boosting-method-risk-factor-analysis-using-shapely-additive-explanations
excerpt: 'We trained a LightGBM model with 5-fold cross-validation to identify key features for accurate heart disease detection, achieving 0.85 auROC (95% CI: 0.70–0.99), 0.81 auPRC (95% CI: 0.59–0.99), 91.8% recall, and 77.5% precision on test data. SHAP values were used to rank important features, offering clinicians actionable insights to improve diagnosis and potentially save lives.'
date: 2022-10-5
venue: '2022 13th International Conference on Computing Communication and Networking Technologies (ICCCNT)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9984277'
citation: 
bibtexurl: '../files/publications/bibtex/classifying-cardiovascular-disease-using-gradient-boosting-method-risk-factor-analysis-using-shapely-additive-explanations.bib'
---

One of the worst diseases in the world is heart disease or cardiovascular disease. Heart disease is on the rise globally, and doctors are becoming quite concerned about it. Therefore, it’s crucial to accurately identify heart disease kinds when you require them. The complete understanding of cardiac disease has become one of the most popular scientific topics. In order to determine the best feature for accurately identifying heart disease, we worked with the "statlog" dataset. There, we trained our model using the LightGMB Python module. It is the Boosting Machine framework. We utilized the auROC score together with a 5-fold cross-validation for performance measurements. Figure 3 displays the results on the test data, which were 0.85 auROC with a 95% confidence interval of 0.70-0.99. However, it obtained 0.81 auPRC with a 95% confidence interval of 0.59 to 0.99. It obtained recall scores of 91.83% and precision scores of 77.52%. Shapely Additive exPlanations or shape value is utilized to discover the best features in this case. We categorize our heart disease datasets by identifying the most effective characteristics. As a consequence, it will assist medical professionals in identifying cardiac disease through practical application and help save countless lives