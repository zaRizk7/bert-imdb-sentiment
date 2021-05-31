# IMDB Dataset Sentiment Analysis using BERT
Sentiment analysis using BERT model with 50K IMDB Movie Reviews (https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) dataset. The model is fully build using Tensorflow with addition of pre-trained BERT model provided in Huggingface's transformer library and trained (fine-tuned) using NVIDIA Tesla P100 GPU provided by Kaggle. Additionally, there is also newly added Pytorch version with similiar results. The scores for the trained model are as follows:
| Metric                    | Score  |
|---------------------------|--------|
| Train Accuracy            | 0.9903 |
| Validation Accuracy       | 0.9164 |
| Test Accuracy             | 0.9235 |
| Train Macro F1-score      | 0.9903 |
| Validation Macro F1-score | 0.9164 |
| Test Macro F1-score       | 0.9235 |
