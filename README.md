# Application Web Design Project

## Student Information
- **Name:** [Raymundo Albarrán Vera]
- **Degree:** [IDS]
- **Semester:** [6th Semester]
- **Subject:** Application Web Design

## What is Markdown?

Markdown is a lightweight markup language created by John Gruber in 2004. It's designed to be easy to read and write, and can be converted to HTML and other formats.

### Common Uses of Markdown:
- **Documentation:** README files, wikis, and technical documentation
- **Web Content:** Blog posts, articles, and website content
- **Notes:** Personal and professional note-taking
- **Formatting:** Simple text formatting without complex HTML
- **Collaboration:** Used in platforms like GitHub, GitLab, and Reddit

## Markdown Tagging Options

### Text Formatting
- **Bold:** `**bold text**` or `__bold text__`
- **Italic:** `*italic text*` or `_italic text_`
- **Bold & Italic:** `***bold and italic***`
- **Strikethrough:** `~~strikethrough text~~`

### Headers
```markdown
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

## Essential Git Commands

**Check Repository Status**
```
git status
```
This command shows the current state of your working directory and staging area, displaying which files are modified, staged, or untracked.

**Add Files to Staging Area**
```
git add <filename>
```
Add a specific file to the staging area. To add all files globally, use:
```
git add .
```

**Commit Changes with Messages**
```
git commit -m "Your commit message here"
```
The `-m` flag allows you to add a commit message describing your changes. For more detailed messages, you can use `git commit` without the flag to open an editor.

**Push Changes to Remote Repository**
```
git push origin <branch-name>
```
This uploads your committed changes to the remote repository. If you're on the main branch, use `git push origin main`.

**Manage Branches**
Create a new branch:
```
git branch <branch-name>
```

Switch to a branch:
```
git checkout <branch-name>
```

List all branches:
```
git branch
```

Delete a branch:
```
git branch -d <branch-name>
```

**Roll Back to a Specific Commit**
```
git reset --hard <commit-hash>
```
This command reverts your repository to a previous commit. Find the commit hash using `git log` to see your commit history.

---