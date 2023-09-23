---

---

## Git and GitHub

Welcome to the world of version control and collaboration with Git and GitHub! This guide will help you get started with the basics of Git and GitHub. Whether you're a beginner or just need a refresher, we've got you covered.

### 1. What is Git?

**Git** is a version control system that helps you track changes in your code and collaborate with others. It allows you to:

- Keep a history of changes.
- Work on different features or fixes simultaneously.
- Easily merge changes made by you or your team.

### 2. What is GitHub?

**GitHub** is a web-based platform built on top of Git. It provides a place to store your code and collaborate with others. Key features include:

- Repositories: Folders to store your code.
- Pull Requests: Propose changes and collaborate with others.
- Issues: Track and manage tasks, bugs, and discussions.

### 3. Setting Up Git

#### Install Git

- **Windows**: Download and install Git from [Git for Windows](https://gitforwindows.org/).
- **Mac**: Git should be pre-installed, but you can update it using [Homebrew](https://brew.sh/): `brew install git`.
- **Linux**: Use your package manager (e.g., `apt`, `yum`, or `dnf`) to install Git.

#### Configure Git

Open a terminal and configure Git with your name and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

### 4. Basic Git Commands

- **Clone**: Download a repository from GitHub.
    `git clone <repository_url>`

- **Add**: Stage changes for commit.
    `git add <file_name>`

- **Commit**: Save changes with a message.
    `git commit -m "Your commit message"`

- **Push**: Upload changes to GitHub.
    `git push`

- **Pull**: Update your local code with changes from GitHub.
    `git pull`

- **Status**: Check the status of your repository.
    `git status`

### 5. Create a Pull Request

1. Make changes in your local repository.
2. Commit those changes.
3. Push the changes to GitHub.
4. Go to your repository on GitHub.
5. Click "New Pull Request."
6. Follow the instructions to create a pull request.

### 6. Common Workflow

1. **Clone** a repository to your local machine.
2. **Create** a new branch for your feature or bug fix.
3. **Add**, **commit**, and **push** your changes.
4. Create a **pull request** on GitHub.
5. **Review** and **collaborate** on the pull request.
6. **Merge** the pull request once it's ready.

### 7. Tips and Best Practices

- Keep your commits small and focused on a single task.
- Write clear and informative commit messages.
	- Example commit message: `feat: implement statistics API route`
		- This would describe that you created a feature in which you implemented an API route that involves statistics
	- Other possible categories for commit message and branches:
		- `feat`, `refactor`, `fix`, `docs`, `chore`, etc
- Pull the latest changes from the main branch before starting your work.
- Communicate with your team through issues and pull requests.

Congratulations! You've completed the Git and GitHub basics. Remember, practice makes perfect, so keep working with Git and GitHub to become more proficient. Happy coding!