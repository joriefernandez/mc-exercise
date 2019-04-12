# mc-exercise









The first problem was after the two teams made changes on separate branches to the files and the merged to master, then Bob did not pull the changes down from master and instead worked on his original file. Then when he tried to merge it back up, his was not up to date. We solved this by going to GitHub and “resolve pull request”. We resolved one team’s branch and merged, then switched to the other team’s branch and merged. Then everyone pulled down to master and everything was fine again.

The next conflict was when both teams were working on the master at the same time. They should have switched to branches. One team pushed before the other, so then the second team could not push. So we did a git status which said that the second team was behind the master branch. So they did a git pull, resolved the problems in VS code, and did an ACP and that synced up the master branch. From there everyone pulled down and everyone was up to date.