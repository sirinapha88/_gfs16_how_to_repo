# Git Cheatsheet

### Start a new project

```shell
$ mkdir project_name
$ git init
$ touch readme.md
$ git add readme.md
$ git commit -m "initial commit"
```

### Do some work and thn save it

First, do some work!
Make some changes., put them in the box, label the box.

```shell
$ git status
$ git add <whatever file>
$ git status
$ git commit -m"I made a bunch of changes, there are so many details, wee."
```

### Share my work with the world!

First, create a github repo.

```shell
$ git remote add origin https://github.com/sirinapha88/<name of repository>.git
$ git push -u origin master

```

### Help someone else with their code

First, find the code on github that you want to contribute to.

Then Fork it!

```shell
$ git clone git@github.com:<your username>/<repo_name>.git
```

Then, make some changes yu think are important.

```shell
$ git add <your files>
$ git commit -m"A really through explanation of what we did since this is someone else's work."
$ git push origin master
```

Finish what you started working on, then push up any addtional commits.

File a pull request with the commits in them that you want to use. Make sure you have a good explaination in the pull request of what this is, what it's intend to do, and some nice languge, rather than making fun of the original author.




