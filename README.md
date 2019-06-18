
# git remote err

## error: The requested URL returned error: 403 Forbidden while accessing ....


```
//check your remote url
git remote -v

// Change Remote URL
git remote set-url origin https://YOURUSERNAME@github.com/USERNAME/REPOSITORY.git

// err msg: [rejected] master -> master (non-fast-forward)
git pull origin master --allow-unrelated-histories
```
