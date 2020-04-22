# Design Goal-Oriented Level Design

This work began in the hopes of creating a process to enable designers to build better levels that combine a game's mechanics and narrative smoothly. After designing and building multiple levels without a formal process, it became clear that there must be a better way to construct the framework of a level before building begins. We decided the best plan was to generate our own process and attempt to formalize as much of it as possible.

[![SIGGRAPH poster preview](/img/pace.png)](/img/pace_full.png)

One of the most significant tools that we generated as a part of this process is the Pace Digraph. What this graph illustrates is a series of nodes that will compose a level of a game. Each logical node is one chunk of a level where something of significance can happen. Each one of these nodes can be illustrated by using our Gameplay Situations construct.

Traversal
: A situation in which the player's objective is to move either their avatar or some controlled asset from one point in the game's space to another.

Defense
: Any time that a player has to use game mechanics in order to defend themselves. This can include traditional combat, or more abstractly, careful positioning on a game board in a game like chess.

Another strong utility that we created from this process is the rapid sketch prototype of a level. By using the node-based structure of the pace digraph, we can break the level down into logical sections based around each node. For a theoretical survival horror game this process works very well when we make each node into its own room. We can see on the sketch that the reconfigurable set of nodes has allowed us to very rapidly draft a design of a whole level without having to agonize over the juxtaposition of gameplay elements in the environment.

This process also streamlines the introduction of narrative and environmental storytelling events by including them as data in the nodes on the digraph. By combining all of these formalized design processes into one set of documents we have effectively made a rapid, effective way to design a level for a game.
