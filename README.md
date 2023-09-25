# Language-Detection-using-NLP

Problem Statement: Identification of the languages based on the given text using NLP and  Deep Learning Techniques.

Abstract: With the growing volume of multilingual data on the web, language detection has become a crucial task in various NLP applications, such as machine translation and sentiment analysis. However, for the case of language detection, the previous works predominantly use machine learning models and very few variations in text vectorization. In our project, we intend to explore the use of deep learning for the classification of languages and the affect of different text-vectorization methods. The dataset was taken as a mixture of 4 different datasets, to facilitate better training procedures. We also conduct experiments to evaluate the impact of different parameters on the performance of the models. Our results demonstrate the effectiveness of deep learning techniques for language detection in NLP, and provide insights into the performance of various deep learning models and text vectorizers for this task.

DataSet:  The datasets we intend to use for implementation are from Kaggle, and each has a text and language column. For our project, we are combining four different datasets that helps our model to predict more unique world languages. The links from where the datasets were taken are 
1.	https://www.kaggle.com/datasets/basilb2s/language-detection
2.	https://www.kaggle.com/code/martinkk5575/language-detection/data 
3.	https://www.kaggle.com/datasets/lailaboullous/language-detection-dataset
4.	https://www.kaggle.com/datasets/chazzer/big-language-detection-dataset?select=sentences.csv

Introduction: Identification of a language typical refers to a method that aims to classify text into a preset set of accessible languages in a language. It is critical in many NLP applications to be able to accurately identify the language in which the current input is written. This capability, for example, is required to load the appropriate autocorrection lexicon and language model for predictive and multilingual typing, machine translation, information retrieval, summarization, and question answering, etc., language identification is a vast study topic. Before processing, they must first identify the language. There are two ways to identify languages: computational and non-computational. Non-computational approaches necessitate that authors have sufficient linguistic expertise to recognize diacritics, symbols, the most frequently used character combinations, and other elements.Statistical methods, as opposed to linguistic understanding, are used in computational ways to handle similar challenges, An essential NLP approach, especially when working with text that rely on classification and language. The goal of this paper is to use the larger datasets which contains more unique languages, and able to make a classification model using custom neural network, and compare the results with the existing ones, by using different text-vectorization methods.


Why is it Important:
1.	In this busy world, language is so important to communicate to other persons, inorder to communicate or respond back, we should be able to identify the language. This is where the language identification plays a major role.
2.	Language detection is also quite popular in the industry as most of the companies do sentiment analysis for the reviews given by the customers from the different countries. Inorder to perform the ML tasks, some preprocessing is needed, where the language identification is one of it. 
3.	In social media, where the whole world is connected i.e. different uniques languages speaking persons exists, they keep commenting in different languages, in order to understand them we need a language identifier. 
4.	This made us motive to choose this topic as our project. 


Methodology: In this work, we are using a dataset which contains features from multiple languages like English, French, German, Spanish etc. The details of how we arrived at the dataset was mentioned above. 

1.	Text Preprocessing: 
a.	We will process the text data by removing special character, punctuation, and stopwords. 
b.	We will later apply lemmatization to the text data, which will help in reducing the dimensionality of feature space. 	

2.	Text Vectorization: 
a.	In this work, we experiment with various text vectorization techniques to represent the text data as numerical features that can be used as input to our deep learning models.
b.	We wish to experiment with various vectorization techniques, including bag-of-words, Tf-Idf, and word embedding, some pretrained models like BERT.
c.	We want to note how each of the technique affects the overall accuracy. 

3.	Classification Task: 
a.	We intend to use Nueral Networks with different variations in them in order to achieve better accuracy. 
b.	The NNs will be implemented with different variations in layers such as LSTM, RNNs, Dense layers with loss function as cross entropy and optimizer as adam.
c.	We will train our models on multiple number of epochs with different learning rates. 

4.	Testing:
a.	On inputting the text from the user to our model, we start with preprocessing the text followed by the text-vectorization, then we use our trained model to predict the language.

References:
[1] Sarma, N., Singh, S.R., & Goswami, D. (2018). Word Level Language Identification in Assamese-Bengali-Hindi-English Code-Mixed Social Media Text. 2018 International Conference on Asian Language Processing (IALP), 261-266.
[2]W. B. Canvar and J. M. Trenkle. N-gram based Text Categorization. Proceedings of Symposium on Document Analysis and Information Retrieval, University of Nevada, Las Vegas, pp. 161-176, 1994.
[3]B. Ahmed, S.-H. Cha, and C. Tappert. Language Identification from Text Using N-gram Based Cumulative Frequency Addition. Proceedings of Student/Faculty Research Day, CSIS, Pace University, 2004.
[4]Pujeri*, B. P., & Sai D, J. (2020). An anatomization of language detection and translation using NLP techniques. International Journal of Innovative Technology and Exploring Engineering, 10(2), 69–77. https://doi.org/10.35940/ijitee.b8265.1210220. 
[5]Khurana, D., Koli, A., Khatter, K., & Singh, S. (2022). Natural language processing: State of the art, current trends and challenges. Multimedia Tools and Applications, 82(3), 3713–3744. https://doi.org/10.1007/s11042-022-13428-4.
[6] https://www.kaggle.com/datasets/basilb2s/language-detection
[7]https://towardsdatascience.com/how-to-detect-and-translate-languages-for-nlp-project-dfd52af0c3b5
[8] https://www.kaggle.com/datasets/basilb2s/language-detection

