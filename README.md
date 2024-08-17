# fine-tuning-a-pretrained-model Bert(uncased)


Model description
BERT is a transformers model pretrained on a large corpus of English data in a self-supervised fashion.
This means it was pretrained on the raw texts only, with no humans labeling them in any way (which is why it can use lots of publicly available data)
with an automatic process to generate inputs and labels from those texts. More precisely, it was pretrained with two objectives:
-- Masked language modeling (MLM)
-- Next sentence prediction (NSP)


Dataset description
GLUE, the General Language Understanding Evaluation benchmark (https://gluebenchmark.com/) is a collection of resources for training, evaluating, and analyzing natural language understanding systems.

sst2
The Stanford Sentiment Treebank consists of sentences from movie reviews and human annotations of their sentiment. The task is to predict the sentiment of a given sentence.
It uses the two-way (positive/negative) class split, with only sentence-level labels.
