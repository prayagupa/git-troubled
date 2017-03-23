git how to fix can not push changes

http://stackoverflow.com/a/24022075/432903

Problem
--------

I'm user1, a nice guy. I started working on a project with last commit as `user1-commit1`.

My boss comes in and says WTF, you need to make some changes. Me being a nice make changes 
and make a `commit2`.

And while trying to push it, error pops up

```bash

$ git push origin HEAD
To https://github.com/prayagupd/git-troubled.git
 ! [rejected]        HEAD -> master (fetch first)
error: failed to push some refs to 'https://github.com/prayagupd/git-troubled.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

```

Then I figured out Son of a programmer, user2 already made changes the same branch I
was working on, but me being a nice guy did not freak out at all.

Instead stashed my uncommited changes.

```

```
