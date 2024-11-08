# Diversity-Graphormer

This repository contains data (all freely available) and code to reproduce the experiments from the paper "Graphormer Meets Diversity: A Case Study in Sarcastic Hate Speech Detection on 4chan"
![Graphormer Figure](https://github.com/the-paper-acc/Diversity-Graphormer/blob/344d5b5f90982f73bfaa5022bf2b9bf27d140bc1/Files/paperfig2.png)

The Files folder contains a zip file with all the datasets used in training and evaluating the proposed and baseline models:
- The [Slur corpus](https://github.com/networkdynamics/slur-corpus) file ("kurrek.2020.slur-corpus.csv")
- The [4chan Dataset](https://github.com/YitingQu/meme-evolution) file ("rewire.txt")
- The [iSarcasm](https://github.com/dmbavkar/iSarcasm) training file ("trainEN.csv")
- The set used for the qualitative validation of the models, with examples from the 4chan Dataset ("HS Expert.csv")
- The Trained Models folder, with the trained models in .pt

The Notebooks folder contains the code to train and evaluate the models.
