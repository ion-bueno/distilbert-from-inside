# DistilBERT, the alternative to massive models for natural language processing

Natural Language Processing (NLP) encloses a wide range of applications which play a critical role in daily business, as automating reviews or developing bots for a web page. Since the publication of BERT, pre-trained language models dominate the area, with a growing trend of increasing the number of parameters to obtain state-of-the-art results and the need of processing huge amounts of data. In spite of overcoming lighter implementations, they require high computational resources and memory requirements,in addition to spend long inference times, constraining real-time situations and scaling. DistilBERT is proposed as an alternative to reduce the size and inference time of massive models maintaining the same performance. It applies distillation over BERT and obtains an architecture 40% smaller. The aim is to compare BERT and DistilBERT in the resolution of two NLP tasks, classification with more than one category and with multiple labels. The obtained results show that DistilBERT was 50% faster in both tasks, reaching the same performance than BERT in multiclass and overcoming it in multilabel classification. DistilBERT presents distillation as an optimal technique to reduce size and computational resources of current NLP state-of-the-art models.

## Notebook
The implementation has been carried out in a notebook with the option to run it from Colab. The file is: 
**inside_distilbert.ipynb**.

## Implemented Models
BERT and DistilBERT models are implemented to solve _Multiclass classification_ and _Multilabel classification_. Their parameters and training arguments are stored in their respective folders to be able to load them for future use, as well as used tokenizers. Mention the saved implementations correspond with the model trained until the specified epoch in the name. For example, _bert-ep3_ corresponds with a bert model trained until epoch 3, since it is the one which performs better respect the 4 trained versions, one per epoch. Everything is inside **models** folder.

## Results
Obtained training and test results in both tasks respect both models are stored in **results** folder.

## Memory
This work is the topic of my Master Thesis. For this reason, the memory is also published with more information and details in case it could be useful to check it. The file is: **memory.pdf**.

## Cite
Thanks for reading! If you find it useful, feel free to use it. You can cite it as:
```
@mastersthesis{bueno2022distilbert,
  author    = {Bueno, Ion},
  title     = {DistilBERT, the alternative to massive models for natural language processing},
  school    = {University Carlos III of Madrid},
  year      = {2022},
  month     = {jun},
  address   = {Madrid, Spain},
  url       = {https://github.com/ion-bueno/distilbert-from-inside}
}
```
