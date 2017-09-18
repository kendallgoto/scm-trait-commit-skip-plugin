# Branch source commit skip traits

This repo is a collection of traits for several branch-source Jenkins plugins.

It provides filters for
 - GitHub: Filtering pull requests 
 - Bitbucket: Filtering pull requests


The filtering will be performed matching the last commit message, applying it whether it starts with [skip ci] or [ci skip]. The check is case-insensitive.