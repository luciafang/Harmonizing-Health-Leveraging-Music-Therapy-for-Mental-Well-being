**Harmonizing Health: Leveraging Music Therapy for Mental Well-being**
This project investigates how music can be used to improve mental well-being, focusing on the relationship between music preferences and mental health conditions such as anxiety, depression, insomnia, and OCD. We explore personalized music therapy recommendations based on individual preferences and therapeutic needs.

**Key Features**
1. Exploratory Data Analysis (EDA): Investigated trends in mental health conditions and music genre preferences.
2. Data Cleaning: Removed irrelevant or incomplete data, applied One-Hot Encoding for categorical features, and binned mental health scores.
3. Machine Learning Models: Applied Random Forest Classifier to predict mental health conditions based on music preferences.
4. Visualization: Used Altair to create bar charts, box plots, and heatmaps for analyzing the data.

**Installation**
To get started, ensure you have the necessary libraries installed: pip install pandas numpy scikit-learn altair

**Key Findings**
1. People experiencing improvements in mental health tend to listen to more K-pop and rap, while those who do not report improvements favor lofi and metal.
2. Depression was found to be the most predictive mental health condition in relation to music preferences, outperforming predictions for anxiety, insomnia, and OCD.
3. The model struggled with imbalanced data, leading to better predictions for "no effect" than "improvement" in mental health outcomes.

**Data**
1. Dataset: The project uses a dataset of mental health conditions (anxiety, depression, insomnia, OCD) and music genre preferences (K-pop, rap, lofi, etc.).
2. Data Cleaning: Features such as 'Age', 'Hours per day', and 'While working' were retained, while mental health scores were binned into low, medium, and high categories.

**Results**
1. Random Forest Classifier provided a 70% F1 score for predicting high anxiety and better-than-chance predictions for depression.
2. A significant imbalance in the dataset between "no effect" and "improvement" groups affected model accuracy, particularly for predicting improvements in mental health.

**Conclusion**
This project highlights the potential for using music preferences to inform personalized mental health therapies. While the model successfully predicted depression-related outcomes, more balanced data and additional demographic information are needed for robust predictions across all mental health conditions.

Collaborators: Amy Deng
