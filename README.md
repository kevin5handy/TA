# Analysis of the Effect of Adding the Charge-Discharge Cycle Index Variable on the Accuracy of State of Charge (SOC) Estimation in LiFePO₄ 18650 Batteries Using Deep Neural Network and Various Tree-Based Regression Algorithms

In the context of battery state of charge (SOC) estimation modeling, this research
focuses on testing the change in SOC model accuracy when an additional variable,
namely the charge-discharge cycle index, is included alongside the primary
variables (voltage, current, and temperature). The inclusion of this variable is
based on the expectation that the model should be robust and adaptive as charging
and discharging activities continuously occur in the battery. The objective of this
study is to analyze the influence of adding the charge-discharge cycle index
variable on the accuracy of the SOC estimation model for LiFePO4 18650 batteries
using a deep neural network (DNN) and various tree-based regression algorithms
(random forest regressor, decision tree regressor, and gradient boosting
regressor). This study utilized three LiFePO4 18650 batteries with varying constant
current values of 180mA, 210mA, and 240mA, each tested over two cycles for the
primary dataset. An additional dataset with a constant current of 240mA from the
third cycle was also acquired to test the model's robustness. The methodology for
this research includes data acquisition, data preprocessing, modeling using four
machine learning algorithms, and model evaluation and analysis. The research
findings indicate that model accuracy consistently improved across all four
algorithms used for the primary dataset with the addition of the cycle index variable
(from MAE < 2.0% to MAE < 1.8%). For model testing on the additional dataset,
accuracy also consistently improved for models with tree-based regression
algorithms (from MAE < 4.5% to MAE < 3.7%). However, for the DNN model, the
addition of the cycle index variable resulted in a significant error spike (from MAE
< 5.3% to MAE > 35.0%). This was attributed to the limited cycle index data, which
caused the DNN model to misinterpret new data. All four algorithms show
significant potential for further development and real-world application, and this
research is expected to contribute to future studies by providing consideration for
using the cycle index variable for SOC estimation
