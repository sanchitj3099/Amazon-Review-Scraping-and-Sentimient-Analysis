# Amazon-Review-Scraping-and-Sentimient-Analysis

### Review Scraping Using BeautifulSoup
The project starts with the data collection for sentiment analysis. To get the required data, the process of review scraping from amazon using the BeautifulSoup library is done. BeautifulSoup is a very useful library as it helps in pulling out data of HTML and XML files, and hence one of the most widely used tools for web scraping. The project uses Beautiful Soup 4. Beautiful Soup really helps me as a programmer save a lot of hours of manual scraping.

### Why Iphone 11 Dataset?
The main reason for scraping Iphone 11 reivews is that, the amount of reviews available were high, as well as the reviews tend to be from all over the world. Making the dataset more varied than any other available. And the high amount of reviews will allow me to create a larger dataset, making the analysis better.

### Data Cleaning for Sentiment Analysis
Step 1: Standardizing the data, removing spaces, punctuations and making all the letters lowercase.
Step 2: Removing all the special characters.
Step 3: Removing all the digits and stopwords.
Step 4: Lemmatizing the data - refers to doing things properly with the use of a vocabulary and morphological analysis of words, normally aiming to remove inflectional endings only and to return the base or dictionary form of a word, which is known as the lemma.
Step 5: Tokenizing the data -  process of tokenizing or splitting a string, text into a list of tokens. One can think of token as parts like a word is a token in a sentence, and a sentence is a token in a paragraph. This makes the data ready for analysis.

### Use of LSTM for Analysis
LSTM is an updated version of Recurrent Neural Network to overcome the vanishing gradient problem. It has a memory cell at the top which helps to carry the information from a particular time instance to the next time instance in an efficient manner. So, it can able to remember a lot of information from previous states when compared to RNN and overcomes the vanishing gradient problem. Information might be added or removed from the memory cell with the help of valves. LSTM network is fed by input data from the current time instance and output of hidden layer from the previous time instance. These two data passes through various activation functions and valves in the network before reaching the output.
