# FE595_Assignment3

Assumptions - 

	Imports are csv files with two columns named "Name" and "Purpose"
	
	Need to manually import your files and merge them (just like in Sentiment_Sorter with given example)
	
Purpose of each file - 

	split_name_and_purpose : Separates name and purpose into two different lists
				split_data(self)
	
	best_and_worst : Using sentiment analysis, finds the best and worst business ideas from the given purposes
				best_and_worst(self)
	
	most_common : Finds the 10 most common words from the given purposes
				most_common(self, remove_stopwords=True)

	Sentiment_Sorter : combines all three of these functions with the example of provided data in "Files" folder
