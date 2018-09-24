# Class Notes

******

### TOC

[Notes on HTML](#html)

#### Html<a name="html></a>"

We are learning about html.

- [ ]

You can make unordered lists:

- thing
- thing two

You can make ordered lists:

1. It doesn't matter what
3. number you
4. use for your lists.

###### How to ask a question:

- List steps you've tried.
- Why you think there is a problem.
- Ask the question.

###### cmd line commands:

- pwd: print working directory - reference from root directory to where you exist.
- cd /: cd's into root directory.
- cd ~: cd's you to user directory.
- ls: looks around in the directory you are in.
- mkdir (filename): makes a directory.
- touch (filename): makes a file.
- rm -rf (filename): force removes a file.
- mv (filename newLocation/Name): moves a file to a new directory. Also renames files.
- (press up arrow): copy previous commands.
- history: lists previous commands.
- history | grep (command): lists previous uses of specified command.
- top: lists out running processes on your computer.

###### vim:

- esc, :q!: quit without saving.
- x: deletes character.
- esc, :wq: saves and quits.

##### git commands:

- git checkout -b (nameofbranch): creates and moves you to a branch.
- git status: shows files that are modified from original.
- git add -A: adds all files to the commit.
- git commit -m "message": commits files for push and adds a description message.
- git push: pushes files to github.
- git merge master: while in your branch (checkout gets you there) will merge your branch with the master.

##### data relationships (ex: DnD)

1. 1:1
  -character:alignment

2. 1:many
  -character:classes

3. many:many
  -races:classes

##### 4 principles when working with databases

1. CRUD
  - create - post
  - Read - get
  - update - put
  - delete - delete

##### relational vs non relational databases

1. Non-relational
  - Afraid to get hurt
  - MongoDB (runs in terminal in background)
  - uses id's to link data (json)
  - Mongo shell will create collections
  - ORM-Object Relational Mapper
  - ORM adds a layer of abstraction, maps objects for you.

2. relational
  - Ready to commit
  - has more structure
  - uses primary keys and (foreign keys-multiple tables)

##### Test Driven Development (TDD)

- Build
- Red = failing
- Get test to pass (green)
- Refactor (make it pretty)
