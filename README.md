# Slovenian Lemmatizer for Python
[![Build Status](https://travis-ci.org/izacus/SlovenianLemmatizer-Python.svg?branch=master)](https://travis-ci.org/izacus/SlovenianLemmatizer-Python)

LemmaGen lemmatizer for Python supporing Slovene, Serbian, Romanian, Estonian, Bulgarian and other languages

## Usage

### Installation

You can install it from PyPi:

```bash
pip install Lemmagen
```

### Lemmatization

```python
import lemmagen.lemmatizer
from lemmagen.lemmatizer import Lemmatizer

lemmatizer = Lemmatizer(dictionary=lemmagen.DICTIONARY_SLOVENE)
print(lemmatizer.lemmatize("hodimo"))
```
