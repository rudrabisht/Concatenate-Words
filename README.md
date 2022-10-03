# Concatenate-Words
If the input size of the list is N and the average of the word length is M.
To solve we have two dp approaches:
1.For each position in a word, we loop through all the words in the List and update the dp arrays. BigO: N * M * N
2.For each word, we loop through all the possible sub strings to find a match in the List and update the dp arrays. BigO: N * M * M
For this one, since N is bigger than M, so we use the 2nd approach.
