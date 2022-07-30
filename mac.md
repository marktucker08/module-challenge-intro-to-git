## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is the version control software with commands that are used on the local terminal.
2. What is the difference between Git and GitHub?
https://docs.github.com/en/get-started/quickstart/hello-world
https://docs.github.com/en/get-started/quickstart/set-up-git
Git is the local commands used to update and tack changes to your code. GitHub is the cloud warehouse of Git repositories. GitHub stores all of the changes made to the repository.
3. Why do we create a branch? 
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches
Branches allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository.
4. What is the purpose of a Pull Request?
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub.
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
git switch main
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
https://training.github.com/downloads/github-git-cheat-sheet/
They all syncronize changes with the remote repo on GitHub. Git fetch downloads all history from the remote tracking branches. Git merge combines remote tracking branches into the current local branch. Git pull Updates 
your current local working branch with all new commits from the corresponding remote branch on GitHub. git pull is a combination of git fetch and git merge.
7. What is a merge conflict?
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts
Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.
8. How do you resolve a merge conflict?
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts
To resolve a merge conflict, you must manually edit the conflicted file to select the changes that you want to keep in the final merge. There are a couple of different ways to resolve a merge conflict:

If your merge conflict is caused by competing line changes, such as when people make different changes to the same line of the same file on different branches in your Git repository, you can resolve it on GitHub using 
the conflict editor.
For all other types of merge conflicts, you must resolve the merge conflict in a local clone of the repository and push the change to your branch on GitHub. You can use the command line or a tool like GitHub Desktop to 
push the change.
