# MisplacedTowns

## Deck
Deck has five colors (red,white,yellow,green,blue).  Each color has card values 2-10 and 3 handshakes (HS).  
## Rules/Gameplay
Game is played with a center/common board that lays out each of the colors.  Players can discard a card by playing it face up on the matching color.  Players can play a card by placing it face up on the matching color on their side of the board -- this is called starting an expedition.  Card values must be played in ascending order (but not necessarily sequential).  Handshakes count as the lowest value, so must be placed first.  
On a players turn, they must first play or discard a card, and then draw a card either from the deck or from the discard.
Both players start with 8 cards!

## Scoring
Each expedition starts with a value of -20.  The value of the expedition is the sum of the values of the cards played on it.  Handshakes will double,triple or quadruple the point total if 1,2, or 3 handshakes are played.  The handshake multiplayer is applicable for positive or negative point values.

## Input
On players turn, they will select 0 to discard a card, or 1-5 to play in one of those spots.  


## AI
All AI classes need to implement  a computerMakeMove("PlayerStrName",P1Hand,community) method.

## TODO
Make it web based -- https://codyparker.com/django-channels-with-react/9/