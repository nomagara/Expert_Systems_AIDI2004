# Expert_Systems_AIDI2004
This is Repository for AIDI-2004 Expert System course

This is first change to Update readme file

#Description of My Programmes 

git status #used to track the current status of repo 
git add *  #used to add new changes
git commit -m "change txt" #used to commit with descriptions
git log #track history

#Description of Lab2 
Last login: Tue Feb  6 16:02:36 on ttys002
(base) nomagara@Nomagara-MacBook-Pro ~ % cd Projects
(base) nomagara@Nomagara-MacBook-Pro Projects % ls
Expert_Systems_AIDI2004		expert_system
Stanley_Omagara_model_v1.ipynb	git-demo
(base) nomagara@Nomagara-MacBook-Pro Projects % cd Expert_Systems_AIDI2004 
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % ls
README.md			sample_python_script.py
Stanley_Omagara_model_v1.ipynb
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % git 
checkout model_v2
error: pathspec 'model_v2' did not match any file(s) known to git
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % git status      
On branch python_branch
Your branch is up to date with 'origin/python_branch'.

nothing to commit, working tree clean
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % git switch 
main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % git 
checkout model_v2
error: pathspec 'model_v2' did not match any file(s) known to git
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % ls
README.md		sample_python_script.py
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % git pull
Enter passphrase for key '/Users/nomagara/.ssh/id_rsa': 
From github.com:nomagara/Expert_Systems_AIDI2004
 * [new branch]      model_v2_branch -> origin/model_v2_branch
Already up to date.
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % git switch 
model_v2_branch
branch 'model_v2_branch' set up to track 'origin/model_v2_branch'.
Switched to a new branch 'model_v2_branch'
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % ls
README.md		sample_python_script.py
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % cp 
~/Downloads/Stanley_Omagara_model_v2.ipynb 
~/Projects/Expert_Systems_AIDI2004 
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % ls
README.md			sample_python_script.py
Stanley_Omagara_model_v2.ipynb
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % git status
On branch model_v2_branch
Your branch is up to date with 'origin/model_v2_branch'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	Stanley_Omagara_model_v2.ipynb

nothing added to commit but untracked files present (use "git add" to 
track)
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % git add *
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % git commit 
-m "adding model_v2"
[model_v2_branch 6f2cac5] adding model_v2
 1 file changed, 117 insertions(+)
 create mode 100644 Stanley_Omagara_model_v2.ipynb
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % git status
On branch model_v2_branch
Your branch is ahead of 'origin/model_v2_branch' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % git push
Enter passphrase for key '/Users/nomagara/.ssh/id_rsa': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 17.65 KiB | 8.83 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:nomagara/Expert_Systems_AIDI2004.git
   625ee62..6f2cac5  model_v2_branch -> model_v2_branch
(base) nomagara@Nomagara-MacBook-Pro Expert_Systems_AIDI2004 % git log
commit 6f2cac594fdd756780b49e2784b5f1ae6840fa3f (HEAD -> model_v2_branch, 
origin/model_v2_branch)
Author: Nomagara <stanleynonsoomagara@gmail.com>
Date:   Tue Feb 6 17:28:35 2024 +0100

    adding model_v2

commit 625ee62e5cbc5ad62d0a4e72752eae80bc528987 (origin/main, origin/HEAD, 
main)
Merge: 6034e71 bf5bd1a
Author: Nomagara <stanleynonsoomagara@gmail.com>
Date:   Sun Jan 28 18:31:24 2024 +0100

    adding new python file

commit bf5bd1abbaa61545a98504c7d3de0812e592bd86
Author: nomagara <144392977+nomagara@users.noreply.github.com>
Date:   Sun Jan 28 18:18:45 2024 +0100

    Create sample_python_script.py

commit 6034e713a247cbb2b3fe4e42233ee8d71410c551 (python_branch_main)
Author: Nomagara <stanleynonsoomagara@gmail.com>
Date:   Sun Jan 28 17:42:11 2024 +0100
:

