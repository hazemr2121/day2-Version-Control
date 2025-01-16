# day2-Version-Control

### 1-Make a project deployment.

### 2-what is pull request and request & differrent bettween them?

Pull Request (PR): A pull request is a feature in Git hosting services (like GitHub, GitLab) that allows you to notify others about changes you've pushed to a branch in a repository. Once a pull request is opened, reviewers can discuss and review the potential changes before merging them into the main branch.

Request: This term is a bit vague, but it could refer to a general request for changes or updates in a project, not necessarily tied to a specific Git feature.

Difference: A pull request is a specific Git feature for code review and merging, while a request could be any general request for changes or updates.

### 3-Make fork from your project and use it from anthor account

### 4-What is the command to delete the branch "new-email"

`git branch -d new-email`
`git push origin --delete new-email`

### 5-What is the command to push the current repository to the remote origin?

`git push origin <branch-name>`

### 6-what is git Rebase and how to use it ?

**Git Rebase** is a command that allows you to move or combine a sequence of commits to a new base commit.
`git checkout feature-branch`
`git rebase main`

### 7-What is the command to get all the change history of the remote repository "origin"?

`git fetch origin`

### 8-What is the command to show the differences between the current branch and the branch "new-email"?

`git diff new-email`

### 9-what is tags and Make five tags and release two of them?

`git tag v1.0.0`
`git tag v2.0.0`
`git tag v3.0.0`
`git tag v4.0.0`
`git tag v5.0.0`

`git push origin --tags`

### Bouns :

### Make SSh to your repo.
