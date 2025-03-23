# nlp_ex3
Exercise 3 for the UPF's NLP class of 2025<br>
Author: Laia Marsó

**CODE**

**Exercise3_AnalysisOfWordUse.ipynb** contains the script in Jupyter Notebook format. It tries to identify contexts of use of social media terms.

**DATA**

**SocialMediaTerms.txt** is a datafile that contains the stems of the keywords we want to analyse


**REQUIREMENTS**

This is a list of modules needed in order to correctly execute this project<br>
**- pandas** and the following dependencies to load a parquet dataset from HuggingFace: *pyarrow, fastparquet and huggingface_hub*<br>
**- spacy** and download the Catalan language model *ca_core_news_md*

System libraries:<br>
re: regular expressions module<br>
collections: for the Counter function
