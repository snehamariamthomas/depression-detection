# Depression Detection on Reddit: An NLP Approach
![Alt Text](mental_health.jpg)
###### Image Source: College of Animal Welfare

# Summary
This project explores the detection of depression in Reddit posts through text analysis and machine learning techniques. Reddit, with its anonymous environment, allows users to openly discuss mental health issues, making it a valuable source for understanding and detecting depression. Accurate detection is crucial for timely support and intervention, addressing the stigma that often surrounds mental health discussions.

The methodology involved preprocessing text data from Reddit posts, applying Term Frequency-Inverse Document Frequency (TF-IDF) analysis to identify distinctive linguistic patterns, and evaluating various classification algorithms. Key algorithms included Naive Bayes, Ridge Regression, and Lasso Regression. The analysis aimed to uncover linguistic markers and refine detection accuracy by employing unigram and bigram models.

Findings indicate that Lasso Regression with bigram analysis outperformed other methods, achieving high accuracy, precision, and recall. The Lasso regression analysis pinpointed key linguistic markers like "job_fire," "anxieti," and "someon_talk" that signify depression. This nuanced approach enhances the model's sensitivity to language patterns, capturing diverse facets such as life stressors, emotional turmoil, and social dynamics, significantly boosting its robustness in detecting depression within online discourse.

The results underscore the importance of effective detection models in digital mental health tools, highlighting how advanced machine learning techniques can improve mental health support and intervention strategies.

# Technical Skills and Tools

| **Category**               | **Skills and Tools**                                         | **Description**                                                  |
|----------------------------|--------------------------------------------------------------|------------------------------------------------------------------|
| **Data Manipulation and Cleaning** | Text cleaning, Tokenization, Stemming                    | Removing numbers, symbols, URLs, stopwords; Tokenizing and stemming text |
| **Natural Language Processing (NLP)** | Unigrams and Bigrams, TF-IDF                              | Creating and manipulating text corpora; Analyzing text using n-grams and TF-IDF |
| **Machine Learning**      | Naive Bayes, Ridge Regression, Lasso Regression             | Building predictive models; Evaluating performance using confusion matrices, accuracy, precision, recall, F1 score |
| **Data Visualization**     | Word Cloud Visualization, Plotting Coefficients             | Visualizing text data and model coefficients                     |
| **Programming Language** | R                                              | Executing data manipulation, analysis, and visualization tasks   |
| **Packages in R**          | `quanteda`, `quanteda.textplots`,`caret`, `glmnet`, `ggplot2` `tidyverse` |, For text analysis, model building and visualization |

# Data

- **[Depression Reddit Cleaned Dataset](https://www.kaggle.com/datasets/infamouscoder/depression-reddit-cleaned/data)**: The dataset used for this analysis is available on Kaggle.
