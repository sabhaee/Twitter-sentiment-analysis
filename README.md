This repository contains sentimnent analysis of tweets using a finetuned version of BERT language model. Google colab notebooks were used for model training, data processing and sentiment analysis.
## Colab Notebooks :
Two main colab notebooks used for this sections are as follows:
- Fine-Tuning_and_Training_BERT :
This notebook perfoms the text cleaning and preprocessing and subsequently uses the labeled tweet dataset and cloud GPU to train a fine tuned BERT model. Description of the code is provide in the notebook.Labeled tweet dataset used for the trainig will be downloaded in the notebook it can also be accessed from this [link](https://www.kaggle.com/kazanova/sentiment140).

Access notebook in colab from this [link](https://colab.research.google.com/drive/1FicAdDkFhe0rRobwbBSonmuNaSVFB3iZ?usp=sharing).


- Sentiment_Analysis_with_BERT :
This notebook performs the data cleaning and encoding on the unlabeled collected tweet dataset. Encoded tweet data then will be classified using the nodel trained in the BERT_Training note book. Finally the overal sentiment analysis is collected in two files currently in the result folder in the current directory:
1. Overal_result.csv containig the frequency of positive, negative and neutral sentiment for each day in the original tweet dataset
2. daily_result folder containig separate csv result files with cleand version tweet texts and their corresponding sentiment probability and prediction, for each day of the in the orginal tweet datset.

Access notebook in colab from this [link](https://colab.research.google.com/drive/1HABn0JGshF2TJGZmL061ABJgy8BvY1GE?usp=sharing).


## Model State and Checkpoint:
Model state files and model checkpoint are not save in this repository due to the large file sizes, All requiured models state and model checkpoints will be downloaded directly in the colab notebooks. Additionaly the best model state can be access [here](https://drive.google.com/file/d/1afvHvYRK2qvOMk-oVF6KDYrIO6hpUAik/view?usp=sharing) and the latest model check point can be downloaded from [here](https://drive.google.com/file/d/1alaDfFsBbJ9WiTkKFdKkERCfb022Ai7E/view?usp=sharing).