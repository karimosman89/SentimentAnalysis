# SentimentAnalysis

 This dataset was created for the Paper 'From Group to Individual Labels using Deep Features', by Kotzias et. al, KDD 2015
Please cite the paper if you want to use it :)

It contains sentences labeled with positive or negative sentiment, extracted from reviews of products, movies, and restaurants

=======
Format:
=======
sentence \t score \n


=======
Details:
=======
The score is either 1 (for positive) or 0 (for negative)	
The sentences come from three different websites/fields:

imdb.com
amazon.com
yelp.com

For each website, there exist 500 positive and 500 negative sentences. Those were selected randomly for larger datasets of reviews. 
We attempted to select sentences that have a positive or negative connotation, the goal was for no neutral sentences to be selected.



For the full datasets look:

IMDb: Maas et. al., 2011 'Learning word vectors for sentiment analysis'
Amazon: McAuley et. al., 2013 'Hidden factors and hidden topics: Understanding rating dimensions with review text'
yelp: Yelp dataset challenge http://www.yelp.com/dataset_challenge

