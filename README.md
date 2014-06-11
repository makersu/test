#test git

```
git config --global user.name "Maker Su"
git config --global user.email "makersu@gmail.com"
git config --global --list
```
```
find . -type d -empty -exec touch {}/.gitignore \;
```
```
git add . (stages new and modified, without deleted)
git add -u (stages modified and deleted, without new)
git add -A (stages All)

git status
git reset README.md
git reset HEAD^
git reset HEAD^ README.md 
git log
git diff HEAD^^ HEAD main.c

git commit -a (stages modified but not new)
git commit -m "add after create-app"
git push
```

#mongodb

##couldn't connect to server 127.0.0.1 shell/mongo.js:84

```
sudo rm /var/lib/mongodb/mongod.lock
sudo -u mongodb mongod -f /etc/mongodb.conf --repair
```
