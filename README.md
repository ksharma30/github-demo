
## Git and GitHub Fundamentals Hands-On

### Steps to Get Started with Git and GitHub

1. **Initialize a Git Repository**  
   Run the following command in your project directory to initialize a Git repository:  
   ```bash
   git init
   ```
   This creates a `.git` folder in your project, which tracks changes.

2. **Check the Status of Your Repository**  
   Use the following command to check the current status of your repository:  
   ```bash
   git status
   ```
   This shows untracked, modified, or staged files.

3. **Add Files to Staging Area**  
   Add files to the staging area using:  
   ```bash
   git add <file-name>
   ```
   Or add all files:  
   ```bash
   git add .
   ```

4. **Commit Changes**  
   Save your changes with a commit message:  
   ```bash
   git commit -m "Your commit message"
   ```

5. **Connect to a Remote Repository**  
   Link your local repository to a GitHub repository:  
   ```bash
   git remote add origin <repository-URL>
   ```

6. **Push Changes to GitHub**  
   Push your changes to the remote repository:  
   ```bash
   git push -u origin main
   ```

### Branching in Git

1. **Create a New Branch**  
   Create a new branch to work on a feature or fix:  
   ```bash
   git branch <branch-name>
   ```

2. **Switch to the New Branch**  
   Move to the newly created branch:  
   ```bash
   git checkout <branch-name>
   ```
   Or use:  
   ```bash
   git switch <branch-name>
   ```

3. **Merge Branches**  
   After completing work on a branch, merge it into the main branch:  
   ```bash
   git checkout main
   git merge <branch-name>
   ```

4. **Delete a Branch**  
   Once merged, delete the branch to keep your repository clean:  
   ```bash
   git branch -d <branch-name>
   ```

### GitHub-Specific Steps

1. **Fork a Repository**  
   Fork a repository from another user to your GitHub account using the "Fork" button on GitHub.

2. **Clone a Repository**  
   Clone a repository to your local machine:  
   ```bash
   git clone <repository-URL>
   ```

3. **Create a Pull Request**  
   After pushing changes to your forked repository, create a pull request to propose changes to the original repository.

4. **Resolve Merge Conflicts**  
   If there are conflicts during a pull request or merge, resolve them manually in the conflicting files, then commit the changes.

5. **Collaborate with Issues**  
   Use GitHub Issues to track bugs, enhancements, or tasks. Assign issues to team members and link them to pull requests.

This guide provides a hands-on approach to mastering Git and GitHub fundamentals. Happy coding!
