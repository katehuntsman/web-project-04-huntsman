# Requests, JSON, and basic NLP with spaCy

```
This exercise illustrates how to access web-hosted APIs, get back a response in JSONLinks to an external site. format, and extract the information we need from the JSON. Accessing APIs is a key skill for data analysts. We can use web APIs to get stock data, weather data, and much more. We'll use an API to access song lyrics or poems in this exercise. We don't care which API - there are many and they change. The skill skills are being able to (a) make an API request and (b) find the information we need in the returned response. 
```

## Cloning the Base Repo
```
Select the "Use this Template" button on GitHub and specifying yourself as the owner.  The base repository is available at: https://github.com/wmnlp-materials/json-sentimentLinks to an external site.

Clone YOUR new repo down to your machine.
```

## Spacy
```
spaCy is a library for natural language processing.

See: https://spacy.io/Links to an external site.

spaCy 101: https://spacy.io/usage/spacy-101Links to an external site.

installation: https://spacy.io/usageLinks to an external site.

spaCy provides pre-trained pipelines to process text. For example, the "en_core_web_sm" package is a small English pipeline that supports all core capabilities and is trained on web text.
spacytextblob is a pipeline component that enables sentiment analysis using the TextBlobLinks to an external site. library.  See https://spacy.io/universe/project/spacy-textblobLinks to an external site.
```

## Import packages 
```
pip install requests spacy spacytextblob
```