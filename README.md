# sklearn-tfidf-sort-words

Tf-idf is a renowned NLP technique for vectorizing documents. I decided to investigate it a bit deeper to see how it works and what it can and cannot do (what kind of tasks it should be used for).  
&nbsp;  
In this notebook, I do mainly two things :  
1 - compare a bag-of-word vectorization vs a tf-idf vectorization on a text classification task with the 20newsgroups dataset  
2 - I build code to get the most and least important words in a document according to the tf-idf weights  
&nbsp;  
This project has been very instructive, particularly the second part during which I learned a lot on numpy arrays and how you can index on them (with nonzero() and argsort function() ). I also learned tf-idf is especially good for text classification (or information retrieval).  
