---
layout: post
title: "Lagged kNN Approach for Data Imputation"
---

<div class="row md-6">
  <img src="{{ site.github.url }}/assets/img/primary-investigator.jpg" width="50%" height="50%">
<div class="row-md-6" style="text-align: justify">
    <br>
    Increasing advancements in building digitization, smart sensing, and metering technologies have allowed large amounts of data to be collected and saved for monitoring, analyzing, and controlling building systems. However, due to sensor or communication failures, the data collected are often incomplete and poor in quality. Data imputation approaches to replace the missing values, specifically based on both statistical and predictive models have been widely adopted for multivariate datasets. It is hence of interest to find an effective way to impute building system data by leveraging the mutual information from strongly correlated sensors. In this paper, we evaluate multiple data imputation approaches using data collected from a medium sized, mixed-use institution building situated in Stockholm, Sweden and a small commercial building simulated in laboratory setup as part of the ASHRAE-1312 research project. Sensors with widely varying characteristics from the case study buildings were selected to test the imputation methods. Artificial test data with ground-truth information was first created for validation by removing randomly selected portions of data. The imputation accuracy was computed for each method and the impact of the chosen method on information entropy, short-term building forecasting model performance and fault detection strategy were evaluated. Results demonstrate that incorporating time-lagged cross correlations within the k-nearest neighbor (kNN) model provide the most accurate imputations without affecting the quality of subsequent data analysis.
</div>
</div>


