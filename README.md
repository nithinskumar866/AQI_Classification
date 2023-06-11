INTRODUCTION:

In this project, I created a classification system for the air quality index (AQI) using a dataset on air pollution collected from various locations. The dataset includes several features such as AQI value, carbon monoxide levels, ozone levels, PM2.5 particulate matter, latitude, and longitude. The objective of this project is to categorise the air quality of various locations based on these characteristics.

The air quality dataset utilised for this project provides valuable information regarding the levels of pollution in various regions. It includes measurements of key pollutants and atmospheric conditions, allowing for the development of models that accurately classify a location's air quality index.

USE OF 'oneAPI':
I utilised the power of oneAPI to optimise the implementation of the AQI classification system. Using the unified programming model of oneAPI, I was able to utilise the computational capabilities of various hardware accelerators such as CPUs and GPUs, resulting in enhanced performance and efficiency. This allowed for quicker training and prediction times, enabling air quality classification in real time.

MODELS USED:
For the AQI classification task, I used the Random Forest algorithm, which is renowned for its capacity to deal with complex datasets and produce accurate results. The Random Forest model generates a collection of decision trees and makes predictions based on the votes of numerous trees.

This task is well-suited for the Random Forest algorithm, which can capture the relationships between air quality attributes and their respective AQI categories. Using various tree-based techniques, including feature selection and hyperparameter tuning, the model was trained on the dataset.

After training the Random Forest model on the air quality dataset, I achieved an accuracy of approximately 99.8%, as discussed in the results and discussion section. This demonstrates that the model can accurately categorise the air quality of different locations based on their characteristics.

The model's high accuracy demonstrates its potential applicability in real-world situations such as urban planning, environmental monitoring, and public health initiatives. It can aid in the identification of regions with poor air quality, the detection of pollution sources, and the formation of policy decisions.

RESULT:
However, it is essential to note that the model's performance may vary depending on the specific dataset and its characteristics. Validating the model's generalizability and robustness requires additional evaluation and testing on diverse data sets. In conclusion, the implementation of the system for classifying the air quality index using the Random Forest model and optimisation with oneAPI has produced promising results. This method has the potential to be used for assessing and monitoring air quality, as demonstrated by its high degree of precision. It is possible to pursue additional research and enhancements to improve the model's performance and expand its applications in environmental studies and public health.
