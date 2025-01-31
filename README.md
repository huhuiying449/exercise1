# CTA-ED-exercise1
In this repository you will find the data and Rmarkdown (Rmd) script for exercise 1 (to be completed for the 5th of February 2025). This is part of the course 'Computational Text Analysis' taught at the University of Edinburgh by Dr. Marion Lieutaud.

## Starting instructions
You are doing this exercise in teams of 2 or 3. Stard by deciding who among you will take charge for _forking_ this repository, as shown in class (make sure your fork is for personal use). Once you have created a forked repository, _add your collaborator(s)_ so you are all working on the same repository. Then each of you can _clone_ this repository, as demonstrated in the class (click on the 'code' green button, then 'open with Github Desktop'). Once you have cloned the repository onto your laptop, open the .Rmd file 'CTA_exercise1_wordfreq.Rmd' in your RStudio, run the code chunk by chunk, making sure you understand every step. Then look at the exercise questions at the end of the .Rmd file. You will need to write and execute your own code to answer them. Because most of you are at the beginning of your programming journey, I recommend that you work on the code as a group, ideally sitting together. I would advise against dividing up the exercise questions between group members - this is a foundational exercise and you want to make sure that all of you understand every bit. 
For this exercise, don't worry about 'pushing' your edits back to the online repository: you can just work locally, on your own laptop.

You should draw on the code presented in the exercise, the week 2 demo [https://marionlieutaud.github.io/CTA-ED/week-2-demo] and the livecoding scripts that we have developed in the tutorials (these are available on my Github). You can also look for help and inspiration in other online resources, especially the quanteda tutorial page [[https://quanteda.io](https://tutorials.quanteda.io/)] or quanteda quick start guide [https://quanteda.io/articles/quickstart] and by looking up problems or error messages on Stack Overflow [https://stackoverflow.com]. That's how programmers do it! 

You could also use ChatGPT but you should know that its use of R is quite outdated; ChatGPT is (for now anyways) not great at coding, especially in R, and you will not learn much by copy-pasting from it. ChatGPT is better at explaining R code than at generating it, so that may be a more useful way to use it if you're keen on it.

As many of you already noticed, there are different ways to write code for the same operations (e.g. tokens() or unnest_tokens(). These do roughly the same thing, only the first command is part of the 'quanteda' package and the second command is part of the tidyverse). There is (almost) never a single command or method to do something in R (or in programming in general) so do not let that disorientate you; you can use whichever package and command work: there are many ways to get to the right answer!
