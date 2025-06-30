# 🔐 GitHub Repo Read Access Lister

This Bash script uses the GitHub API to list all users who have **read access** (pull permission) to a specified repository.

## 🚀 Features
- Authenticates using GitHub username and personal access token
- Lists collaborators with read (pull) access
- Simple and lightweight

## 🛠 Requirements
- `curl`
- `jq`

## ⚙️ Usage

1. Set your GitHub credentials:
   ```bash
   export username="your_github_username"
   export token="your_personal_access_token"
2.Run the script:
  ```bash
   ./script.sh <repo_owner> <repo_name>
```
## 📦 Example
```bash
  ./script.sh octocat Hello-World
```
## 📄 Output
```bash
   python-repl
   Users with read access to octocat/Hello-World:
   user1
   user2
```
