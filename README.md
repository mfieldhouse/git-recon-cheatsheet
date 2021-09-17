# Git Recon Cheatsheet
## A cheatsheet of commands to help you investigate Git repositories

**Recon = Reconnaissance**: "The act of scouting or exploring to gain information."

**Problem**: You've used `git clone` to copy a GitHub repository locally. Now you want to show all branches that currently exist for the project.

**Solution**: `git branch -a`

**Problem**: You want to see all commits by a particular person

**Solution**: `git log --author=tom`

If you use the command without quotes around the name, the search is not case sensitive. It will match the characters at any position of the name.

If you use single quotes or double quotes, the search is case sensitve. Again, it will match the characters at any position.