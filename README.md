# BLOCKCHAIN TCG

A trading card game build on the ethereum blockchain.

#### Core concepts

* Cards can be traded via the blockchain
* Matches get recorded on the blockchain

## The Game

Each player starts with a 32 card deck and 2000 life points (LP). The winning player is the first to reduce their opponents LP to 0.

Flip a coin to decide who goes first. The turn player starts with 5 move counters that reset at the beginning of their turn. **You don't draw any cards, there is no concept of a 'hand'.** The turn player can use their move counters to start play. A turn ends when the player has no move counters remaining or they choose to end their turn early. Move counters are used for the following:

* **Revealing a card** - To reveal a card flip the top card of your deck face up. You must then choose to play or discard the revealed card.

* **Attacking** - Attacking with a monster uses a move counter. Monsters can only attack once per turn.

* **Using abilities** - Some cards have special abilities that require move counters (MVCs) to activate.
