# GitHub Tutorial

_by Raquel Joseph_

---
## Git vs. GitHub
Git is version control which allows you to take snapshots of your code. Git does not require github.  
Github is an online cloud that stores your code, visually tracks your changes, easier way to collaborate on files, and requires git.


---
## Initial Setup
An ssh key is...

**Type**
```bash
ssh -T git@github.com
```  

**After you should see** 
```bash 
Hi <your username>! You've successfully authenticated, but GitHub does not provide shell access.
```

---
## Repository Setup
**Github Set Up**
1. Create a Github account
2. Create a new repository named [folder name]

**Cloud 9 Set Up**
1. Open c9
2. You should see your terminal which looks like this
3. Now you need to create a folder  
    * use `mkdir [folder name]`
4. cd into [folder name]
5. then type `git init` to initialize git
6. insert picture here!

---
## Workflow & Commands
#### Status
What is `git status`?  
`git status` is used to see which files are staged to be committed.

#### Add
What is `git add`?  
`git add` is used to add files to the stage. You use `git add .` to add all files to the stage to be committed. You use `git add --all` to add all **renamed or deleted files** to the stage to be committed.

#### Commit
What is `git commit`?  


#### Push
What is `git push`?  


---
## Rolling Back Changes