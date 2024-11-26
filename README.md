# Check Git/GitHub Config

This respository is intended to be used to check a contributor's `git`/GitHub username configuration to ensure that they match. Matching usernames are necessary for ensuring a given contributor's work is tracked correctly.

## Intended use

This repository is intended to be used with the **feature branch workflow**:

1. Clone this repository.
1. Create a new branch.
1. Make a few commits to the branch... the changes made in each commit are not important.
1. Push the new branch to GitHub.
1. Open and approve a pull request so that your feature branch is merged into the `main`/`master` branch.

You will receive an automated email showing the usernames detected for the commits as well as the pull requests. Ensure that these usernames match. If they do not, fix the problem and try again.

- commit usernames come from the `git` configuration.
- pull request usernames come from your GitHub account and profile settings.
