# Present your work with Git and Rebase

## Exercise 8 - Rebase and split a branch

Scenario:

- In the previous exercise you moved the menu work to it's own commit.
- You realize you should really focus on the most important feature here, the awesome rolling Rick.
- You decide to split the menu out into it's own branch (without rick feature).
- That branch can later easily be picked up again for further work.

Instructions for exercise:

- Checkout branch `start`.
- Create a new branch `exercise`.
- Have a look at the commits in `solution` and `solution-menu` branch.
- Create a new branch `exercise-menu` containing the menu commit, but not the rolling Rick commit. 
- Rebase the `exercise` branch on commit "Add style for a bouncy ..." and drop the menu commit.
- Verify that the `exercise` branch contains the rick feature but not the menu.
- Verify that the `exercise-menu` branch contains the menu but not the rick feature.

Tips:

- [Rebase](https://git-scm.com/docs/rebase) the `exercise` branch and choose edit option.
- Use a GUI client such as [GitExtensions](http://gitextensions.github.io/) (Win), [Fork](https://git-fork.com/) (Mac + Win) or [GitKraken](https://www.gitkraken.com/) (Linux, Mac, Win) so that you don't have to figure out the git cli commands for doing the above.
- I've written a bit about dropping commits using GitExtensions on [my blog](https://blomholm.no/posts/how-i-git-it-basic-rebase/#drop-a-commit)

[Click here for next exercise](https://github.com/kraftlauget/git-ws-9)
