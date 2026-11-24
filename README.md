#Assignment5- Git and GitHub

##About me
- **Name:** Hanna Marazevich
- **Date:** November 24, 2026
- **University:** Jagiellonian University
- **Field of Study:** Bioinformatics
- **Year:** Second year

## About this repository

This repository was created as part of an assignment to learn
the basics of Git and GitHub.

## Git - My Personal Cheat Sheet

### 1. What is Git?

Git is a version control system that helps us track changes
in files and keep a history of our work.

Git is especially useful when working on scientific projects,
because we can see what was changed, when and by whom.

### 2. Git vs GitHub

- **Git** is a tool that tracks changes locally on our computer
- **GitHub** is an online platform where we can store and share Git repositories
- Git can work without GitHub, but GitHub makes collaboration easier

### 3. Basic Git Commands

- `git init` - creates a new local repository
- `git clone URL` - downloads a repository to our computer
- `git status` - shows which files have been changed
- `git add filename` - adds a file to the staging area
- `git add .` - stages all changes in the current directory and below
- `git commit -m "message"` - saves staged changes with a description
- `git push` - uploads local commits to a remote repository
- `git pull` - downloads and integrates changes from a remote repository
- `git log` - shows the history of commits

### 4. The Basic Git Workflow

1. Create or modify files
2. Check the changes using `git status`
3. Stage the necessary files using `git add`
4. Save the changes using `git commit`
5. Upload the commits to GitHub using `git push`

**Important:** `git add`, `git commit` and `git push` are different
steps. Adding a file does not automatically create a commit,
and creating a commit does not automatically upload it to GitHub.

### 5. Branches

A branch is an independent line of development.

Branches allow us to work on new features or experiments
without changing the main version of the project.

Useful commands:

- `git branch` - shows local branches
- `git switch -c new-branch` - creates and switches to a new branch
- `git switch main` - switches back to the main branch

### 6. Merging

Merging combines changes from different branches.

For example:

1. Create a new branch to work on a feature
2. Make changes and commit them
3. Switch back to the main branch using `git switch main`
4. Run `git merge new-branch`

### 7. Things to Remember

- Always check `git status` before committing
- Write clear and meaningful commit messages
- Commit regularly to keep track of changes
- Use branches when working on new features
- Pull the latest changes before starting collaborative work
