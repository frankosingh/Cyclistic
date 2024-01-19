Hi this is my capstone project from Google Analytics Project which is about analysing annual data of the company to figure out what is the difference between a member and a casual person.

The database is publically available and was part of the course. Otherwise you can find it on Kaggle as "Cyclistic Data".

Started with Cleaning the data up and organising the data in excel and then imported all the data into R where I combined all of the data into a single dataset.

After combining it into a single dataset I immediately checked whether everything was in order.

Then used key statistical formulae as below

Results of Statistics applied:
    
    Mean (18.97121): On average, the duration of a ride is approximately 19 minutes. 

    Median (12.03333): Half of the rides are shorter than 12 minutes, and half are longer. Since the median is lower than the mean, it indicates that there are some longer rides skewing the mean upwards. 
    
    Min (1.016667): The shortest ride lasted just over 1 minute. 
    
    Max (1424.7): The longest ride lasted approximately 1425 minutes, or nearly 24 hours. 
    
    Q1 (6.916667): 25% of the rides are shorter than approximately 7 minutes. 
    
    Q3 (21.68333): 75% of the rides are shorter than approximately 22 minutes. 
    
    IQR (14.76667): The middle 50% of rides have durations that range from about 7 minutes to 22 minutes, a spread of approximately 15 minutes. 
    
    Std_Dev (26.17043): The standard deviation, a measure of the spread of the data, is approximately 26.17 minutes. This indicates a relatively wide spread around the mean. 
    
    Variance (684.8912): The variance, another measure of spread, is the square of the standard deviation. It's useful for statistical tests and in contexts where you might need the squared term. 
    
    Range (1423.683): The range of ride durations is from just over 1 minute to nearly 24 hours. 
    
    Skewness (9.199857): A positive skewness indicates that the distribution of ride durations is skewed to the right. This is consistent with the fact that the mean is greater than the median. The data has a long tail on the right side, with a few exceptionally long rides. 
    
    Kurtosis (197.2369): Kurtosis is a measure of the "tailedness" of the distribution. A high kurtosis value indicates a distribution with heavy tails and a sharp peak, meaning there are more extreme values than would be found in a normal distribution. 

    
  From these statistics, it's evident that while most rides are relatively short (with 50% being under 12 minutes), there are some exceptionally long rides, with the longest being almost a full day.
This was the overall analysis of the data.


The second part of the analysis that i did was by grouping the type of customers. The casuals and members and figuring out some statistics.


    
