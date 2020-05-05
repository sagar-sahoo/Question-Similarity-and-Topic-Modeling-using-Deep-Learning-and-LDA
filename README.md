# Question-Similarity-and-Topic-Modeling-using-Deep-Learning-and-LDA

In the current world, the rate at which questions are being asked in online platforms is exceeding the capacity of qualified people to answer them, and many of the questions are repetitive. Identifying similar questions could enable businesses answer customer queries much more efficiently. Quora is a platform where in users ask questions to people with quality insights and answers. Quora gives importance to similar questions problem because it wants to provide a unique experience for both the user asking the question and the user answering the question. Through this work we focused on two things. 

First, checking the similarity of questions using deep learning. The main idea was to take up the questions, pre-process, tokenize and then vectorize the questions. We then used pre-trained GLOVE word embeddings trained on 6 Billion corpus and represented in 300 dimensions to represent the vectors. Then we fed the vectors to LSTM and Dense layers and predicted the similarity of question pair. 

The second part of the project comprises an application of Latent Dirichlet Allocation to categorize the Quora Question corpus into topic clusters. 

Through our experiment we achieved a training accuracy of 89% for the question similarity and classified the question corpus into 10 topic clusters.
