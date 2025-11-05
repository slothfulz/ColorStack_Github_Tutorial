# 🚀 GitHub Crash Course: First PR Challenge

Welcome to our hands-on GitHub tutorial! Your mission is to add your team name and a fun fact to `scoreboard.md` and be the first team to get your pull request merged. Let's get started!

---

## 📋 Prerequisites

Before you begin, make sure you have:
- A GitHub account
- Git installed on your machine ([Download here](https://git-scm.com/downloads))
- A code editor (VS Code recommended, but any editor works!)

---

## 🎯 Challenge Steps

### Step 1: Fork This Repository

Click the **Fork** button at the top right of this repository. This creates a copy of the repository in your own GitHub account that you can freely edit.

> 💡 **Think of this like:** Making a copy of a Google Doc that you don't have edit permissions for.

---

### Step 2: Clone Your Fork to Your Local Machine

Open your terminal and run:

```bash
git clone https://github.com/YOUR-USERNAME/ColorStack_Github_Tutorial.git
```

Replace `YOUR-USERNAME` with your actual GitHub username.

Then navigate into the project directory:

```bash
cd ColorStack_Github_Tutorial
```

---

### Step 3: Create a New Branch

Create and switch to a new branch with your team name:

```bash
git checkout -b team-<your-team-name>
```

**Example:** `git checkout -b team-taco`

> 💡 **Why branches?** Branches let you work on changes without affecting the main code. It's like creating a draft version of your work.

---

### Step 4: Edit `scoreboard.md`

Add your team's entry to the scoreboard file. You have two options:

#### Option A: Using VS Code (or another editor)
1. Open the project folder in VS Code
2. Find and open `scoreboard.md`
3. Add a new line with your team name and fun fact
4. Save the file (Cmd/Ctrl + S)

#### Option B: Using Vim in Terminal
```bash
vim scoreboard.md
```
- Press `i` to enter insert mode
- Add your team's line
- Press `Esc`, then type `:wq` and press Enter to save and quit

**Format your entry like this:**
```
- Team Taco: We once ate 47 tacos in one sitting! 🌮
```

---

### Step 5: Commit and Push Your Changes

Now it's time to save and upload your changes using the standard Git workflow:

#### a. Stage your changes
```bash
git add .
```
This adds all your changes to the staging area (preparing them for commit).

#### b. Commit your changes
```bash
git commit -m "Add Team <your-team-name> to scoreboard"
```
**Example:** `git commit -m "Add Team Taco to scoreboard"`

Every commit needs a descriptive message explaining what you changed.

#### c. Push to your fork
```bash
git push origin team-<your-team-name>
```
This uploads your branch to your GitHub fork.

---

### Step 6: Create a Pull Request

1. Go to your fork on GitHub
2. You should see a banner suggesting you create a Pull Request - click **Compare & pull request**
3. Add a title and description for your PR
4. Click **Create pull request**

🎉 **Congratulations!** You've just created your first pull request!

---

## 🏆 First Team to Get Merged Wins!

The race is on! May the fastest team win! 🚀

---

## ❓ Common Issues & Solutions

**Problem:** `git push` asks for a username and password  
**Solution:** You may need to set up SSH keys or use a personal access token. [GitHub's authentication guide](https://docs.github.com/en/authentication)

**Problem:** Merge conflicts  
**Solution:** Don't worry! Your instructor will help you resolve these.

**Problem:** "Permission denied" when pushing  
**Solution:** Make sure you're pushing to your fork, not the original repository.

---

## 📚 Helpful Git Commands

- `git status` - Check what files have been changed
- `git log` - View your commit history
- `git branch` - See all branches
- `git pull` - Get the latest changes from remote

---

## 🤝 Need Help?

Raise your hand or ask in the chat - we're here to help you succeed!

Happy coding! 💻✨
