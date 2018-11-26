In order to get things pushed up to github, here is a cheat sheet to help you get going. Depending on whether or not your are starting from scratch or you are forking a previous repo, follow the instructions as neccesary. The third section is the same for both.

### From Scratch:
1. Create your repo on github
2. `mkdir <project_name>` inside of your in your PC folder
3. `cd <project_name>`
4. `git init`
5. Copy the ssh link from github.
6. `git remote add origin <paste github url here>`

### From a fork:
1. Fork the respository on github by clicking the fork button at the top of the repo page.
2. Click on the "Clone or download" button and copy the url.
3. In your terminal, type `git clone <paste link here>`


#### The steps listed below are identical for both.
1. `git add .`
2. `git commit -m <commit message here>`
3. `git push origin master`