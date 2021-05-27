# Git Commands


## …or create a new repository on the command line
```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mfrony2003/OnlineShop_MobileApp_Flutter.git
git push -u origin main


```
---
## …or push an existing repository from the command line

```

git remote add origin https://github.com/mfrony2003/OnlineShop_MobileApp_Flutter.git
git branch -M main
git push -u origin main

```
## Change your remote's URL 

---

```
git remote set-url origin git@github.com:USERNAME/REPOSITORY.git

```

## List your existing remotes

```
git remote -v

```
## After chaging remote url Error : Message 'src refspec master does not match any' when pushing commits in Git

```
git commit -m "initial commit"
git push origin master

```

