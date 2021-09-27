# Commits

- Imperative
- One sentence
- Human instructions for your program

## Good Examples

- "Respond with session cookie on login"
- "Control user log in form"
- "initial commit" - right when you start your project

## Bad examples

- "Done"
- "jsldkfjsdlkfjsdlkfjlsdjflskdjflksdj"
- "Why won't this work?"

^While this may seem harmless, remember that employers will look at your repository (which displays your last commit for every folder), and sometimes even your commit history.

Further Reading: Conventional Commits - https://www.conventionalcommits.org/en/v1.0.0-beta.2/ 

# Branching

## Workflow

- Developer checks out a user story, github issue, trello card, etc.
- Developer plans a solution to solve that issue
- Developer creates a new branch to match that feature.
- Developer implements that feature on the new branch
- Developer pushes branch to github and opens a pull request
- Several developers review the code and changes. 
    - If changes need to be made, they will be noted and developer will make them
- Developer will squash commits and merge branch into production
- Developer repeats process on the next feature



## Commands

- git branch - shows all branches and current branch
- git checkout branch-name - switches to an already existing branch
- git checkout -b branch-name - switches to a new branch
- git merge branch-name - merges the specified branch name into your current branch
- git rebase branch name - rebases the specified branch into your current branch

## Rebasing vs Merging

- Merging places the incoming commits at the end of the commit history
- Rebasing places the incoming commits at the beginning of the commit history

Generally:
- Rebase the main/master branch into feature branches if updates have been made
- Merge and squash the feature branch into the main/master branch when the PR has been approved

# User Stories

"A user story is an informal, general explanation of a software feature written from the perspective of the end user. Its purpose is to articulate how a software feature will provide value to the customer."

"A user story is the smallest unit of work in an agile framework. It’s an end goal, not a feature, expressed from the software user’s perspective."

“As a [persona], I [want to], [so that].”

Atlassian 

Further reading: https://www.atlassian.com/agile/project-management/user-stories 

## Examples

Good:
- As a user, I want to be able to log in so that I can use this service
- As an administrator, I want to delete anyone's posts to keep the site within our conduct guidelines
- As Max, I want to post pictures so that I can tell people about myself

Bad:
- As a user, I want to log in, post pictures, delete pictures, and listen to music on this platform, so that I can enjoy the platform.
- As a user, I want to be able to type into an input box type="password" my password, so that I can log in.

## Workflow

- Development team breaks up current sprint objectives into user stories
- Developers pick user stories to work on for the sprint
- Developers work on those stories one at a time
- Developers plan out how they will approach that story
- Developers use the branching workflow noted above for each story.
- Development team deploys the code at the end of the sprint

