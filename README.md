# given string
Quote= ("Learning  is never done without error, and defeat ")
words =Quote.split()
# Reversed the list of words
reversed_words = words[::-1]
# join the reversed list of words back into Quote
reversed_Quote = ' '.join(reversed_words)
print (reversed_Quote )
