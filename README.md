# web scrapping in NLP
Data cleaning is a time consuming and unenjoyable task, yet it's a very important one. Keep in mind, "garbage in, garbage out".

Feeding dirty data into a model will give us results that are meaningless.
Objective:
Getting the data
Cleaning the data
Organizing the data - organize the cleaned data into a way that is easy to input into other algorithms
Output :
cleaned and organized data in two standard text formats:
Corpus - a collection of text
Document-Term Matrix - word counts in matrix format


Getting The Data
You can get the transcripts of some comedian from Scraps From The Loft.

You can take help of IMDB and select only 10 or 20 comedian having highest rating.

Cleaning The Data
When dealing with numerical data, data cleaning often involves removing null values and duplicate data, dealing with outliers, etc. With text data, there are some common data cleaning techniques, which are also known as text pre-processing techniques.

With text data, this cleaning process can go on forever. There's always an exception to every cleaning step. So, we're going to follow the MVP (minimum viable product) approach - start simple and iterate.

Perform the following data cleaning on transcripts: i) Make text all lower case ii) Remove punctuation iii) Remove numerical values iv) Remove common non-sensical text (/n) v) Tokenize text vi) Remove stop words
