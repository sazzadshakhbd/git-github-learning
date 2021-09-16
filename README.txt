Git Setup
---------
1. git init [git initialize]
Git Add Command
---------------
1. git add --all [All all files & folder]
2. git add -A [All all files & folder]
3. git add . [All all files & folder under directory]
4. git add \* [Add all files & folder with untracked files]
5. git add \*.txt [Add all tex files]
6. git add one.txt [Add specific files]

Git command role back / reset
-----------------------------
1. git reset HEAD~ [Back to previous stage after commit]
2. git reset --hard [Back to deleted file & folder after commit]
3. git reset (All files & folder back to previous version before commit)

Git command remove file
-----------------------
1. git rm two.txt [Remove files command]
2. git rm one.txt -f [Remove files and folder command forcefully]
3. git rm myfolder -r [Remove folder to inner folder and file command ]
4. git rm --cached one.txt [Remove files but not changed staged]
5. git rm myfolder [Remove only folder]

Git Branching
-------------
1. git branch [show branch list]
2. git branch development [create and copy master branch all and create & paste development branch]
3. git checkout development [switch to development branch from master branch]
4. git merge development[brach name] -m "merge development branch" [Merge development branch to main branch]

Git Remote
----------
1. git push origin development [push development branch remotely]
2. git push [push main branch]
3. git fetch [push change files]
4. git merge [if you git fetch command then git merge command have to be done.]


