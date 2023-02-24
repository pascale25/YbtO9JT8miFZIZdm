# NLP _ Project _ Ranked Candidates

## Ranked candidates based on job requirements using a combination of 5 models incorporating word2vec, TF-IDF, GLOVE, and a pre-trained BERT model.


Models:

Word2Vec model
TF_IDF model (unigram, bigram an trigram)
word2vec pretrained model
Glove - pretrained model
Bert - pretrained model

We developed multiple models and assigned rankings to candidates based on the match between the job title and requirements. However, the rankings varied depending on the model used. To find the most accurate ranking, we calculated the average score for each candidate across all models. The results were satisfactory, as the top 10 candidates were consistent across most models. To further improve the accuracy, it would be beneficial to closely examine the job titles of the top 10 candidates in relation to all models and identify which model aligns closest with reality, thus providing insight for algorithm selection and improvement.
