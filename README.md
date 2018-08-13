## Twitter-Sentiment-Analysis-with-Python---Part-IV

Attached Ipython Notebook the the part4 of twitter sentiment analysis as a part of my current phd project. 

## Comparing machine learning algorithms
Convert text into numerical representaiton (countVectorizer & TfidfVectorizer) and test with 
- unigram with/without stopwords
- bigram with/without stopwords
- trigram with/without stopwords

## TextBlob
TextBlob is a Python library for processing textual data. It provides a simple API for diving into common natural language processing (NLP) tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more.

## vaderSentiment 
VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media, and works well on texts from other domains. Vader implements with the grammatical and syntactical rules described in paper (Gilbert, 2014), incorporating empirically derived quantifications for the impact of each rule on the perceived intensity of sentiment in sentence-level text. 
Vader goes beyond what would normally be captured in a typical bag-of-words model, incorporating word-order sensitive relationships between terms (e.g., intensifers, booster words, or degree adverbs): 
- "The service here is extremely good" (positive sentiment intensity = 0.36)
- "The service here is good" (positive sentiment intensity = 0.293)
- "The service here is marginally good" (positive sentiment intensity = 0.227)

Vader implements includes proper handling of sentences with:
- typical negations (e.g., "not good")
- use of contractions as negations (e.g., "wasn't very good")
- conventional use of punctuation to signal increased sentiment intensity (e.g., "Good!!!")
- conventional use of word-shape to signal emphasis (e.g., using ALL CAPS for words/phrases)
- using degree modifiers to alter sentiment intensity (e.g., intensity boosters such as "very" and intensity dampeners such as "kind of")
- understanding many sentiment-laden slang words (e.g., 'sux')
- understanding many sentiment-laden slang words as modifiers such as 'uber' or 'friggin' or 'kinda'
- understanding many sentiment-laden emoticons such as :) and :D
- translating utf-8 encoded emojis such as 💘 and 💋 and 😁
- understanding sentiment-laden initialisms and acronyms (for example: 'lol')

## LIWC
The Tone variable puts the two dimensions (positive emotion and negative emotion dimensions) into a single summary variable Cohn, Mehl, & Pennebaker, 2004). The algorithm is built so that the higher the number, the more positive the tone. Numbers below 50 suggest a more negative emotional tone.
