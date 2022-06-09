# **Simple typing error corrector**

#### *Marcos V. O. Assis (mvoassis@gmail.com)*

***
> ## Objective: 

Generate an algorithm capable of correcting misspelled words.

> ## Language: 

For development and testing, words in Portuguese-BR were used.

> ## Approach:

1. Creation of a dictionary of correct words based on a dataset (Articles from the ALURA.com.br website)
2. Creation of generation of possible words for correction based on the errors considered.
3. Submission of the wrong word for correction
4. Selection of the generated word with the highest probability (frequency) of appearing in the dataset.

> ## Typing errors considered:

* Word with missing letter
* Word with extra letter
* Word with misspelled letter
* Word with swapped letters
* Word with errors in 2 levels

> ## Files

* artigos.txt -> Training dataset
* palavras.txt -> Testing dataset, each line following the format: *(\<correct word\> \<mispelled word\>)*
