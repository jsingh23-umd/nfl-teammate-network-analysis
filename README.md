# nfl-teammate-network-analysis
# NFL Teammate Network Analysis

This project analyzes connections between NFL players using roster data from 2015 to 2025.

In the network, each node represents an NFL player. An edge connects two players if they were teammates on the same team during the same season.

The main question:
Which NFL players are the most connected based on the number of different teammates they have played with?

## Data

The project uses historical NFL roster data from the nflverse data repository.

## Analysis

Python and NetworkX were used to build the network and analyze player connections. Degree centrality was used as the main measure of importance, and PageRank was also used to examine important players in the network.
