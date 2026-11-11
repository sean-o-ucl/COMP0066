# COMP0066
This is the shared repository for the COMP0066 group work for group 15. 

## Using `git` in terminal
- `git pull repo-URL/SSH` will pull this remote repository to your current directory, allowing you to view/make changes on your computer. See the green <>code button near the top of this page.
    * If you do this via HTTPS, git will ask for your login credentials. For your password, you will need to enter a person-access-token (PAT) rather than your actual password. These can be generated under developer settings.
- `git checkout -b branch-name` creates a branch named branch-name, and switches you to this branch automatically. Code changes should be made in branches.
- `git add .` moves all changes you've made in your working directory to the _staging area_
    * **Staging area:** Intermediate area between working directory and local repository, allows you to organize changes before committing them.
- `git commit` will move the changes in the staging area to your _local reposity_
	* **Local repository:** Located on your computer, this is a repository where you can manage versions and make changes before you're ready to push them to the remote repository (GitHub)
- `git push` moves the changes you've made in your current branch and repository to the same branch on the remote repository.
    * At this point, you can navigate to the GitHub repo on the web, find your branch, and open a _pull request_
        + **Pull Request:** Sends a request to the owner of the repository to look at your branch and merge it into the "main" branch