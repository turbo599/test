Microsoft Windows [Version 10.0.18363.1198]

student@DESKTOP-VVP8Q69 c:\users\student\desktop\openserver
# cd domains

student@DESKTOP-VVP8Q69 c:\Users\student\Desktop\OpenServer\domains
# cd lesson1

student@DESKTOP-VVP8Q69 c:\Users\student\Desktop\OpenServer\domains\lesson1
# git add lesson1.php

student@DESKTOP-VVP8Q69 c:\Users\student\Desktop\OpenServer\domains\lesson1
# git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   lesson1.php


student@DESKTOP-VVP8Q69 c:\Users\student\Desktop\OpenServer\domains\lesson1
# git checkout lesson123
Switched to branch 'lesson123'
M       lesson1.php

student@DESKTOP-VVP8Q69 c:\Users\student\Desktop\OpenServer\domains\lesson1
# git commit -m "lesson1.php"
[lesson123 7070dca] lesson1.php
 1 file changed, 150 insertions(+), 69 deletions(-)
 rewrite lesson1.php (98%)

student@DESKTOP-VVP8Q69 c:\Users\student\Desktop\OpenServer\domains\lesson1
# git commit
On branch lesson123
nothing to commit, working tree clean

student@DESKTOP-VVP8Q69 c:\Users\student\Desktop\OpenServer\domains\lesson1
# git push
fatal: The current branch lesson123 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin lesson123


student@DESKTOP-VVP8Q69 c:\Users\student\Desktop\OpenServer\domains\lesson1
# git push origin lesson123
Logon failed, use ctrl+c to cancel basic credential prompt.
Username for 'https://github.com': turbo599
Password for 'https://turbo599@github.com':
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 923 bytes | 923.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/turbo599/lesson1.git
   1ac56b3..7070dca  lesson123 -> lesson123

student@DESKTOP-VVP8Q69 c:\Users\student\Desktop\OpenServer\domains\lesson1
#

