GIT COMMANDS
Useful Resources: git-scm.com, docs.github.com 
Tools: Windows PowerShell x86


VS Code extension: Git graph

git --version / git -v
git status
ls -la (for hidden folders)

git init (initialize git)

Get-ChildItem -Force (view subfolders)

cd.. (get out of the current folder)

git push
git commit
pwd (present working directory)

New-Item -ItemType File -Name "newfile.txt" (Add new text file)
git add (Add file to staging area)
git add . (Add all files to staging area)

git commit -m "Add commands.md" (Save files to Git)
q (Escape)

“files with spaces or long” – use quotation marks


NOTES:
clone (Repository hosted somewhere like GitHub)
add 	(edit files and add changes to GIT)
commit (save files/changes to GIT)

git log
git log –oneline
(All git logs in one line)


git config
(How it gets to know about your details)
git config --global user.name "Christopher Mawela"
git config --global user.email christopher.mawela@gmail.com
git config --global core.editor "code --wait" 



.gitignore
(don’t track files, e.g. node_modules, files holding passwords and API keys)
new-item .gitignore
(Add empty gitignore file, ignores files holding sensitive info e.g. .env Variables files for holding API keys, etc)
git commit
git log



push (upload git commits to a remote repo)
pull (download changes to remote repo to your local machine)
	





