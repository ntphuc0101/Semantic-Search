# Semantic-Search-
Semantic Search - Natural Language Processing

### Using the info set from: https://u.cs.biu.ac.il/~koppel/BlogCorpus.htm you shall build an enquiry and ranking system for taking a question as input and retrieving all the blogs that contain the terms and also are ranked.

### The query are provided as an English query joined does on google search.

### The query could contain sentence/keyword/phrases query.

### The queries may not contain the precise words as presented within the blogs, so please make sure that relevant words and similar word matches are taken into consideration.

There are several steps in this project.
1. Data Cleaning and Pre-processing.
2. Using BERT to embedded paragraphs of papers using bert-base-nli-mean-tokens pretrained model.
3. Find the closest 5 sentences of the corpus for every query sentence supported cosine similarity.

