Data Preparation:
Imported necessary libraries (pandas, seaborn, matplotlib).
Loaded the data into Google Colab.
Explored the structure of the dataset using df.head().
Data Cleaning:
Checked for missing values and handled them (filled NaN values).
Dropped irrelevant columns ('Timestamp', 'What is your grade/year of studies?').
Encoded categorical variables using one-hot encoding.
Exploratory Data Analysis (EDA):
Conducted a univariate analysis by visualizing the distribution of individual variables (e.g., age, gender) using histograms.
Explored relationships between numerical variables using a correlation matrix.
Visualized distributions and relationships for categorical variables (e.g., gender distribution).
Statistical Analysis:
Computed descriptive statistics (mean, count, etc.) for key variables.
Conducted segmentation and grouping, such as grouping by grade/year of studies and calculating mean satisfaction.
Machine Learning Model:
Split the data into training and testing sets.
Trained a Random Forest Classifier to predict satisfaction levels.
Evaluated the model's performance using accuracy, classification report, and confusion matrix.
Visualization:
Created visualizations, including histograms, a correlation matrix heatmap, and a confusion matrix with colors.
