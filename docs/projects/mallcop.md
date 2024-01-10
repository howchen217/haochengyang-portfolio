# Mall Cop

September 2022 - January 2023

"Mall Cop" is a multiplayer vesus game I created as my first master's game project. I collaborated with a team of six: three programmers, two artists and one game designer. I took on the responsibility of implementing most of the game systems and contributing to developing the multiplayer client-server logic.

**Code base:** [code base link](https://gitlab.com/alexyanghaocheng/Mall-Kop/-/tree/main)<br />
**Game link:** [itch.io link](https://haochengyang.itch.io/mall-kop)

In the game, players can choose the role of a cop or a thief. The Cop's objective is to defend the mall using various gadgets to prevent the thief from making off, while the thief's goal is to use everything they can to escape. The game shares a similar spirit with "Who's Your Daddy?!" but instead of a clueless father and an infant trying to stick a knife inside a socket, you have a cop setting up bucket traps around the mall and a thief throwing banana peels everywhere.

<iframe width="560" height="315" src="https://www.youtube.com/embed/dssXr--CDNA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Throughout development, I worked on creating the inventory and item pickup system, ensuring synchronization across both the client and server, in addition to the player movement and health systems. The main challenges we encountered were in the multiplayer aspect, as we utilized the recently released Unity Netcode. It was not fully documented then, and we encountered unexplained error messages. We made the mistake of implementing gameplay first and then attempting to migrate it to multiplayer rather than designing every system with both client and server considerations from the beginning. This decision led to a significant time investment in revamping features. Our lack of familiarity with the Unity Netcode resulted in incorrect judgment calls, which could have been avoided with more thorough research instead of rushing into development.
