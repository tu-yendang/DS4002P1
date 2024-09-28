# DS4002P1
Data Science Capstone Project 1 - The Keith Lee Effect

## Section 1: Software and Platform
* The primary software used for this project was Python, specifically using Interactive Python Notebook files (ipynb). These files were created and used with Google Colab. Additionally, data was read in as CSV files.
* The packages used were pandas to read the CSV files as dataframes, nltk to access the VADER Sentiment Analysis tool, and matplotlib's pyplot to create graphs and figures.
* Three laptops were used, where two devices used Mac, while one was conducted on Windows.

The type(s) of software you used for the project.
## Section 2: Documentation Map
Section 2: A Map of your documentation. In this section, you should provide an outline or tree illustrating the hierarchy of folders and subfolders contained in your Project Folder, and listing the files stored in each folder or subfolder.

This Project Folder contains three folder. Those folders are DATA, OUTPUT, and SCRIPTS.

In the Data folder, there are two subfolders: datasets and final data analyzed. Datasets contain 6 subfolders for the data found of the 6 restaurants that we collected data for. These folders are Calabash African Kitchen, Frankensons, Jamaican Jerk Biz, Joe's Pizza, Popping Yolk, and Thick and Thin. Each of these folders contain two csv files. One csv file is the date and written text of Yelp reviews before Keith Lee made a review for that restaurant and the second csv file is the date and written text of Yelp reviews after Keith Lee made a review for that restaurant. The csv files in datasets were used to create the csv files in final data analyzed. Final data analyzed also contains 6 subfolders: Calabash African Kitchen, Frankensons, Jamaican Jerk Biz, Joe's Pizza, Popping Yolk, and Thick and Thin Treat Bar. Each folder has two csv files. Each folder is identical to the folders in datasets, except each csv file now has an additional column that contains the sentiment analysis score of the written text of the review. 

Outputs contain one subfolder called Pie Charts. This folder contains 6 sub folders: Calabash African Kitchen, Frankensons, Jamaican Jerk Biz, Joe's Pizza, Popping Yolk, and Thick and Thin. Each folder contains two images of pie charts. One pie chart is the ratio of positive and negative reviews left on Yelp before Keith Lee left a review for that restaurant and the other is the  ratio of positive and negative reviews left on Yelp after Keith Lee left a review for that restaurant.

Scripts contain one subfolder called SentimentAnalysis. This folder contain 6 .ipynb files: CalabashAfricanKitchen.ipynb, Frankensons.ipynb, JamaicanJerkBiz.ipynb, JoesPizza.ipynb, PoppingYolk, and ThicknThin.ipynb. These all contain the code that was used to calculate the sentiment analysis scores of all the Yelp reviews left for the restaurant and added those values to the original dataset.

## Section 3: Reproducing Results Instructions
 Instructions for reproducing your results. In this section, you should give explicit step-by-step instructions to reproduce the Results of your study. These instructions should be written in straightforward plain English, but they must be concise, but detailed and precise enough, to make it possible for an interested user to reproduce your results without much difficulty. N.B. This section will be crucial for the CS1 assignment, where you'll be required to reproduce the results of other groups. Therefore, make sure to explain this section thoroughly.

 ## References: (these can also be found directly in code where used)
[1] L. Geetha, “Vader: A Comprehensive Guide to Sentiment Analysis in Python,” Medium, Feb. 28, 2023. https://medium.com/@rslavanyageetha/vader-a-comprehensive-guide-to-sentiment-analysis-in-python-c4f1868b0d2e

[2] “Adding new column to existing DataFrame in Pandas,” GeeksforGeeks, Dec. 11, 2018. https://www.geeksforgeeks.org/adding-new-column-to-existing-dataframe-in-pandas/
‌
[3]“Dataframe to CSV – How to Save Pandas Dataframes by Exporting,” freeCodeCamp.org, Mar. 24, 2023. https://www.freecodecamp.org/news/dataframe-to-csv-how-to-save-pandas-dataframes-by-exporting/#:~:text=to_csv()%20Method-
‌
[4]“python - Extracting specific selected columns to new DataFrame as a copy,” Stack Overflow. https://stackoverflow.com/questions/34682828/extracting-specific-selected-columns-to-new-dataframe-as-a-copy

[5]“Basic pie chart — Matplotlib 3.3.4 documentation,” matplotlib.org. https://matplotlib.org/stable/gallery/pie_and_polar_charts/pie_features.html
‌
