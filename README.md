# Cyber-Bullying-tweet-analysis
This is a project that I have made with my classmates for our second semester project in my Msc.

This project contains a data set of 470000+ tweets that have been classified on the basis of six types of cyber bullying.
The classifications are:
- religion based
- gender based
- age based
- ethnicity
- other types of cyber bullying
- not cyber bullying

The steps followed in the project are:

1. We did a initial data analysis on the data set. 
2. We were able to conclude that the data set roughly contained the same number of samples for each types before the step of preprocessing.
    Th samples for each types before preprocessing.
      religion               7998
      age                    7992
      gender                 7973
      ethnicity              7961
      not_cyberbullying      7945
      other_cyberbullying    7823  
3.Since the data set consisted of tweets we there were a lot of unecessary character like emojis, special character and others, these needed to be removed in     the step pf preprocessing so that we get clean data that can be later used to machine learning part.

4.Later after the tweets have been cleaned we used viualization techniques to visualize the data based on the tweets
5.Machine learning algorithms were used to make a model that correctly predicted the tweets. We tried several different algorithms and we finalised on the SVM     which gave us the highest accuracy.



