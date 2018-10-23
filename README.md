# IMDB_MR

在这里选用了多种 **文本分类** 方法进行IMDB数据集的 **情感分类** ：

- 采用基本的MachineLearning方法（LR、NB、RF）（采用Tfidf权重，n-gram特征）
- 采用stacking的思想进行模型融合
- 采用fasttext的思想（n-gram + 词嵌入）
- 采用doc2vec进行文本表示
- 采用word2vec + 多种DeepLearning方法（包括TextCNN、Bi-LSTM、RCNN、HRNN）
- 采用DeepLearning + Attention的方法

dataset: https://www.kaggle.com/c/word2vec-nlp-tutorial/data

