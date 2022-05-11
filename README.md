# Energy-Efficiency

**Overview**

The effect of eight input variables (relative compactness, surface area, wall area, roof
area, overall height, orientation, glazing area, glazing area distribution) on two output
variables, namely heating load (HL) and cooling load (CL), of residential buildings is
investigated using a statistical machine learning framework.

**Dataset**

The Dataset you can get through this link: https://docs.google.com/spreadsheets/d/1V7e5nX-ER2uU12u3TKvM-wjmxfN2hITE/edit#gid=453908598

The dataset contains eight attributes (or features, denoted by X1...X8) and two
responses
(or outcomes, denoted by y1 and y2).

**Approach**

The classical machine learning tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and Model Testing. Tried out different machine learning algorithms to determine the best fit for the above case.

**Technical Aspect:**

1)Cleaned the data as necessary such as changing the type,etc.

2)Visualizing the data using various modules such as Matplotlib.

3)Built models such as Linear regression, Logistic Regression,K-Nearest Neighbor,Decision Tree,Random Forest,Gradient Boosting and XG Boost.Also evaluated each model using R^2 score, to choose among them the best model.

Finally,done the feature importance of the best model.

**Result**

Relative Compactness(X1),Surface Area(X2),Roof Area(X4) and Overall Height(X5)are the important feature to determine the Heating and Cooling load.

**Technologies Used**

Pandas

Google Colab Notebook

Matplotlib

Sckit-Learn
