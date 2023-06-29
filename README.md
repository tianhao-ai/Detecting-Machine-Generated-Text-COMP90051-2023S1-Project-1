# Detecting-Machine-Generated-Text-COMP90051-2023S1-Project-1
This project is about to detecting the text generated by different LLM given prompts. The instance is labelled by Human and Machine, and this project utilised both traditional machine learning method and deep learning method to classify the instance.

# Result of the project
According to the result from the private board, LGBM could achieve 76% overall accuracy to detect LLM-generated text:
![private and public result](graph/lgb_accuracy.png)
also ranked 7th in the private leaderboard, which is top 10%:
![private and public result](graph/kaggle_rank.png)
finally, scoring 11.75/12 in the Kaggle competition in Project 1:

![private and public result](graph/score.png)

# File Description
* `exploratory_data_analysis.ipynb`: This notebook mainly focuses on data analysis, expecting to find insight into the data.
* `lgb-comp90051.ipynb`: This notebook utilises the LGBM classifier to detect the LLM-generated text.
* `gru-comp90051.ipynb`: This notebook utilises the GRU to detect the LLM-generated text.
* `transformer-comp90051.ipynb`: This notebook utilises the Transformer to detect the LLM-generated text.

# Exploratory data analysis


