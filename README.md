Project Description 

One of my biggest hobbies since I was a kid was collecting sneakers. For my extract, transform and load project I wanted to explore the 1 billion dollar sneaker reselling market. 

Questions that this project can answer: 
What are the prices for various shoe models?
What sizes of a particular shoe is the most profitable?
What are the average price of a shoe depending on its shoe sizes? 

Extract (Pulling data from stockx.com): To start off, I had to pull data from the infamous sneaker reselling platform Stockx.com. I extracted data from the website through postman into multiple Json files. I chose to compare prices for the shoe model Yeezy 700 Vanta vs the Yeezy 700 Static. 

Transform (Data cleaning):  I than imported the json files into panda dataframes. Using python I cleaned the data and selected the columns that I wanted to analyze by renaming and indexing. In addition, I also grouped the prices to calculate their averages and listed them according to their respective sizes. 
Load : Last but not least I loaded the data to my SQL and used queries to display the specific dataframes. 

Conclusion: Sizes 15 and over are the most profitable but they also have the least amount of sales. While common sizes such as 7-13 are generally the least profitable sizes. 


