# restaurant-data-analysis
RMDS Lab Data science cometition submission - The Himalayas

## Review_analysis.ipynb
This program loads the two datasets ("Q3_competition_detail_dataset.xlsx", "Q3_competition_review_dataset.xlsx"), cleans them up for the Tableau Word Cloud and exports the 
result in a csv file called "Restaurants_review2.csv".

### How to use
* Navigate into the directory containing "Review_analysis.ipynb" as well as the two datasets ("Q3_competition_detail_dataset.xlsx", "Q3_competition_review_dataset.xlsx"),
"positive.txt" and "negative.txt".
open "Review_analysis.ipynb" in an ipython notebook reader and run every cell. This should generate a file named "Restaurants_review2.csv",
which is also present in this repository.

### Dependencies:

* **pandas**
* **seaborn**
* **matplotlib.pyplot**
* **requests, re**
* **nltk**
* **string, itertools**
* **collections.Counter, collections.defaultdict**
* **gensim.corpora.dictionary**
* **gensim.models.tfidfmodel**
* **sklearn**
* **wordcloud**
* **csv**

## population_density_cleanup.ipynb
This program loads "Q3_competition_detail_dataset.xlsx", cleans it up for the Tableau and exports the result in "data.xlsx".

### How to use
* Navigate into the directory containing "population_density_cleanup.ipynb" and the dataset "Q3_competition_detail_dataset.xlsx". 
Open population_density_cleanup.ipynb in an ipython notebook reader and run every cell. This should generate a file named "Restaurants_review2.csv", which is also present in this repository.

### Dependencies:

* **pandas**

## Data Visualizations:
* [Average Index Score For Each Zip Code](https://public.tableau.com/app/profile/irisa2031/viz/RMDSvisualization/Story1)
* [Word Cloud](https://public.tableau.com/app/profile/thuong.nguyen/viz/Wordcloud_Reviews/Sheet1)
* [Covid Density and Restaurant Locations](https://public.tableau.com/app/profile/thuong.nguyen/viz/Covid_and_Restaurants/Sheet2)
* [Population Density and Restaurant Locations](https://public.tableau.com/app/profile/sumin.park/viz/DScompetition_2/Dashboard1?publish=yes)
