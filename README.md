# Text-Reconstruction

## Word segmentation and vowel insertion


### Word Segmentation:
Word segmentation often comes up when processing many non-English languages, in which words might not be flanked by spaces on either end, such as written Chinese or long compound German words.
The goal of Word Segmentation part is to insert spaces into the input string (of alphabetical characters [a-z]) such that the result is most fluent according to the language model.


### Vowel Insertion
Vowel insertion is relevant for languages like Arabic or Hebrew, where modern script eschews notations for vowel sounds and the human reader infers them from context.
The goal of Vowel Insertion is to insert vowels back into segmented words in a way that maximizes sentence fluency (i.e., minimizes sentence cost). 
A bigram cost function is used. 
