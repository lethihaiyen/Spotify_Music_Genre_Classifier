# Spotify_Music_Genre_Classifier

This capstone project is based on the audio features of Spotify’s song released in
the Spotify API. In this project, I used features of 50K randomly picked songs to
predict the genre that the song belongs to.

- In this project, I perform a visual analysis of the data, perform EDA and visualize
data distribution; through plotting bar graphs of each feature in our data. After
that, I start to process and clean our data, through handling missing values,
outliers, dropping identification data and process categorical variables.

- I then split my data into a train and test set; with the instructions given. Here, the
train set size is 45000; and the test set size is 5000 with an equal distribution of
music genres in each set.

- After this, I performed feature engineering by applying dimension reduction
analysis on our model and then used the reduced data for Classification Models.
For our dimension reduction, I used PCA. And for our Classification Models, I
will be using Random Forest Classifier and Logistic Regression; then evaluate
the two models using AUC score and along with accuracy score.

- My model can be revised to produce better results. I acknowledge that using t-SNE instead of dimension reduction might increase the accuracy of my model. 
