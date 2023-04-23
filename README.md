# Movie Rating Prediction
In this project, I predicted movie ratings using the "movieReplicationSet.csv" dataset which features ratings data of 400 movies from 1097 research participants.

## Dataset Details
The dataset has the following details:

* 1st row: Headers (Movie titles/questions)
* Columns 1-400: These columns contain the ratings for the 400 movies (0 to 4, and missing)
* Columns 401-420: These columns contain self-assessments on sensation seeking behaviors (1-5)
* Columns 421-464: These columns contain responses to personality questions (1-5)
* Columns 465-474: These columns contain self-reported movie experience ratings (1-5)
* Column 475: Gender identity (1 = female, 2 = male, 3 = self-described)
* Column 476: Only child (1 = yes, 0 = no, -1 = no response)
* Column 477: Movies are best enjoyed alone (1 = yes, 0 = no, -1 = no response)
## Tasks Completed


1. Imputing the missing ratings with a blend (50:50) of the arithmetic mean of each column and each row.
2. For each of the 400 movies, using a simple linear regression model to predict the ratings.
3. Using the ratings of the other 399 movies in the dataset to predict the ratings of each movie.
4. For each of the 400 movies, finding the movie that predicts ratings the best.
5. Reporting the average COD (Coefficient of determination) of those 400 simple linear regression models.
6. Histogram of these 400 COD (Coefficient of determination) values and a table with the 10 movies that are most easily predicted from the ratings of a single other movie and the 10 movies that are hardest to predict from the ratings of a single other movie.

## Project Structure
This repository contains the following files:

* movieReplicationSet.csv: the original dataset.
* Movie Rating Prediction.ipynb: a Jupyter notebook where I performed all the data analysis, imputation, and regression models.
* README.md: this file, providing a summary of the project.
## Results
After completing the assigned tasks, I found that the average COD (Coefficient of determination) of the 400 simple linear regression models was X. Additionally, I created a histogram of the COD values and a table of the 10 movies that are most easily and hardest to predict from a single other movie, along with their associated COD values and the best predictor movie rating.

##  Conclusion
Overall, this project provided me with the opportunity to demonstrate my ability to follow detailed and specific instructions while performing data analysis and machine learning tasks.
## License
This project is licensed under the MIT License.
