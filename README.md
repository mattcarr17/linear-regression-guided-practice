
# Linear Regression Guided Practice

 In this guided practice, you'll be using data collected by the WHO about life expectancy to try and understand potentially-related factors. The information is aggregated on a per-country per-year basis. Explanations of the data variabales can be found in `DATA.md`

#### Overview
1. Initial EDA
2. Baseline Model
3. Check Assumptions
4. Iterations

We'll start by importing the relevant modules and loading the data below.


```python
# run this cell without changes
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sm
from statsmodels.formula.api import ols
```


```python
# run this cell without changes
df = pd.read_csv('../data/life_expectancy.csv').drop('Unnamed: 0', axis=1)
df.head()
```

## Initial EDA

Before we get into modeling, we want to have a better idea of the data we are working with. Your EDA can be as extensive as you wish, but for the purposes of this notebook we will want to at least do the following:
- Check shape of dataframe
- Check for missing values
- Explore distribution of target variable
- Look at correlations with target variable


```python
# your code here (add as many cells as needed)
```


```python

```

### Baseline Model

Now that we have a better understanding of our data, it's time to create our first model. After investigating how the independent variables correlate with the dependent variable above, please choose three independent variables you would like to create the baseline model with. Using these three independent variables create a multiple linear regression model to predict `life_expectancy`. **NOTE** you may need to handle missing values.

Once you have fit your model, please print the model summary and do the following:
- Identify the extent these three variables explain the variance of `life_expectancy`
- Interpret the intercept and coefficients
- Conclude whether each coefficient is statistically significant


```python
# your code here (add as many cells as needed)
```


```python

```

### Check Assumptions

A key component of inferential modeling is to ensure our model meets the assumptions of linear regression. 

1. **Linearity** - The independent variables linearly predict the dependent variable (linear relationship between them).

2. **Normality** - The model's residuals are normally distributed.

3. **Homoscedasticity** - The residuals have a consistent variance across entire range of dependent variable

4. **Independence** - Independent variables are not too highly correlated to one another (no multicollinearity)

Please check each of these assumptions for the baseline model you created above.


```python
# your code here (add as many cells as needed)
```


```python

```

### Iterations

Create additional model iterations. Be sure to check the assumptions of linear regression after each.


```python
# your code here
```


```python

```
