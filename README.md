# Predicting-Mental-Health-Illness
The project's aim is to predict mental health illnes (depression, schizophrenia, obsessive compulsive disorder, etc) of a user based on his or her comment in social networks. The code consists of few parts:
1) Lemmatization of text comments
2) Balancing data through agumentation of underpresented classes: using of RuWordNet database (https://github.com/avidale/python-ruwordnet) to replace words with synonyms 
3) Preprocessing data
4) Building an embedding layer (https://github.com/natasha/navec)
5) Compilation of a CNN: this type of models has shown the best results spending a comparatively little time on training
6) Training and validation of a model 

