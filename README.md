# Git Graph

Git Graph is a git command for showing the branch history as a graph. It's similar to `git log --graph --abbrev-commit --oneline`, but with several key things inspired by [GitKraken's](https://gitkraken.com) graph:

 - Branch names are displayed to the left of the graph, making it easier to find the branches
 - Branches are drawn as straight vertical lines (they never twist), making it a lot easier to follow them and find merges
 - The commits are shown as ASCII identicons and not hashes by default, making it easier to trace peoples' work

## Installation

### Linux and Mac:

Copy `git-graph` to somewhere in your path. Run as `git-graph` or `git graph` within a repo. The script is written in Ruby so you need to have that installed.

### Windows:

To be determined
