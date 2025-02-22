# gabs.py actual change
<h1 align="center">Small tutorial for Gabs</h1>
<h3 align="center">For Git teaching purposes</h3>
<h6 align="center">Small code on Python so we can fork and merge</h6>

### First of all, are your credentials in VS Code already set? 

1.- Check your data by writing on the terminal:
```
$ git config --global --list #email and name will appear together
$ git config --global user.email #exclusively for email
$ git config --global user.name #exclusively for username
```
2.- Do you have corrections to make? Change your email and username so they match your Github info, and your repo gets updated on every commit:
```
$ git config --global user.email yournew@email.com
$ git config --global user.name yournewgoodname
```

- Check [this tutorial](https://4geeksacademy.github.io/git-interactive-tutorial/) for the most common commands:
```
$ git add
$ git commit #add -m "message here" if you wanna add a message
$ git push
$ git pull
$ git merge #useful when working with forks
```

- Make sure you got GitHub Pull Request and Issues extension on VS Code, as well

### Let's fork! 

* Click `Fork` on this page and create your own fork off this repo

* Once it's ready, enter VS Code and press `Control + Shift + P`. Then, select `Git: Clone` and find your fork. Select a folder to store the files, and should be ready to go

* Try making some changes on the `testing.py` file and then commit them:
```
$ git add . #adds every file
$ git commit -m "your message here"
$ git push
```
Keep in mind, these changes are staged to your own repo! not the main one

### Wanna try merging?
* First, make sure there are no changes made before you try, and solve any issues that may appear:
```
$ git pull
```

* Then, merge your branch with the main one:
```
$ git merge
```
Now, your changes will appear on the main branch, and not just your fork!

### Any doubts? You can always check the [Git Documentation on Branches](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging) to find more info, or the [set up Git](https://docs.github.com/en/get-started/quickstart/set-up-git) page on GitHub Docs. Here's a list on [10 Git tutorials for beginners](https://www.webfx.com/blog/web-design/git-tutorials-beginners/), and here's a specific page for [Learning Git Branching](https://learngitbranching.js.org/).
### Happy commit!
