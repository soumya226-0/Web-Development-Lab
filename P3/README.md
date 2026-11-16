# P3 - Feature-Branch Git Workflow

## Aim
To understand and practise the Git branching and merging process.

## Tools Required
- VS Code
- Git
- GitHub
- Terminal

## Theory
Git branching allows developers to work on different features separately without changing the main branch directly. After completing the work, the branch can be merged into the main branch.

## Commands Used

| Command | Description |
|---|---|
| `git switch -c feature/p3` | Creates and switches to a new branch |
| `git branch` | Displays available branches |
| `mkdir P3` | Creates a new folder |
| `touch P3/branch-demo.txt` | Creates a text file |
| `git add P3` | Adds P3 files to staging |
| `git commit -m "Complete Practical 3"` | Saves the changes |
| `git switch main` | Switches to the main branch |
| `git merge feature/p3` | Merges the feature branch into main |
| `git push` | Pushes changes to GitHub |

## Procedure
1. Created a new branch named `feature/p3`.
2. Created a folder named P3 and a sample text file.
3. Added the changes to the staging area.
4. Committed the changes on the feature branch.
5. Switched back to the main branch.
6. Merged the feature branch into main.
7. Pushed the updated repository to GitHub.

## Result
Successfully created and merged a feature branch using Git.