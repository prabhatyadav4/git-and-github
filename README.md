# 🌿 Git & GitHub Mastery

> A hands-on learning repository documenting my complete journey through Git version control and GitHub collaboration — from `git init` to production workflows.

[![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com)
[![Commands Mastered](https://img.shields.io/badge/Commands-50%2B-success)](https://github.com/prabhatyadav4/git-and-github)

---

## 📋 Table of Contents

- [About This Repository](#-about-this-repository)
- [What's Inside](#-whats-inside)
- [Learning Journey](#-learning-journey)
- [Command Reference](#-command-reference)
- [Key Concepts Mastered](#-key-concepts-mastered)
- [Practice Files](#-practice-files)
- [Resources](#-resources)
- [Connect](#-connect)

---

## 🎯 About This Repository

This repository is a **living learning lab** where I practiced and mastered Git & GitHub. Every file and folder here represents hands-on experimentation with version control concepts. This isn't a polished project — it's a learning playground that captures the messy, iterative process of truly understanding Git.

### 🎓 Learning Source

**Tutorial:** [Git & GitHub Complete Course](https://youtu.be/MuZySo5lF8E?si=2Px6zQleeomYgJYe)

**Why This Repo Exists:**
- 📚 Document my Git learning journey
- 🔬 Experimental space for practicing commands
- 📝 Personal reference for Git workflows
- 🎯 Demonstrate hands-on learning approach

> **Note:** Files and folders here were created solely for practicing Git commands. They're intentionally simple to keep the focus on version control, not code complexity.

---

## 📦 What's Inside

This repository contains:

- ✅ **Practice files** used to test Git commands
- ✅ **Experimental branches** for understanding branching workflows
- ✅ **Commit history** showing real learning progression
- ✅ **Merge scenarios** for conflict resolution practice
- ✅ **Stash experiments** for understanding temporary storage
- ✅ **.gitignore examples** for file exclusion patterns

**Everything here is a learning artifact!** 🎨

---

## 🚀 Learning Journey

### Phase 1: Git Fundamentals ✅
**Mastered:** Repository initialization, staging, and committing

```bash
git init                    # Initialize repository
git add <file>             # Stage changes
git commit -m "message"    # Commit changes
git status                 # Check status
git log                    # View history
```

### Phase 2: Advanced Commits ✅
**Mastered:** Commit manipulation and history management

```bash
git commit --amend         # Modify last commit
git reset --soft/mixed/hard # Undo commits
git revert <commit_id>     # Safe undo
git log --pretty=oneline   # Custom log views
```

### Phase 3: Branching & Merging ✅
**Mastered:** Parallel development and integration

```bash
git branch <name>          # Create branch
git checkout/switch        # Switch branches
git merge <branch>         # Merge branches
git cherry-pick            # Selective commits
```

### Phase 4: Remote Collaboration ✅
**Mastered:** GitHub integration and team workflows

```bash
git remote add origin      # Link remote
git push -u origin main    # Push changes
git pull origin main       # Fetch & merge
git fetch --prune          # Clean remote tracking
git clone                  # Copy repository
```

### Phase 5: Advanced Workflows ✅
**Mastered:** Stashing and file management

```bash
git stash                  # Save work temporarily
git stash apply            # Restore stashed work
.gitignore                 # Exclude files
```

---

## 📚 Command Reference

### 🔧 Setup & Configuration

| Command | Purpose |
|---------|---------|
| `git` | Verify Git installation |
| `git -v` | Check Git version |
| `git init` | Initialize repository |
| `git init --initial-branch=main` | Initialize with custom branch |

### 📂 File Operations

| Command | Purpose |
|---------|---------|
| `nano <file>` | Create/edit file |
| `touch <file>` | Create empty file |
| `ls -al` | List all files (including hidden) |
| `rm -rf .git/` | Remove Git repository |

### 📊 Status & Inspection

| Command | Purpose |
|---------|---------|
| `git status` | Check repository status |
| `git status -v` | Verbose status |
| `git status -s` | Short status |
| `git log` | View commit history |
| `git log -n 2` | Show last 2 commits |
| `git log -p` | Show changes in commits |
| `git log --pretty=short/full/fuller/oneline` | Format log output |
| `git log --pretty=format:"%h %s %an %ae"` | Custom log format |
| `git log --since="1 week ago"` | Time-based filtering |
| `git log --since="2025-01-01" --until="2025-12-31"` | Date range filtering |
| `git log --author="name"` | Filter by author |
| `git log --grep="keyword"` | Search commit messages |

### ➕ Staging & Committing

| Command | Purpose |
|---------|---------|
| `git add <file>` | Stage specific file |
| `git add .` | Stage all changes |
| `git rm --cached <file>` | Unstage file |
| `git commit` | Commit with editor |
| `git commit -m "message"` | Commit with inline message |
| `git commit -a -m "message"` | Stage & commit tracked files |
| `git commit --amend` | Modify last commit |
| `git commit --amend --no-edit` | Amend without changing message |
| `git commit -s -m "message"` | Signed commit |
| `git commit --allow-empty -m "message"` | Empty commit |

### ⏮️ Undoing Changes

| Command | Purpose |
|---------|---------|
| `git reset --soft <commit_id>` | Undo commit, keep changes staged |
| `git reset --mixed <commit_id>` | Undo commit & staging |
| `git reset --hard <commit_id>` | Undo commit & discard changes |
| `git revert <commit_id>` | Create new commit that undoes changes |

### 🌿 Branching & Merging

| Command | Purpose |
|---------|---------|
| `git branch` | List branches |
| `git branch <name>` | Create branch |
| `git branch -d <name>` | Delete branch |
| `git branch -r` | List remote branches |
| `git checkout <branch>` | Switch to branch |
| `git switch <branch>` | Modern branch switching |
| `git merge <branch>` | Merge branch into current |
| `git cherry-pick <commit_id>` | Apply specific commit |

### 🌐 Remote Operations

| Command | Purpose |
|---------|---------|
| `git remote` | List remotes |
| `git remote add origin <url>` | Add remote repository |
| `git push -u origin main` | Push & set upstream |
| `git push` | Push changes |
| `git pull origin main` | Fetch & merge |
| `git pull origin main --allow-unrelated-histories` | Force merge unrelated repos |
| `git fetch` | Download remote changes |
| `git fetch --prune` | Remove stale remote branches |
| `git fetch --all` | Fetch from all remotes |
| `git fetch origin <branch>` | Fetch specific branch |
| `git clone <url>` | Copy remote repository |

### 💾 Stashing

| Command | Purpose |
|---------|---------|
| `git stash` | Save changes temporarily |
| `git stash list` | List all stashes |
| `git stash apply <stash_id>` | Apply specific stash |
| `git stash clear` | Delete all stashes |

### 🚫 File Management

| Command | Purpose |
|---------|---------|
| `.gitignore` | File to specify ignored files |
| `find . -name ".git" -type d -exec rm -rf {}` | Remove all nested .git folders |

---

## 🧠 Key Concepts Mastered

### 1. **Three-Stage Architecture**
```
Working Directory → Staging Area → Repository
     (add)              (commit)
```

### 2. **Commit States**
- `--soft`: Undo commit, keep staging
- `--mixed`: Undo commit & staging (default)
- `--hard`: Undo everything

### 3. **Branch Workflows**
- Creating feature branches
- Merging strategies
- Resolving conflicts
- Cherry-picking commits

### 4. **Remote Collaboration**
- Push/pull workflows
- Fetch vs pull differences
- Tracking remote branches
- Handling merge conflicts

### 5. **Stashing Strategy**
- Temporary work storage
- Switching contexts
- Stash management

---

## 📁 Practice Files

The files in this repository are intentionally simple because:

✅ **Focus on Git, not code** — Simple files keep attention on version control  
✅ **Easy to track changes** — Text files clearly show diffs  
✅ **Quick experimentation** — Create/modify files rapidly  
✅ **Clear commit history** — Each change is obvious  

**Common Practice Files:**
- `f1.txt`, `f2.txt` — Basic text files for staging practice
- `test.txt` — File operations and commits
- Various folders — Directory structure experiments

> These aren't meant to be impressive code — they're learning tools! 🎓

---

## 📊 Progress Stats

```
✅ 50+ Git Commands Mastered
✅ 5 Major Learning Phases Completed
✅ Branching & Merging: Proficient
✅ Remote Workflows: Confident
✅ Advanced Operations: Comfortable
```

---

## 🎯 What I Can Do Now

- ✅ Initialize and manage Git repositories
- ✅ Track changes and maintain commit history
- ✅ Create and merge branches effectively
- ✅ Collaborate on GitHub projects
- ✅ Handle merge conflicts
- ✅ Undo mistakes safely (reset, revert)
- ✅ Use stash for context switching
- ✅ Configure .gitignore for projects
- ✅ Work with remote repositories
- ✅ Cherry-pick specific commits

---

## 📚 Resources

### Tutorial Used
🎥 **[Git & GitHub Complete Course](https://youtu.be/MuZySo5lF8E?si=2Px6zQleeomYgJYe)**

### Additional Resources
- 📖 [Official Git Documentation](https://git-scm.com/doc)
- 📘 [GitHub Docs](https://docs.github.com)
- 🎮 [Learn Git Branching (Interactive)](https://learngitbranching.js.org/)
- 📝 [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

---

## 🎓 Learning Philosophy

This repository embodies my approach to learning:

1. **Learn by Doing** — Theory is good, practice is better
2. **Document Everything** — Future me will thank present me
3. **Embrace Mistakes** — Git lets you experiment safely
4. **Build Progressively** — Master basics before advanced topics
5. **Share Knowledge** — This repo might help someone else

---

## 🚀 Next Steps

- [ ] Explore Git hooks
- [ ] Practice rebase workflows
- [ ] Learn Git submodules
- [ ] Contribute to open-source projects
- [ ] Master GitHub Actions

---

## 👨‍💻 Connect

**Prabhat Kumar**  
Computer Science Engineering Student | Git & Version Control Enthusiast

- 📧 Email: osrprabhatyadav4@gmail.com
- 💼 LinkedIn: [Prabhat Kumar](https://www.linkedin.com/in/prabhat-kumar-95059531a)
- 🐙 GitHub: [@prabhatyadav4](https://github.com/prabhatyadav4)

---

## 💡 Final Thoughts

> "Git is not just a tool — it's a time machine, a safety net, and a collaboration superpower rolled into one."

This repository proves that **learning in public** and **documenting the journey** creates value beyond just personal growth. If you're learning Git, remember: every expert was once a beginner who kept practicing.

---

<div align="center">
  <sub>Built through practice, mistakes, and persistence 🌿</sub>
</div>
