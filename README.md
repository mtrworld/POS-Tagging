Problem Statement

The vanilla Viterbi algorithm has low accuracy because it cannot handle the unknown words (words that are not present in the tagged test set). For such unknown words the emission probability is zero and thats why the algorithm choses the first tag available and assigns it to the word. This is very crude method to aasign tags to unknown words.

In this assignment we will modify the Viterbi Algorithm to handle the unknown words so that the algorithm doesnt assign the tag randomly and uses some features of words like morphology, frequency or probability of occurrence to assign the correct tag to the unknown words encountered thereby increasing the accuracy of POS tagging.
