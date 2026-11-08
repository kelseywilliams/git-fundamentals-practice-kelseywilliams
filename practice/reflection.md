# Git workflow reflection

Write at least one complete sentence for each answer. Each answer must contain at least 20 characters.

## 1. What is the difference between a commit and a push?

Answer: A commit is a snapshot of the repository and a push sends all added commits to the remote repository

## 2. Why work on a branch instead of directly on `main`?

Answer: Working on a branch instead of directly on main allows for isolating different changes in order to keep experimental code from production code, keeping main stable and merging in reviewed and tested code

## 3. What does a pull request make possible?

Answer: Pull requests make project management more streamlined with contributors to a repo able to write changes and submit pull requests to trusted maintainers who can then approve these changes and merge them with main or another branch.  Repo maintainers can see stats on pull requests such as differences from main and changes made as well as discuss the requests and propose changes to the PR before acceptance. 

## 4. Which Git command helped you understand the repository's state, and what did it show you?

Answer: git status helped me to understand the repositories state by showing me the changes not staged and changes ready for commit
