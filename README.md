# Numerical_Feature_Selection
in this section will be numerical feature selection on diabetes dataset

________________

# Feature Selection

**Feature selection** is the process of selecting a subset of relevant features from a larger set to improve model performance or reduce computational complexity. *Types of feature selection* refers to various methodologies or approaches used to select a subset of features from the original feature set. These methodologies can be broadly categorized into three main types:

* Filter Methods
* Wrapper Methods
* Embedded Methods

________________________

# Numerical Feature Selection

* **Filter Methods**


  1. **Mutual Information**: Measures the relationship between two random variables; assesses the information gain by measuring the relationship of features with the target variable.

  2. **Chi-Squared**: Measures the relationship between categorical independent variables and a categorical target variable; tests the association between two categorical variables.

  3. **f_classif**: is a feature selection method commonly employed to evaluate the influence of features on a classification task, often utilizing ANOVA (Analysis of Variance). ANOVA is utilized to determine the statistical significance of the relationship between each feature and the target variable. High F-statistic values resulting from ANOVA imply a substantial association between the feature and the target, indicating its importance for classification. Conversely, low F-statistic values suggest a weaker impact. This technique plays a crucial role in feature selection processes aimed at enhancing model performance by selecting the most informative features.

  4. **ROC_AUC**: Calculates the area under the Receiver Operating Characteristic (ROC) curve (AUC), evaluating classifier performance; a higher ROC AUC value indicates better classifier performance.

  5. **Correlation**: Measures the linear relationship between features; assesses the correlation between features using statistical metrics such as the Pearson correlation coefficient.
