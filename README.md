# Kaggle-practice pandas solution 
#q1 
import pandas as pd 
fruits = pd.DataFrame({'Apples' : [30], 'Bananas' : [21]})
#q2 
import  pandas as pd
fruit_sales = pd.DataFrame({'Apples' : [35,41] , 'Bananas' : [21,34]}, index = ['2017 Sales ' , '2018 Sales'])
#q3 
import pandas as pd 
ingredients = pd.Series(['4 cups', '1 cup', '2 large','1 can'] , index = ['Flour', 'Milk', 'Eggs', 'Spam'] , name = 'Dinner')
#q4 
reviews = pd.read_csv('../input/wine-reviews/winemag-data_first150k.csv')
#q5 
animals.to_csv("cows_and_goats.csv")
