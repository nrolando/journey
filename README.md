# journey - best temporary game name i could come up with..

For Starters
*In your git client, clone repo to desired location, e.g.:
	cd path_to/git/repos
	git clone https://github.com/nrolando/journey.git
*Run Unity and open project -> "journey"
	*Note: Unity should create "Library" (and maybe "Temp") folder(s) under the project root for you. These should be in the .gitignore file so they are excluded.
*Do not work in the "master" branch. Checkout a new branch that tracks the remote master branch:
	git checkout -b your_branch_name origin/master
*To pull and merge changes from other devs.. Commit your work in your branch, checkout master, fetch origin, pull remote master, checkout your branch, merge master.. e.g.:
	git add -A
	git commit -m "Meaningful commit description"
	git checkout master
	git fetch origin
	git pull origin master
	git checkout your_branch_name
	git merge master
*To commit and push your updates to the repo.. Commit your changes in git and push up to your branch. E.g.:
	git add -A
	git commit -m "Meaningful commit description"
	git push origin your_branch_name


Update the Master Branch
	*First make a Pull Request to the "staging" branch
	*I'll merge and test the updates, and if successful I will merge to master
