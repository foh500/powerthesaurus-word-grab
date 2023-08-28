# powerthesaurus-word-grab
grabs words from new searches on powerthesaurus, sends sentiment analysis results via OSC

https://github.com/foh500/powerthesaurus-word-grab/blob/main/power%20thesaurus%20text%20grab.ipynb

Uses textblob, selenium, pythonosc
Also uses the NLTK movie reviews database to return sentiment

Three floats sent via OSC:
1. positive sentiment percentage
2. negative sentiment percentage
3. word length

This can be used to control outputs via Wekinator, such as audio parameters
