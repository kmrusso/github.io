# github.io
'''mermaid
flowchart TD
   A[6]
   L[0]
   G[11]
   Start[[Start]]-->|Guess a the correct number between one and 10| B{Enter a number}
   B --> |L<B>A| C[Too low] --> B
   B --> |B<A>G| D[Too High] --> B
   B --> |B=A| E[Correct Answer]
   B --> |B<L| F[Not In range] --> B
   B --> |B>G| K[Not In range] --> B
   E -->End[[End]]  
'''
Made a variable to hold the random number.
Make variables for numbers outside the range.
Started up the game and introduced the instructions.
Made a input box to enter guess.
Put in different endings for different guesses.
Once guess is correct, it ends the game.