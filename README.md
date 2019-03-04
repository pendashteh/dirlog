# dirlog
Keep track of changes in a directory with the comfort of git

# Usecase
Let's say you have a project folder with a git repository in it.
```
$ tree -L 1 ./project
./project
├── archive
├── docs
├── todo.txt
└── repo
```
You want to keep track of the name of the files exists in this directoy, not the content (because content is either large, or irreleavnt)

```
$ dirlog
```
Now there is a new filed called `__dir__.log` and everytime you run `dirlog` again, it updates the log and keeps track of the changes in a git repository created for this purpose.
