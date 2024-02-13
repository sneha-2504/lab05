# lab05
rebase local branch 
editing the remote repo
2nd modification
C:\Users\Acer>E:

E:\>cd sneha1mv22cs155/gitlab

E:\Sneha1MV22CS155\gitlab>mkdir exp8

E:\Sneha1MV22CS155\gitlab>cd exp8

E:\Sneha1MV22CS155\gitlab\exp8>git init
Initialized empty Git repository in E:/Sneha1MV22CS155/gitlab/exp8/.git/

E:\Sneha1MV22CS155\gitlab\exp8>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git commit -m "file1 created"
[master (root-commit) 2156e7a] file1 created
 1 file changed, 1 insertion(+)
 create mode 100644 file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git checkout -b featurebranch
Switched to a new branch 'featurebranch'

E:\Sneha1MV22CS155\gitlab\exp8>file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git commit -m "first"
[featurebranch 8310668] first
 1 file changed, 2 insertions(+), 1 deletion(-)

E:\Sneha1MV22CS155\gitlab\exp8>file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git commit -m "second"
[featurebranch 9fa1b88] second
 1 file changed, 2 insertions(+), 1 deletion(-)

E:\Sneha1MV22CS155\gitlab\exp8>file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git commit -m "3"
[featurebranch 3a4929a] 3
 1 file changed, 2 insertions(+), 1 deletion(-)

E:\Sneha1MV22CS155\gitlab\exp8>file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git commit -m "4"
[featurebranch c41c1d3] 4
 1 file changed, 2 insertions(+), 1 deletion(-)

E:\Sneha1MV22CS155\gitlab\exp8>file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git commit -m "5"
[featurebranch 60f3dd8] 5
 1 file changed, 2 insertions(+), 1 deletion(-)

E:\Sneha1MV22CS155\gitlab\exp8>file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git commit -m "6"
[featurebranch 2d8dbc8] 6
 1 file changed, 2 insertions(+), 1 deletion(-)

E:\Sneha1MV22CS155\gitlab\exp8>git checkout master
Switched to branch 'master'

E:\Sneha1MV22CS155\gitlab\exp8>git checkout -b targetbranch
Switched to a new branch 'targetbranch'

E:\Sneha1MV22CS155\gitlab\exp8>file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git checkout featurebranch
Switched to branch 'featurebranch'

E:\Sneha1MV22CS155\gitlab\exp8>git log
commit 2d8dbc89eff25e3139aa25962eefec4fca57e34f (HEAD -> featurebranch)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:39:15 2024 +0530

    6

commit 60f3dd8cf79c63f53a23966a354aeacd881c4af9
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:38:51 2024 +0530

    5

commit 2d8dbc89eff25e3139aa25962eefec4fca57e34f (HEAD -> featurebranch)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:39:15 2024 +0530

    6

commit 60f3dd8cf79c63f53a23966a354aeacd881c4af9
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:38:51 2024 +0530

    5

commit c41c1d3b92efb9e720f13cfbed20f5818da736a2
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:37:37 2024 +0530

    4

commit 3a4929a4e842ca62388598cfb81bb279dfe23171
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:37:14 2024 +0530

    3

commit 9fa1b88a73c6d9506e645782045ad2c5abc1abbc
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:36:42 2024 +0530

    second

E:\Sneha1MV22CS155\gitlab\exp8>git log -n 7
commit 2d8dbc89eff25e3139aa25962eefec4fca57e34f (HEAD -> featurebranch)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:39:15 2024 +0530

    6

commit 60f3dd8cf79c63f53a23966a354aeacd881c4af9
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:38:51 2024 +0530

    5

commit c41c1d3b92efb9e720f13cfbed20f5818da736a2
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:37:37 2024 +0530

    4

commit 3a4929a4e842ca62388598cfb81bb279dfe23171
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:37:14 2024 +0530

    3

commit 9fa1b88a73c6d9506e645782045ad2c5abc1abbc
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:36:42 2024 +0530

    second

commit 8310668ac84b2f09f13f1a2994599e296ded713b
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:35:53 2024 +0530

    first

commit 2156e7a19b6afe1302bf21207b5ea2764be66936 (targetbranch, master)
Author: sneha <sneha251104@gmail.com>
Date:   Tue Feb 13 06:34:11 2024 +0530

    file1 created

E:\Sneha1MV22CS155\gitlab\exp8>git checkout targetbranch
Switched to branch 'targetbranch'

E:\Sneha1MV22CS155\gitlab\exp8>git cherry-pick 8310668ac84b2f09f13f1a2994599e296ded713b^..60f3dd8cf79c63f53a23966a354aeacd881c4af9
Auto-merging file1.txt
CONFLICT (content): Merge conflict in file1.txt
error: could not apply 9fa1b88... second
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".

E:\Sneha1MV22CS155\gitlab\exp8>file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git cherry-pick --continue
[targetbranch 351714a] second conflict resolved
 Date: Tue Feb 13 06:36:42 2024 +0530
 1 file changed, 4 insertions(+), 1 deletion(-)
Auto-merging file1.txt
CONFLICT (content): Merge conflict in file1.txt
error: could not apply 3a4929a... 3
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".

E:\Sneha1MV22CS155\gitlab\exp8>file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git cherry-pick --continue
[targetbranch 17cc23b] 3
 Date: Tue Feb 13 06:37:14 2024 +0530
 1 file changed, 2 insertions(+)
Auto-merging file1.txt
CONFLICT (content): Merge conflict in file1.txt
error: could not apply c41c1d3... 4
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".

E:\Sneha1MV22CS155\gitlab\exp8>file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git cherry-pick --continue
[targetbranch c87c86b] 4
 Date: Tue Feb 13 06:37:37 2024 +0530
 1 file changed, 1 insertion(+)
Auto-merging file1.txt
CONFLICT (content): Merge conflict in file1.txt
error: could not apply 60f3dd8... 5
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".

E:\Sneha1MV22CS155\gitlab\exp8>file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git add file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>git cherry-pick --continue
[targetbranch 3ab1da4] 5
 Date: Tue Feb 13 06:38:51 2024 +0530
 1 file changed, 1 insertion(+)

E:\Sneha1MV22CS155\gitlab\exp8>file1.txt

E:\Sneha1MV22CS155\gitlab\exp8>
