# Git Crash Course
```
$ git init

$ git add .

$ git commit -m

git chekout <commit_id>
```
* this will detach the HEAD from original location to given commit ID & rest of file changes above the head will deattached.But wont delete from git history.To revert; 
```
$ git checkout main

$ git branch -M main - set default branch of git call <main>

* <origin> is the alias of default remote repository 
** One repository can have more than 1 remote repos.
ex: origin = https://github.com/nteej/mastering_git.git
    origin_azure = https://liyanajayasinghe@dev.azure.com/liyanajayasinghe/Git%20Mastering/_git/Git%20Mastering
    origin_bb = bitbucket path
    origin_gl = GitLab path

```