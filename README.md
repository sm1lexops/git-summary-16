## Finall task in GIT section by Rebrain

```
git config --global -l #show ~/.gitconfig file

```

# Tips in this task

```
mkdir git-summary-16 && cd git-summary-16
git init
echo "# repeat text" >> README.md
git add README.md
git commit -m "Add README.md file in repo"
echo "# some change to README.md" > README.md
git add .
git commit -m "change README.md file in repo"
git checkout -b develop
git checkout -b feature
```
