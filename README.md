**BlackJack Smart Effect of Removal ML**
Predicting Expected Value Changes in Blackjack Through Card Removal Analysis

**Goal**

Predict the Expected Value (EV) changes in Blackjack based on card removal patterns from a 6-deck shoe. 
Your model should accurately estimate how removing specific combinations of cards affects the remaining deck's EV, 
providing a machine learning alternative to traditional combinatorial analysis.

**The Challenge**
You are provided with data showing:

Number of cards removed for each value (1-10)
The corresponding EV of the remaining deck
Training data (20,500 rows):
1, 2, 3, 4, 5, 6, 7, 8, 9, 10, ev
0, 1, 0, 1, 2, 2, 3, 0, 1, 3, -0.024345
1, 11, 5, 5, 12, 7, 8, 10, 9, 30, -0.024339
…

Test data (8,655 rows):
1, 2, 3, 4, 5, 6, 7, 8, 9, 10
12, 6, 10, 7, 8, 10, 11, 5, 8, 43
11, 5, 9, 5, 7, 9, 9, 10, 8, 27
…

**Evaluation**
Models are evaluated using Mean Squared Error (MSE). Successful solutions should balance accuracy with computational efficiency.

**Here is the link to the competition:** https://www.kaggle.com/competitions/black-jack-smart-effect-of-removal-ml


