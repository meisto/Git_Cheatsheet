# <p align="center">Git Cheatsheet</p>
### <p align="center">Personal Git Cheatsheet</p>

Work in progress

## Setup local CLI
```
git config --global user.email "username@users.noreply.github.com"
git config --global user.name "username"
git commit --amend --reset-author
```

## Setting up a project
An overview over the various licenses can be found here:
[Choose a license](https://choosealicense.com/)

```
git init
git add README.md
git commit -m "Initial commit"
git branch -M main      # Give the current branch a name
```

## Gitignore
[Gitignore Cheatsheet](https://linuxize.com/post/gitignore-ignoring-files-in-git/)

Removing files that were already commited but later added to *.gitignore*:
```
git rm --cached file
```

## Pushing a project to a remote server:
```
git remote add origin link-to-repo
git push -u origin current-branch
```

## Markdown
Markdown is the format in which one styles files in both GitHub as well as in jupyter notebooks. It is a very easy filetype and can be transpiled in both HTML and LaTex. 
**Further sources:**  
- [General markdown (German)](https://markdown.de/)
- [GitHub-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
- [Grip - Viewer for GitHub-flavored Markdown](https://github.com/joeyespo/grip)
- [Markdown Tutorial](https://www.howtogeek.com/448323/what-is-markdown-and-how-do-you-use-it/)
