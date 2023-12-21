# NLP Poetry Generator
This poetry generator is the second project that I completed as part of the NLP course I have been taking on Udemy by Lazy Programmer Inc. The link can be found at https://www.udemy.com/course/data-science-natural-language-processing-in-python/.

The poetry generator is a generative model that creates poetry in the style of Robert Frost. First-order Markov models, second-order Markov models, and initial state distributions are created from a file containing lines from Robert Frost poems. I chose to use a dictionary to represent these models since a regular n-d array may contain words in which the probability is 0, which wastes space. Furthermore, dictionaries that use the actual word as keys is much easier to implement and access than converting unique words to unique numbers.

I felt very accomplished after working on this particular project, especially since I did almost all of the coding myself, with mostly having guidance from high-level implementation details that the coding exercise provided. A great second project to help me practice my understanding of Markov models!
