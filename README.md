# github-appendix
Extra tips and resources relating to concepts covered in the workshop.

## Github tips
### Initializing a git repo: 2 ways
#### Create remote first
1. Create a new repo or fork an existing repo in your Github account online. Then use `git clone <repo.git>` to copy the repo to your local machine. (This is what we did in the workshop.)

#### Create local first
2. Locally create a new directory for your project, `cd` to the directory, and enter `git init`. This will turn your directory into a git repo with a `.git` file. Add a remote with `git remote add <remote_name> <remote_repo_url>` and set this as the repo to push to with `git push -u <remote_name> <local_branch_name>`.

More info:  
https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-init  
https://www.atlassian.com/git/tutorials/syncing



### Git rebase in depth
You can rebase one branch by itself, or rebase a branch onto another branch. 
More info: https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase


### Commit access with SSH keys
More info: https://help.github.com/en/enterprise/2.15/user/articles/adding-a-new-ssh-key-to-your-github-account


## Other
### Basic bash commands
More info: https://dev.to/awwsmm/101-bash-commands-and-tips-for-beginners-to-experts-30je
https://www.unr.edu/research-computing/the-grid/using-the-grid/bash-commands

### Markdown
More info: https://guides.github.com/features/mastering-markdown/

## Open source projects to get started
### TODO
