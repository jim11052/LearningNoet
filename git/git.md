### Sign last commit 
```sh
$ git commit --amend --signoff
```

### Submodule
```sh
$ git submodule update --init --recursive
```

### Improve large repo `git clone` speed
```sh
$ git clone <url> --depth 1 --single-branch
$ git clone <url> --depth 1 --no-single-branch
```
### Custom format for `git log` 
```sh
$ git log --graph --pretty=format:"%Ced%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset" --abbrev-commit --date=relative
```

### Git rebase interactive
```sh
$ git rebase -i <after-this-commit>
```
### Git stash
```sh
$ git stash save "comment"
$ git stash save -u "comment"    # -u | --include-untracked
$ git stash save -a "comment"
$ git stash apply
$ git stash drop
$ git stash clear
```

### Useful Git command 
```sh
$ git pull --rebase --autostash
$ git rm --cached <file>
```
### Reference
1. [Git-Tutorials](https://github.com/twtrubiks/Git-Tutorials)
