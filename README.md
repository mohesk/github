# github
github cheatsheet

# setup a working environment, including a fork from a repository
* This will create a new folder dedicated to the project and Move to the project directory
```sh
git init <projectName>
cd <projectName>
```
* Add remote repo “prime”.

`git remote add prime https://github.com/<repo_owner>/<projectName>`

* Add remote repo “origin”.

`git remote add origin https://github.com/<username>/<projectName>`

* Download latest code from prime.

`git pull prime master`

 * Create local branch for current development

`git checkout –b <meaningfulBranchName>`

#  create a pull request to push local modifications

* Add files to be committed

`git add path1/filename1.c path2/filename2.h`

* Commit the changes. 

`git commit –m”Meaningful commit message explaining what’s the purpose of the pull request and how it was implemented”`

* Push to remote origin

`git push origin <meaningfulBranchName>`

* Open pull requests

`To open the pull request, go to <username> fork on github and press “create pull request”. `
