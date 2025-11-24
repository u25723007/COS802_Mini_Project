This project is about investigating sentiment analysis aproacu for Sesotho, a low-resource African language.
Three approaches tested here:
1. Monolingual learning using Afro-XLM-R
2. Cross-lingual transfer leanrning using BERT-base-uncased and Google Translate
3. Learning from languages with similar semantics using puoBERTa

# Dependancies
Language: python

Libraries: transformers, googletrans, pandas, datasets, numpy, plotly, torch, imblearn, sklearn, matplotlib


# Datasets
[Sesotho News Healines Dataset ](https://zenodo.org/records/10531959/files/NewsSA.txt?download=1)

This data is already included in the ziped file, but you can also download it from the above link, its publicly available.

# Execution
the script file is : Sesotho_Sentiment_Analysis.ipynb
To run the script, place the dasetfile (NewsSA.txt) in the same location as the python script and do the following:
1. If you are running from a local machine, comment this line in the script file_path = "/content/drive/MyDrive/NewsSA.txt"
2. if you are running on google colab, confirm that this is the correct location for the dataset : file_path = "/content/drive/MyDrive/NewsSA.txt"
     othewise modify the path to match your location.
these line are loacted at the begging of the file, immediatly after importing libraries
   Then press run all button on the script. Everything will run.
   Lookout for model training pop-ups https://wandb.ai/ for model training
   
All three parts will with results per part, and the final results at the end.
