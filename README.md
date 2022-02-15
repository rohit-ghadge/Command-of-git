
## Usage/Examples

# git init
    creates a new Git repository on local machine 
# git add . 
    add all file to staging area of local machine
# git commit -m "write comment here"    
    add changes to local repository 
# git remote add origin repository name
    Ex - git remote add origin https://github.com/rohit-ghadge/Selenium.git
    connect to remote origin (needed when you are connecting for first time)
# git push origin master 
    sends all the pending changes to the remote repository.
    Username and password asked for authentication
    Username - github username
    Password - token
    steps to generate token  - 
    go to Setting- Developer Setting - Personal Access Token
# git pull
    get the changes from the remote and merge them into your local machine
# git pull --rebase 
    as above, but try to redo your commits on top of the remote changes
# git branch subBranch
    create new branch
# git rev-parse --abbrev-ref HEAD
    To display the current branch you're on, without the other branches 
    listed, you can do the following:
# git checkout subBranch 
    This is obvious to go into that branch.
# git reset --hard origin/master
    If your local changes are bad then just remove them or reset your local 
    master to the state on remote 
# Git log
    Git log is a utility tool to review and read a history of everything 
    that happens to a repository
# git status
    The git status command displays the state of the working directory and
    the staging area.
    
## Screenshots of Flow of Git

![git_Working](https://user-images.githubusercontent.com/57706022/154007752-477ce2e5-0510-4945-9a1e-0ca529c6449a.png)



