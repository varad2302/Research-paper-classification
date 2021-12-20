# Research-paper-classification

I tried out various methods for multi-label classification of roughly 700k research papers on Arxiv.  
Approches implemented:
1. Naive Bayes using OnevsAll strategy (Naive Nayes.ipynb)
2. LSTM(using pretrained GloVe embeddings as well as training embedding layer from scratch) (LSTM.ipynb)
3. Fine-tuned [SciBERT](https://arxiv.org/abs/1903.10676)(BERT trained on scientific texts) (BERT.ipynb)

Dataset used: [Arxiv](https://www.kaggle.com/Cornell-University/arxiv/tasks?taskId=1757)  
Pre-trained GloVe embeddings can be downloaded from [here](https://nlp.stanford.edu/projects/glove/).(I have used the 840B vocab, 300 dimensional vector embeddings)
