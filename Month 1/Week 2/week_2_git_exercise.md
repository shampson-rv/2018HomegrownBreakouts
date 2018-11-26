# Homegrown Breakout Week 2 - Git Commands

In this exercise you will create a readme file in markdown, push it to a new public repo on github, and commit a couple of changes. [This GitHub article](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/) outlines the process.

## Step 1 - create the directory `practice_repo` to use as your local repo
This could be in your Documents or root directory. This represents a working directory on your computer where you've been writing code but haven't implemented version control yet.

## Step 2 - create README.md in `practice_repo`
Here we'll create a markdown file that will have an H1 title "README: [your name] Git Practice", and below that in plain text, the date and time of creation. You can access the R Markdown cheatsheet in R Studio via Help > Cheatsheets > R Markdown Cheatsheet.

A markdown file is just a plain text file with the extension .md. GitHub will display such files with the html formatting you intend, which makes them great for READMEs.

You can write your README in any text editor that can save a .txt file, R file, or Rmd file. (Easiest with something like Sublime Text or MS Notepad, but you can also use R Studio). For the purpose of this exercise, if you save your README as .R or .rmd, you can simply rename the extension to .md and it will display on GitHub. We'll cover .rmd (R Markdown) in more detail later.

## Step 3 - initialize `practice_repo` as a local Git repo
Navigate to your `practice_repo` directory in git bash or Terminal (not Windows Command Prompt). Use the appropriate `git` command to initialize version control on the directory.

## Step 4 - add changes to stage your document
Use the appropriate `git` command to add your changes (i.e. the creation of your readme) so they are staged in your new repo.

## Step 5 - commit your changes
Use the appropriate `git` command to commit your changes, and be sure to include a commit message.

A best practice is to phrase commit messages as an imperative command in present tense. For example:
`"create initial commit with readme"`.

## Step 6 - create a corresponding `practice_repo` on your own public GitHub

Do this WITHOUT creating a new readme. We want a completely empty repo, so when we push our commit we won't encounter any conflicts. You'll almost always name your local and remote repos identically ("`practice_repo`"), although it is possible to do otherwise.

## Step 7 - set your GitHub repo as the remote repo for your local repo

With your terminal in the `practice_repo` directory, use the command `git remote add origin git@github.com:user/repo_name.git` (substituting the appropriate URL). You'll notice this command is available for you to copy straight from the results page once you've created your GitHub repo.

## Step 8 - push your local repo up to remote

You can try a simple `git push`. Git will tell you that you need to set an upstream branch and will suggest the code to set the master branch of your GitHub repo as the upstream version of your local master branch. You'll only have to do this once. Go ahead and use the recommended command.

Now if you check GitHub, your README.md file should have appeared.

## Step 9 - make a change to your local README and push it up to GitHub

Add a comment below the date indicating that you've made a change and at what time you made it. Use the appropriate git commands to stage (add) and commit the change to your local repo (always include a message), then push the change to remote.

## Step 10 - make a second change and push it up to GitHub

Add another comment and the time. Your Readme should now have 3 times added. Add, commit and push the change. Notice that you can view your repo in GitHub, click on the number of commits, and see 3 separate commits. Click on a commit to see the state of your Readme at that point in your version control history. Red sections indicate removals and green sections show additions. ([My example.](https://github.com/chrissirico/practice_repo/commits/master))

Congratulations! 👏👏👏  

These commands account for 80% of the git you'll need to use on a regular basis. We'll explore collaborating through git with creating new branches, pull requests, and merges later in the accelerator.