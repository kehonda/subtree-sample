# subtree-sample
```
git subtree add --prefix=child --squash child master
git remote add child git@github.com:kehonda/subtree-child-sample.git
```

```
# childのリポジトリにpushします
git subtree push --prefix=child --squash child test-branch
```
