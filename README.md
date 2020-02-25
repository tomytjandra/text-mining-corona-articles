# TEXT MINING FOR INDONESIAN ONLINE NEWS ARTICLES ABOUT CORONA

<img align="right" width="50%" src="https://github.com/tomytjandra/text-mining-corona-articles/blob/master/results/wordcloud.png" style="margin-right:10%">

Hi! In the notebook, we will start our text mining journey by scraping a list of news articles from [tirto.id](https://www.tirto.id) and [detik.com](https://www.detik.com) about the Coronavirus using `BeautifulSoup` package. The contents will be saved to an individual .tsv (tab seperated value) files, which will be loaded again for further analysis. From there, we analyze the posting pattern for each sites and train a `Word2Vec` model using `gensim` package in order to analyze the semantic and syntactic similarity between each preprocessed words.

## REFERENCES
### Article Contents
* https://www.tirto.id
* https://www.detik.com

### About Word2Vec
* https://towardsdatascience.com/introduction-to-word-embedding-and-word2vec-652d0c2060fa
* https://radimrehurek.com/gensim/models/word2vec.html

### Stopwords List
* https://github.com/har07/PySastrawi
* https://github.com/pebbie/pebahasa/blob/master/indonesian
* https://github.com/aliakbars/bilp/blob/master/stoplist
* http://web.archive.org/web/20120608052057/http://fpmipa.upi.edu/staff/yudi/stop_words_list.txt
