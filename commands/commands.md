# Some useful commands

### I messed up my Git repo by trying out some fancy command from StackOverflow.

This happens to the best of us, and fortunately, Git has a magic time machine, or rather, a log of every event that happened in the git repo.

To use this:
- `git reflog` will list the history of git commands that have been invoked in the repository.
- To reset to a point in the history, do `git reset HEAD@{index}` where index is the number inside the {} in the reflog. Usually starts from 0.