#Git
- Create Local Repository
```
$ git init git_example
$ cd git_example
$ git add readme.txt
$ git status
$ git commit -m "First Commit"
```
#Github
```
$git clone https://github.com/hmdo/proj
$cd proj
// add files to STAGING ARE to update what will be committed
$ git add README.md git-github.md
// Discard changes in working directory
$ git checkout -- README.md git-github.md
// Check status
$ git status
$ git commit -m "First commit on Github"
$ git push origin master
// Hide reports
$ git config --global push.default simple
```


#Python
```python {cmd:true, matplotlib:true}
import matplotlib.pyplot as plt
plt.plot([1,2,3, 4])
plt.show() # show figure
```
