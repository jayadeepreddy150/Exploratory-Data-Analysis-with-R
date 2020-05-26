# Exploratory-Data-Analysis-with-R
# vegas dataset
1. Explore the overall structure of the dataset using str().
2. Use summary to get a summary statistics of each variable. Does any of the variables have missing values?
3. Draw a histogram of the score variable. Describe what you see in the histogram.
4. Find the mode of “Score”.
5. Use the “quantile” function to get the quantiles for score. What is the median of score?
6. Use the ifelse function (You can get help on the syntax of this function in R by typing ?ifelse) to create a factor variable “sentiment” which takes the value “positive” if score is 4 or 5 and “negative” otherwise. You can use the method “factor” to create a factor from a character vector.
7. Take a summary of “sentiment” to make sure that the frequencies of “positive” and “negative” categories are consistent with the frequency of the values in Score (e.g., the frequency for the “positive” sentiment should be equal to the combined frequency of 4 and 5 for the Score).
8. Use chisquare test to determine if sentiment is associated with any of the variables: "Pool", "Gym","Free.Internet", "Period.of.Stay", "traverler.type"", and "hotel.stars" (Assume the significance level alpha=0.01). Which of these variables are associated with sentiment?
