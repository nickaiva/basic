 How Git works

Here is a basic overview of how Git works:

    Create a "repository" (project) with a git hosting tool (like Bitbucket)
    Copy (or clone) the repository to your local machine
    Add a file to your local repo and "commit" (save) the changes
    "Push" your changes to your master branch
    Make a change to your file with a git hosting tool and commit
    "Pull" the changes to your local machine
    Create a "branch" (version), make a change, commit the change
    Open a "pull request" (propose changes to the master branch)
    "Merge" your branch to the master branch

git remote add origin git@github.com:nickaiva/basic.git
git branch -M main
git push -u origin main

git commit -m "descriptiveText"
git status
git log --oneline --all >> log.txt
git branch --help for browser help
git brach -h for console
git branch newbranchName
git branch /*to find out which branch are you on*/
git branch --delete newBranchName
git checkout -b deletedBranchName hashcode /*undo a  brach deletion*/
git checkout commithashcode /* go to another commit */
git checkout -b newBranchName /* create new branch and switch to it*/
git checkout newBranchName /* switch from main branch into newBranch*/
git merge newBranchName /* to merge changes to main branch*/

git checkout -- filename /* undo any changes*/

/*push another feature branch other than main*/
 git checkout feature
 git push -u origin feature
 git push