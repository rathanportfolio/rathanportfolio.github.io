# rathanportfolio.github.io

Install git bash:
    https://git-scm.com/downloads

Clone git repository:
    clone https://github.com/rathanportfolio/rathanportfolio.github.io.git

to connect from local(our local machine) to origin(git hub)    

    git remote add origin "https://github.com/rathanportfolio/rathanportfolio.github.io.git"

pull the files from remote master.
    git pull origin master 

status: to check the status.
    git status    


in local, if we need to add file or folder, we should create a branch.
branch creation:

    git checkout -b rathan_b1 (to create new branch)
    git checkout "branch" (to move to that branch)

to merge master code into out branch(rathan_b1):
    git merge master

add or create files or folder and update(rathan_ba)

to check the status:
    git status

to add file into our branch(rathan_b1)
    git add file name
    git add -A (to add multiple files)

    git status
to save(commit) the file in rathan_b1:
    git commit -m 'proper message'

to save(commit) rathan_b1(local) to rathan_b1(remote origin)
    git push --set-upstream origin rathan_b1

for next commits use:
    git push origin rathan_b1
