## NMF_stocks

This is a mini-project using dynamic network analysis and NMF to assemble stock portfolios.

The aim of this project is to pick stocks whose prices move in dissimilar directions in response to market trends.

For every month over a 20-year period, I construct a weighted network graph where nodes represent companies and edges represent pairs of companies whose stock prices are closely tracked.  Based on this graph, I compute a matrix of network features for each company. By using NMF, I reduce this matrix to three feature archetypes.  These archetypes are linear combinations of network features that describe roles, or patterns of interaction, among stocks. Upon user prompting, this project assembles a bundle of stocks whose roles in recent years are most dissimilar to that of their chosen stock.

This is still a work in progress.
