# EU_bank_turnover_explainability_project


Prepared for IBM Hackaton in Explainability

Prepared by Luis Antonio Coca Urdanivia

May 1, 2020

[Google Slides Presentation](https://docs.google.com/presentation/d/1GNjeJhyTScEyZIehNiRVWG7gV_P4p9oi4ci7kCqzD7c/edit?usp=sharing)
## Explainability EU Bank Turnover Dataset
Background:

A medium size bank in Europe is looking at checking which clients accounts are going to be closed in the next 6 months. They have records of staying clients as well as clients who left.  

Goal:

    -Utilize bank data to create an explainable model for stakeholders and peer Data Scientist.
    -Perform basic EDA to understand preliminary Features, describe the dataframe
    -Use Lale to create a pipelies for feature selection, Hyperparameter Tuning and model selection.
    -Select the model from the lale pipelines models selection.
    -Use AIX360 and Lime tools to visualize and explain features amongst models, which were useful, which were not
    
    
Expectations:

    -All relevant information pertaining to the dataset, methods, and algorithims are properly cited and explained
    -Source code is bug-free and self-contained
    -Analysis is accurate and pertinent to task at hand
    -Finall results explain properly the features selected
    
To understand this notebook, a user is expected:

    -Basic understanding of Linear Algebra and its applications (outer, inner product, etc.)
    -Basic understanding of descriptive statistics
    -Understanding of Object Oriented Programming
    
To run:

    -If on Unix or Linux, press 'cmd' + 'spacebar' to open the search bar, type 'terminal' and hit enter
    -In terminal, type 'which python', to check which python you are currently running
    -If in python 3, type 'pip install jupyter lab pandas numpy tensorflow'
original dataset at: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling
image credits: https://unsplash.com/@pampouks


### Explainability checklist
+ Who is our stakeholder?
    + Accounts Manager
+ what are their needs(problem Identification)?
    + identify which customers are more likely to leave in the next 6 months
+ what are the constraints/restraints of the project?
    + GDPR/ Data privacy / data management / not enough data (by date-transaction)
+ Where will the data be obtained?
    + Marketing sales, database
+ What impact is expected based on problem statement?
    + Provide incentives to identified clients for being active in account and increase cash flow 
+ What KPI will be measured in the system?
    + KPI is customer retention
+ How Will we Disseminate results?
    + Will create a presentation showing the most important features
+ Where will the end product live?
    + Product will live in in the transactions and marketing funnel



<figure class="video_container">
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vT95y_G3QKmaJKfzIltYFLt6FiLSjgZLRNL5y0Ut2AZl-EFVp13xEh9OKEI0Ev0MG6zpZmBoKRKuIhA/embed?start=true&loop=true&delayms=5000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</figure>

![alt text][PipelineSummary]
![alt text][HyperOut]
![alt text][PipeVizPlan]
![alt text][PipeVizFinal]
![alt text][ShapForce]
![alt text][ShapWater]












[PipelineSummary]: https://github.com/luisantoniococa/EU_bank_turnover_explainability_project/blob/master/PipelineSummary.png "Pipeline Summary"
[HyperOut]: https://github.com/luisantoniococa/EU_bank_turnover_explainability_project/blob/master/HyperparameterTunningOutput.png "Hyperparameter Tunning Output"
[PipeVizPlan]: https://github.com/luisantoniococa/EU_bank_turnover_explainability_project/blob/master/PipelineVizPlanned.png "Pipeline Visualization Planned"
[PipeVizFinal]: https://github.com/luisantoniococa/EU_bank_turnover_explainability_project/blob/master/PipelineVizFinal.png "Pipeline Visualization Final or Trained"
[ShapForce]: https://github.com/luisantoniococa/EU_bank_turnover_explainability_project/blob/master/ShapForcePlot.png "Shap Force Plot"
[ShapWater]: https://github.com/luisantoniococa/EU_bank_turnover_explainability_project/blob/master/ShapWaterfallPlot.png "Shap Waterfall Plot"
