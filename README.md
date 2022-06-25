# Social Media Analytics
An analysis to identify the degree to which engagement rates on social media posts are attributable to content/non-content characteristics. Full information can be found in the file [AssignmentGuideSocialAnalytics.pdf](AssignmentGuideSocialAnalytics.pdf) within the repo.

A reference on what the LIWC variables refer to can be found in the file [LIWC2015_LanguageManual.pdf](LIWC2015_LanguageManual.pdf) within the repo.

Each codefile is numbered in the sequence they should be executed and commented accordingly. A brief summary of methods used within this problem include:
- Selection of important variables based on intuition 
- 1-hot encoding of categorical variables
- Ranking of features by importance using a Random Forest
- Regression using Neural Networks (Keras)
- K-Means Clustering


## Dataset

A large dataset containing posts from several brands on various social media platforms was used. This dataset includes non-content characteristics such as:
- Date/time of post
- No. of followers of brand at time of post
- Number of likes/comments/shares (or total interactions)

... and content-based features such as:
- General sentiment of post (positive/negative)
- Amount of masculine & feminine words used (% of article)
- Amount of words relating to money/power/fame/sports (% of article)
- Wordcount, average sentence length, use of slang, etc

The entire dataset can be downloaded [here](https://drive.google.com/file/d/1uvkRM1V5rO-EarJE9w8asFXsDJqF7RvM/view?usp=sharing).

<br>

Code contained here is used within the course 'MRKT 671 Advanced Marketing Analytics' of the MMA Program at McGill University.