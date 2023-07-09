## What is GitHub Authentication?

GitHub authentication is a process that verifies the identity of users accessing GitHub services. It ensures secure interactions by confirming user credentials, such as usernames and passwords, or using more advanced authentication methods like SSH keys or OAuth tokens. Authentication safeguards user accounts and allows for authorized access to repositories and collaborative features on GitHub.

<br />

| GitHub Authentication Methods | |
| -------------------- | --------------------|
| Username and Password | The traditional method where users provide their username and password to access their GitHub account. |
| Personal Access Tokens (PATs) | PATs are alternative credentials that can be used instead of passwords. They offer scoped access to specific GitHub resources and can be generated and managed within a user's GitHub account settings. | 
| SSH Keys | Secure Shell (SSH) keys provide a secure and convenient way to authenticate with GitHub. Users can generate an SSH key pair and associate the public key with their GitHub account. |
| OAuth | GitHub supports OAuth authentication, allowing users to authenticate using third-party applications or services that integrate with GitHub. This method enables single sign-on (SSO) and enhances security by not sharing the user's actual GitHub credentials with the third-party application.
| GitHub Apps | GitHub Apps are another method of authentication that allows third-party applications to access GitHub on behalf of a user or organization. They offer granular permissions and can be installed on specific repositories or organizations.
<br />

These authentication methods provide users with flexibility and security options based on their specific needs and preferences when interacting with GitHub services.

<br />

## Commonly Used GitHub Commands

| Command         | Description                                   |
| --------------- | --------------------------------------------- |
| `git clone`     | Clone a repository from GitHub to your local machine. |
| `git init`      | Initialize a new Git repository locally.       |
| `git add`       | Stage changes or new files to be committed.    |
| `git commit`    | Create a new commit with staged changes.       |
| `git push`      | Push local commits to a remote repository on GitHub. |
| `git pull`      | Fetch and merge changes from a remote repository. |
| `git branch`    | List, create, or delete branches.              |
| `git checkout`  | Switch branches or restore files from a specific commit or branch. |
| `git merge`     | Merge changes from one branch into another.     |
| `git status`    | Show the status of files in the repository.     |
| `git log`       | Display the commit history.                    |
| `git remote`    | Manage remote repositories.                    |
| `git fetch`     | Retrieve changes from a remote repository without merging. |
| `git reset`     | Undo changes or move the head to a different commit. |
| `git stash`     | Temporarily save changes that are not ready to be committed. |

These commands are frequently used in Git and GitHub workflows to manage version control, collaboration, and repository management.

<br />

## In a real project, the four GitHub commands that are commonly used are:

1. `git clone`: This command is essential when starting a new project or when collaborating with others. It allows you to clone an existing repository from GitHub to your local machine, providing you with a complete copy of the project's codebase to work with.

2. `git add` and `git commit`: These commands go hand in hand and are used frequently to save your changes in the local repository. By staging changes with `git add` and then committing them with `git commit`, you create a new revision in the repository, making it easy to track and manage your progress.

3. `git push`: Once you have committed your changes locally, `git push` is used to upload those commits to the remote repository on GitHub. This command enables you to share your work with others, collaborate, and keep the remote repository up to date.

4. `git pull`: When collaborating with a team or working on a project with multiple contributors, `git pull` is frequently used to fetch and merge the latest changes from the remote repository into your local branch. This ensures that your local copy is synchronized with the most recent updates made by others.

These four commands—`git clone`, `git add` and `git commit`, `git push`, and `git pull`—form the foundation of collaboration, version control, and project management when working with Git and GitHub in real projects.
