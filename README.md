### About

Python utility that compares two texts together using following techniques:

* (a) simple comparison from ```difflib``` library;
* (b) cosine between vector of words from text;

### Usage

Create two ```txt``` files with text inside and name them as follows ```text-a.txt``` and ```text-b.txt```.
Navigate to teh 'textcomparator' folder and run the ```textcomparator.py``` python script:
```
python textcomparator.py
```

### Materials

* [How to calculate cosine similarity given 2 sentence strings?](http://stackoverflow.com/questions/15173225/how-to-calculate-cosine-similarity-given-2-sentence-strings-python)
* [Python: tf-idf-cosine: to find document similarity](http://stackoverflow.com/questions/12118720/python-tf-idf-cosine-to-find-document-similarity/18914884#18914884)
* Collection of the stop words in 29 languages can be found [here](https://code.google.com/p/stop-words/)

### Dependencies

* Python 2.7

### TO-DO

* [ ] Check the sklearn functionality
* [ ] Try [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) python package more about the package can be sees in the article [FuzzyWuzzy: Fuzzy String Matching in Python](http://chairnerd.seatgeek.com/fuzzywuzzy-fuzzy-string-matching-in-python/)
