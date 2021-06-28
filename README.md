# The Data Frog: Transformers

## TODO 

* tf GPU installation 
* fine-tuning example + look at the model from a keras point of view. embedding


## Notebooks

Each notebook runs on Google Colab (link therein)

* Basic usage of the Huggingface transformers ([notebook](https://colab.research.google.com/github/thedatafrog/transformers/blob/main/basic_huggingface.ipynb)): 
  * Sentiment analysis 
    * in English 
    * in other languages: Dutch, German, French, Spanish, Italian
  * Translation
    * English to French and Vice-Versa 
  * Zero-shot classification in French
  * Summarization in French
  * Named entity recognition in French
* Fine-tuning 


## How to install on your machine 

### Base install 

* python 3.8 environment with jupyter notebooks

```
conda create -n hfnlp python=3.8 jupyter
conda activate hfnlp
```

### Huggingface with pytorch backend

```
pip install transformers[sentencepiece]
```

### Huggingface with Tensorflow backend (CPU)


```
pip install transformers[tf-cpu,sentencepiece]
``` 

### Huggingface with Tensorflow backend (GPU)

TODO



