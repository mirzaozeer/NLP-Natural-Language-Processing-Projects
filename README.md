![an-introduction-to-natural-language-processing-with-python-for-seos-5f3519eeb8368](https://user-images.githubusercontent.com/88277713/154839789-8279cfa9-07c8-4bc3-967d-15a01aa3985f.png)

CONTENT

[0. What is NLP ?](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/README.md#what-is-nlp-)

[1. Grammar-Spell-Punctation-Corrector-ENG Project](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/README.md#1-grammar-spell-punctation-corrector-eng-project)
- [1.1. Grammar Corrector](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/README.md#1-grammar-corrector)
- [1.2. Punctuation Corrector](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/README.md#2-punctuation-corrector)
- [1.3. Spell Checker](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/README.md#3-spell-checker)

[2. Style Former-ENG Project](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/README.md#2-style-former-eng-project)

[3. Spell Checker 2 TR-ENG Project](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/README.md#3-spell-checker-2-tr-eng-project)

[4. Multi Class Text Classification /BERT](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/README.md#4-multi-class-text-classification-bert)

[5. Text Summarization](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/README.md#5-text-classification-summarization)



# What is NLP ?

Natural language processing (NLP) is a subfield of linguistics, computer science, and artificial intelligence concerned with the interactions between computers and human language, in particular how to program computers to process and analyze large amounts of natural language data. The goal is a computer capable of "understanding" the contents of documents, including the contextual nuances of the language within them. The technology can then accurately extract information and insights contained in the documents as well as categorize and organize the documents themselves.

Challenges in natural language processing frequently involve speech recognition, natural language understanding, and natural language generation. 

[For more information](https://en.wikipedia.org/wiki/Natural_language_processing)

# 1. Grammar-Spell-Punctation-Corrector-ENG Project
[Project Code](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/Grammar-Spell-Punctation-Corrector-ENG.ipynb)
### 1.1. Grammar Corrector
![Resim1](https://user-images.githubusercontent.com/88277713/157423923-0f82e214-58fe-43a5-8129-690db1a1e5a2.png)

The term "grammar" can also describe the linguistic behavior of groups of speakers and writers, rather than individuals. Differences in scales are important to this sense of the word: for example, the term "English grammar" could refer to the whole of English grammar (that is, to the grammars of all the speakers of the language), in which case the term encompasses a great deal of variation.[3] At a smaller scale, it may refer only to what is shared among the grammars of all or most English speakers (such as subject–verb–object word order in simple declarative sentences). At the smallest scale, this sense of "grammar" can describe the conventions of just one relatively well-defined form of English (such as standard English for a region).  
[For more information](https://en.wikipedia.org/wiki/Grammar)

### 1.2. Punctuation Corrector
![Resim2](https://user-images.githubusercontent.com/88277713/157428502-31515562-6aac-4f67-8c9f-ca8246ff22ff.png)

Punctuation (or sometimes interpunction) is the use of spacing, conventional signs (called punctuation marks), and certain typographical devices as aids to the understanding and correct reading of written text, whether read silently or aloud.

### 1.3. Spell Checker
![Resim3](https://user-images.githubusercontent.com/88277713/157428683-283ae4d9-274e-42fb-88f2-48ee73976496.png)

# 2. Style Former-ENG Project
[Project Code](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/SpellingChecker2TR-ENG.ipynb)
![Resim1](https://user-images.githubusercontent.com/88277713/157613386-27f70154-885f-419f-b156-8e1f42598f65.png)
![Resim5](https://user-images.githubusercontent.com/88277713/157429769-7c292096-6ea1-4824-9fe6-51f949dbf781.png)

# 3. Spell Checker 2 TR-ENG Project

A different method  tried for word prediction.
Data with English words taken from Github [https://github.com/dwyl/english-words]
In order to divide the words into letters and make predictions according to possible wrong word errors, each letter of the words was replaced with other letters in the alphabet, and the model's prediction capacity was tried to be increased.
The good thing about the  model is that it offers options and there is a chance to choose the right word.


[Project Code](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/SpellingChecker2TR-ENG.ipynb)

![Resim6](https://user-images.githubusercontent.com/88277713/157430058-688feb4a-78ff-4c16-8ce8-39b27e46d3bc.png)

# 4. Multi Class Text Classification /BERT
[Project Code](https://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/MultiClassTextClassificationENG-BERT%20.ipynb)

![bert-chart](https://user-images.githubusercontent.com/88277713/161452903-c56bd7e1-0e8a-4822-9c16-9012031a66cd.png)

In this study, I used the BERT algorithm produced by Google to detect sentiment analysis in the text. BERT uses a masked language model, trying to understand the relationships between each word used in the texts. In this way, I present to you a multi-classified sentiment analysis project that predicts whether each sentence in a text is positive or negative.

<img width="852" alt="Ekran Alıntısı" src="https://user-images.githubusercontent.com/88277713/161452934-0a167c24-52fd-469e-8ca6-e1965c65f3e2.PNG">

In the example above, the sentences of a text(it is a letter), which is the input, were parsed and the sentiment analysis of each sentence was made, and then the general sentiment analysis of the text was estimated.

# 5. Text Summarization

[Project Code](hhttps://github.com/Dodger22/NLP-Natural-Language-Processing-/blob/main/TextSummarizationENG%26TR.ipynb)

<img width="837" alt="wewe" src="https://user-images.githubusercontent.com/88277713/161452986-7a13b0ac-4d84-4947-a3ca-e72685b323b5.PNG">

In this study,  trying to summarize a long text.


1- Remove auxiliary words from the input text.

2– Remove punctuation marks,.

3– Label words according to their frequency.

4– Find the distribution ratios of the words.

5– Separate the text according to its sentences and do the same for sentences.

6– Determine the length of our summary text

7- Finally, create our summary text according to their frequency.

Example of labeled words;

<img width="835" alt="ooo" src="https://user-images.githubusercontent.com/88277713/161453005-ab516f1f-e941-4227-bc5e-746ff1f2a96d.PNG">






