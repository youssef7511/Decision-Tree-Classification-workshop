# Decision-Tree-Classification-workshop
what i did:/

1. Download the play_tennis.csv dataset. The dataset contains the following
attributes:
- Outlook: the aspect of the sky (Sunny, Overcast, Rain)
- Temperature: the temperature (Hot, Mild, Cool)
- Humidity: the humidity level (High, Normal)
- Windy: whether it's windy or not (True / False)
- PlayTennis: target variable indicating whether the person played tennis that day
(Yes / No)
2. Load the data into a DataFrame with pandas.
3. Check for missing values.
4. Encode categorical variables.
5.
6. Convert the categorical variables into numerical variables using
pd.get_dummies().
7. Separate the explanatory variables (X) and the target variable (PlayTennis).
8. Encode the target variable (Yes/No → 1/0).
9. Create a DecisionTreeClassifier (from sklearn.tree) and
train it on the data.
10. Visualise the decision tree using plot_tree from matplotlib.
11. Explore the importance of the variables.
12. Test the model on a new observation to predict whether we will play
tennis in a new weather context.

Outlook Temperature Humidity Windy
Sunny Hot High False

3
- Encode categorical variables:
Use pd.get_dummies() to convert the Outlook,
Temperature and Humidity columns into binary numeric variables.
- Add missing columns:
Make sure that all the columns present in the
training data (X.columns) also exist in new_data. If some
columns are missing
