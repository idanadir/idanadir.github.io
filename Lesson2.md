# Lesson 2 - Working with Github:

## Creating new repositor
- Create an online repository in github (pretty straigt forward)
- First: install git scm on PC
- Open git-bash app – this opens a command line window
- Decide on where you would like your workspace to be and enter 'cd <path>' 
- Then make new directory for your local repositort using 'mkdir' path
- Enter username and password from your github account:
- To allow authorisation for git, make a .SSH key:
	- type: 'ssh-keygen -t ed25519 -C your_email@example.com'
	- Press enter '> Enter a file in which to save the key (/c/Users/you/.ssh/id_algorithm)'
	- Write private password '> Enter passphrase (empty for no passphrase):'
	- Enter it again: 'Enter same passphrase again:'
	- Start ssh-agent in the background	'eval "$(ssh-agent -s)'
	- Add your SSH private key to SSH agent: 'ssh-add ~/.ssh/id_ed25519'
- Branch out to main 'git branch -M main'
- Link local repository with online one : 'git remote add origin git@github.com:idanadir/idanadir.github.io.git'

## Create markdown file in repository:
- Create a file in your repository folder with an .md
- In the git bash enter git init
- Then git add <filename> which stages your file.
- Before uploading, enter 'git commit -m "some message"'
- to upload enter 'git push -u origin main'
