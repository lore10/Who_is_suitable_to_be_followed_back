# Who_is_suitable_to_be_followed_back
Dataset used in the project "Who is suitable to be followed back when you are a Twitter interested in Politics?" 
Conference dg.o 2017.

Twitter users might be characterized as highly politically active or poorly politically active citizens, 
according to their Twitter activity. Identifying the level of interest in politics of a user would be relevant 
to provide them with meaningful recommendations such as political actors to follow, tweets talking about politics, 
and political-oriented lists, among others. However, due to the information overload and the wide range of topics 
posted on Twitter, generating personalized political-related suggestions becomes a problem. 

The Datasets contain json and txt files obtained by querying Twitter. The data corresponds to 
information generated during during November 2016 in Ecuador, the users who posted tweets at that time, their timelines' tweets and some political actors tweets were alse crawled. In detail, the files are:


1. Training_Dataset.txt
Contains the (preprocessed) tweets used to train the model word2vec.

2. political_actors.txt:
List of political actors used to validate the accuracy of the model.

3. 5_Clusters.txt
Contains a list of the 5 clusters found in the training model (Cluster 2 is related to POLITICS)

4. Sample_of_Users_and_their_Friends.json
List of the users and their friends who were used in our experimental framework and DOIPs correlation.
[
[u1, [fr1_u1, fr2_u1, fr3_u1, ... ]],
[u2, [fr1_u2, fr2_u2, fr3_u2, ... ]],
[u3, [fr1_u3, fr2_u3, fr3_u3, ... ]], ...
]

