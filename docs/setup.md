---
title: Opensource coursekit tool chain setup guide
marp: true
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---

# **Tool Chain Introduction**

## 1. Git & Github

## 2. VSCode

## 3. Markdown

## 4. Warp for VSCode

---

# **Git Introduction**
<style scoped>
li {
    font-size: 25px;
}
</style>
- What is Git?
  - Git is a free and open-source source control management (SCM) system.
  - It is a distributed version control system for tracking changes in source code.
  - Git's primary function is to track changes to files over time, allowing users to revert to previous versions and compare differences.

- Why Use Git?
  - Manage changes to files: Git allows you to see who changed what and compare different versions.
  - Revert to previous versions: If you make a mistake, you can jump back to a previous version.
  - Experiment safely: Use branches to work on new features or fixes without affecting the main code.
  - Track project history: Git keeps a record of all changes made, creating a project history.

---

- Key Git Concepts
  - Repository (Repo): A storage location for source code, documentation, and other files with all its history. Represented by the hidden .git folder.
  - Commit: A snapshot of a repository at a specific point in time, creating a record of changes made.
  - Branch: A parallel version of a project's code, allowing developers to work on features or fixes without affecting the main code.
  - Staging: A transitional area where changes are prepared to be included in the next commit.
  - Working Directory: The area where you make edits to your files.

---

# **Github Introduction**
<style scoped>
li {
    font-size: 25px;
}
</style>
- What is GitHub?
  - GitHub is a web-based platform for version control and collaboration using Git.
  - It provides cloud hosting for Git repositories.
  - It offers tools for project management, issue tracking, and code review.

- Key GitHub Features
  - Remote Repositories: GitHub hosts repositories that can be accessed by multiple users.
  - Collaboration: GitHub facilitates collaboration through features like issues, pull requests, and project management tools.
  - Issues: Used to track feature requests, bug reports, or questions related to a project.
  - Pull Requests: A request to merge changes from one branch into another, often used in collaborative workflows.

---
<style scoped>
li {
    font-size: 25px;
}
</style>
- Connecting Local Git to GitHub
  - Create a Repository on GitHub: Set up a new repository on GitHub.
  - Add Remote: Connect your local repo to a remote GitHub repo with the command git remote add origin <github_repo_URL>.
  - Set Main Branch: Set the target branch to main using git branch -M main.
  - Push to GitHub: Push your local repo to the remote with the command git push -u origin main. git push --all will push all branches to GitHub.

- Working with GitHub
  - Making Changes: Edit files directly on GitHub or make changes locally and push them.
  - Downloading Changes: Use git fetch to download all the remote history or git pull to download all remote history and merge it with local files.
  - Collaboration: Use issues and pull requests to manage changes and collaborate with others.
  - Releases: Create releases to mark specific versions of your project.
