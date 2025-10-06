# 🧠 Git & GitHub Setup

This simple guide explains how to set up and use a Git repository.

---

## ⚙️ 1. Clone the repository

```bash
git clone https://github.com/robertvizvari/mip_clanok.git
cd mip_clanok
```

---

## 🔄 2. Pull the latest changes

```bash
git pull
# or for a specific branch
git pull origin main
```

---

## 🌿 3. Create a new branch

```bash
git checkout -b branch_name
```

Switch between branches:

```bash
git checkout main
```

List all branches:

```bash
git branch
```

---

## ✏️ 4. Commit your changes

```bash
git status          # check changes
git add .            # add all changes
git commit -m "describe your changes"
```

---

## 🚀 5. Push changes to GitHub

```bash
git push origin branch_name
```
