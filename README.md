# WORDLE-VISION
_Up your Wordle game!_

Are you obsessed with playing the increasingly-popular word game <a href="https://www.powerlanguage.co.uk/wordle/">Wordle</a>?

Ever wondered what the optimal first word to guess might be?

As a fan of the game myself, I've done some quick analytics to try and help guide you.

Final output is a text file of 60 words (best_guesses.txt) that are good initial guesses when playing Wordle. 
The list can, with manual curation, be pared down further to only the more common words used in the game.

Python 3
--------

**Requirements**

- urllib
- collections
- numpy
- seaborn
- matplotlib

Acknowledgments
---------------

This code uses a lexicon of English words provided on GitHub by dwyl <a href="https://github.com/dwyl/english-words">here</a>.

Further Reading
---------------

A write-up of this work can be found <a href="https://towardsdatascience.com/wordle-vision-simple-analytics-to-up-your-wordle-game-65daf4f1aa6f">here</a>.

A independent analysis that uses a different data set and looks into letter placement can be found <a href="https://cosmiccoding.com.au/tutorials/wordle">here</a>.

Update using New York Times Wordle List (30 Apr 2022)
----------------------------------------------------

Updated my analysis to use the <a href="https://static.nytimes.com/newsgraphics/2022/01/25/wordle-solver/assets/solutions.txt">official Wordle solutions list</a> of 2,309 words. 

I also find pairs of words that are good opening 1st and 2nd guesses that will help you to eliminate letters. 

Added a list of previous Wordle solutions as of 29 Apr 2022 (previous_wordle_solutions_314.txt) in order to remove them from my analysis. 
