# Introduction to Git and GitHub


<!-- README.md is generated from README.qmd. Please edit that file -->

<!-- badges: start -->

<!-- badges: end -->

## Prerequisites

- No prior experience with Git or version control required
- Some experience with R, Python, or other programming language

## Learning outcomes

By the end of the course you should be able to:

- Set up Git on a project
- Link your local git project with an online project on GitHub
- Understand how to use issues to track ideas or problems
- Use branches to manage features or changes
- Basic collaboration workflows (pull requests, merging, merge
  conflicts)
- Work on new ideas and code, without the cocnerns of breaking working
  code
- Collaborate with others without stepping on each other’s toes
- Know how to resolve basic git issues
- Identify when and where bugs are introduced

## Course website

<https://gentle-git.njtierney.com>

## Details

Transparency is key to trust. We have all (almost certainly) used
services like Google Drive, and Dropbox. These services facilitate
collaboration by allowing many people to work on the same documents, and
have them stay in-sync. These systems are similar to the version control
systems of Git, but Git helps you track every change to your code,
understand what changed and why, and work confidently knowing you can
always return to a previous working state. It’s like a “super Google
Drive” or “super Dropbox”. It keeps track of changes, but also does so
much more.

## Schedule

### Version Control Fundamentals

- The what and why of version control
  - Git vs OneDrive/Google Drive/Dropbox
- Concepts, and terminology
  - Repo, commits, branches,
- git vs github
- Installation and setup
  - Git Handshake
  - Setup with git/github
  - Connect to RStudio/Positron/VS code
  - Using `usethis` with git
  - The (many) ways of creating a git repository

### Git Workflow

- Commit Early, commit often
- What makes a good commit
- .gitignore file
- How to write a useful commit message
- How to view commits / commit history
- How to look at differences between commits
- How to go back to another commit
- Public vs private repositories
- Tracking your work in github: Issues, Milestones, Labels, etc

### GitHub and Branching

- Using branches
  - Make changes without breaking code
  - Link every branch to an issue
  - Creating, moving between branches
  - Merging branches and pull requests
  - git hygiene
- Practicing branching
  - Link branch and issue.
  - Resolve issue.
  - using usethis with

### Collaborating with git

- Forking vs branching
- How to code review
- How to “import” someones changes onto your machine
- Merge conflicts
  - What, and why?
  - How to read merge conflicts
  - Resolving conflicts
- Simulating, and practicing conflict resolutions

### Github Actions

- github pages
- using github workflows to automate work
- Linking github with Zenodo

### git: some more technical aspects

- Linking git with an existing project
- Some basic troubleshooting of common errors
- Understanding `git push` and `git pull`
- Push an existing project to GitHub
- git bisect to find bugs
