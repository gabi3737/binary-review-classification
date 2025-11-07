# binary-review-classification
NLP solution for a binary classification of comments about products using Python (PyTorch, CUDA, BERT) and compared different technologies’ accuracy

##Begin readme
there are three code files:
baseline.ipynb - contains code for building and training the baseline LR model
improved.ipynb - contains code for building and training the improved BERT model
testing.ipynb - contains some code for testing, validation and some graphs

Additionally, the zip contains:
readme.txt - this file
train.csv - the main dataset - extracted from : https://www.kaggle.com/datasets/arashnic/game-review-dataset/data

!!!!IMPORTANT!!!!: If, for any reason, the dataset must be re-downloaded, ONLY the train.csv file is important, everything else is unimportant


Due to the above notebooks having been written and implemented using Google Colab, the directory dependencies are as follows:
The files will all connect to Google drive (as content/gdrive/)

My directory layout was as follows:
content/gdrive/My Drive/Uni/NLP (this makes up "main_path" in the files)
NLP/data/ (this makes up data_path) contains train.csv
NLP/models/ (this makes up model_path) contains the following files: logistic_regression_model.joblib ;
count_vectorizer.joblib; 
#^The above make up the LR baseline model and have details on how to run them on validation data in testing.ipynb
vocab.txt;
special_tokens_map.json
tokenizer_config.json;
model.safetensors;
config.json;
#^The above make up the BERT improved models and have details on how to run them on validation data in testing.ipynb

#if needed, change main_path / data_path / model_path to your Google drive respective directories.

If any further issues arise, please contact me at gabi.prefit@city.ac.uk
