# Beer_EDA

1. for beer/name - More the review count means more popular beer it is, count of bear can be worked as feature inplace of 
2. for beer/style - More the style count means more popular style it is, count can be worked as feature
3. for review.text i used nltk.vador which gives sentiment of sentennces percentage value of neutal, neagative, positive, compound

4. I used to struct_dict_time to create more feature  like min date time etc

5. i dropped col which have more than 60 percent data

6. i used stratified distribution of data so that class imbalance problem won't come it make model worse

7. i dropped duplicate data based on user profile

8. First i used 'review/appearance','review/aroma', 'review/palate' in features than i dropped them but the accuracy did not get increased

9. Wr can use it as multilabel Classification also 
