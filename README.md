# Steps to create a boilerplate
## VS Code
In order to check what the markdown looks like, you can press `STRG + SHIFT + V` in VS Code.

## Python
`python -m venv venv` creates a virtual environment so that you can install packages without affecting the global Python packages
`.\venv\Scripts\activate` activates the virtual enviornment. You can then install packages using `pip install`

`pip freeze > requirements.txt` creates a file with all your currently installed packages. It can be used with `pip install` in case you clone the repository to another computer.

## Git(hub)

`git config --global user.email "you@example.com"` set the credentials for git - you can omit the global.
`git config --global user.name "Your Name"` set the credentials for git - you can omit the global.
`git init` creates an empty git repository
`git add README.md` create the readme file
`git commit -m <text>` set your initial commit
`git branch -M main` sets the main branch to `main`
`git remote add origin <URL>` set the url of the git repository you want your files to be pushed (previously created via the web interface)
`git push -u origin main` push the changes to the repository

After that, you can also perform the git operations with the GUI of VS Code.