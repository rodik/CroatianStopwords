English
-------

This is a collection of Croatian Stopwords. There are 4 versions of
Stopwords:

1.  **cro\_sw\_min\_d** - minimal set of words with diacritics included
2.  **cro\_sw\_min** - same set but diacritics converted to their basic
    form (*hoćeš* -&gt; *hoces*)
3.  **cro\_sw\_full\_d** - expanded set of words with diacritics
    included
4.  **cro\_sw\_full** - expanded set without diacritics

People often chose not to write diacritics, especially on social
networks, so a set of stopwords without them is needed to perform
matching. This also means that some words change their meaning i.e.
*što* becomes *sto*, which is the Croatian word for "one hundred". Keep
that in mind.

The minimal set was taken from an existing
[repository](https://github.com/6/stopwords-json/blob/master/dist/hr.json).

The full set was created by filtering terms with high frequences. Term
frequency database - (Ljubešić, Klubička, and Boras 2016).

Croatian
--------

TODO

References
==========

Ljubešić, Nikola, Filip Klubička, and Damir Boras. 2016. “Inflectional
Lexicon hrLex 1.2.” <http://hdl.handle.net/11356/1072>.
