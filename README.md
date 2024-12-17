…or create a new repository on the command line
-----------------------------------------------
echo "# ui" >> README.md
git init
git status
git add README.md
git status
git commit -m "first commit"
git status
git branch -M master
git remote add origin https://github.com/sugganabalaji/ui.git
git push -u origin master

…or push an existing repository from the command line
-----------------------------------------------------
git remote add origin https://github.com/sugganabalaji/ui.git
git branch
git branch -M master
git push -u origin master
