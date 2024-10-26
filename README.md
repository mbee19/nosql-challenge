# nosql-challenge
Module 12 Challenge for Morgan Bee

In this challenge, I used all class activities from Module 12 and Khaled's detailed class notes in his .ipynb notebook to practice and help me through the challenge. 

I also used this stack overflow article: https://stackoverflow.com/questions/64307420/how-to-take-the-value-of-a-key-in-mongodb-using-python?rq=3 to help me identify the latitude and longitude in the results for Part 3 of this challenge (these lines of code): 
```
# Calculate latitude and longitude to use in query
latitude = establishments.find_one({'BusinessName' : 'Penang Flavours'})['geocode']['latitude']
longitude = establishments.find_one({'BusinessName' : 'Penang Flavours'})['geocode']['longitude']
```

Note that in Part 3 for questions 1-3, there was no specification for the fields to display in the DataFrames. Therefore, I displayed all of the information from each query into its respective DataFrame. 