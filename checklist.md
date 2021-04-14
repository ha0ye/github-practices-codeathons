# Getting Started Checklist

## Installation

- [ ] install the [Git software](https://git-scm.com/downloads)
- [ ] install the [GitHub Desktop](https://desktop.github.com/) application (optional)

## Setup

- [ ] configure your [name and email](https://swcarpentry.github.io/git-novice/02-setup/index.html)
- [ ] if you're a command-line user and NOT comfortable with vim, configure an [alternative text editor](https://swcarpentry.github.io/git-novice/02-setup/index.html)

## GitHub Setup

- [ ] create a [GitHub account](https://github.com/join) *use the same email as you configured for git!*
- [ ] claim your [GitHub Student Developer Pack](https://education.github.com/pack/join) (or equivalent if you're not a student)

- [ ] Configure an [SSH Key](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh) for use with GitHub
- [ ] [Connect GitHub Desktop with your GitHub account](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/authenticating-to-github) (optional)

## Workflow (starting with a new or existing local project)

- [ ] Initialize a git repo in the project folder:
  ```bash
  git init
  ```
- [ ] [Add commits](https://rogerdudler.github.io/git-guide#add)
- [ ] [Create a GitHub repo](https://github.com/new) without any initialized files.
- [ ] Connect your local git repo to GitHub
  ```bash
  git remote add origin <server>
  ```
- [ ] [Push local commits to GitHub](https://rogerdudler.github.io/git-guide/#push)

## Workflow (starting with a new GitHub project)

- [ ] [Create a GitHub repo](https://github.com/new) without any initialized files.
- [ ] Clone the empty project to your computer
  ```bash
  git clone <server>
  ```
- [ ] [Add commits](https://rogerdudler.github.io/git-guide#add)
- [ ] [Push local commits to GitHub](https://rogerdudler.github.io/git-guide/#push)

## Workflow (GitHub Flow)

- [ ] Create a local branch
  ```bash
  git checkout -b <branch>
  ```
- [ ] [Add commits](https://rogerdudler.github.io/git-guide#add)
- [ ] Push to GitHub
  ```bash
  git push origin <branch>
  ```
- [ ] Create a pull request on GitHub
- [ ] Approve the pull request to merge the new branch

