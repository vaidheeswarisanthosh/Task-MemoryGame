Explanation of the project:

1.Array of Cards (cardsArray):

     The cardsArray contains pairs of card objects, each having a name and an icon. Each card appears twice.

2.Shuffle Function:

    shuffleCards() uses the Fisher-Yates algorithm to shuffle the cards at the beginning of the game.

3.Display Cards (displayCards):

   This function creates a card element for each card in the array and appends it to the game board. Each card is initially displayed with the class cardback and has an active class for click handling.

4.Card Flip (flipCard):

   When a card is clicked, it is flipped (by removing the cardback class and showing the corresponding icon). Two flipped cards are held in flippedCards, and once two are flipped, the checkMatch function is triggered after a short delay.

5.Check Match (checkMatch):

   If the two flipped cards match (i.e., have the same name), they are marked as inactive by removing the active class. If they don’t match, the cards are flipped back.

6.Restart Game (restartGame):

The restart button shuffles the cards and resets the game state for another round.



How to Play the Game:

1.Start the Game:

    Upon loading the game, you will see a grid of cards.

2.Flip Cards:

    Click on any card to flip it and reveal the icon. You can only flip two cards at a time.

3.Match the Pairs:

    If the two cards you flip have the same icon, they stay revealed. If they don't match, they will flip back after a brief delay.

4.Restart the Game:

    Click the "Restart" button at any time to reshuffle the cards and start a new game.