# List of commands used in git bash

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/ShellScripting (main)
$ git ~
git: 'C:/Users/MMooKow' is not a git command. See 'git --help'.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/ShellScripting (main)
$

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/ShellScripting (main)
$ cd ~

MMooKow@DESKTOP-MNQ3ALS MINGW64 ~
$

MMooKow@DESKTOP-MNQ3ALS MINGW64 ~
$ cd c:/Revature/01Scripting/
bash: cd: c:/Revature/01Scripting/: No such file or directory

MMooKow@DESKTOP-MNQ3ALS MINGW64 ~
$

MMooKow@DESKTOP-MNQ3ALS MINGW64 ~
$ cd c:/Revature/training-code/01Scripting/Activity1

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ touch commandsUsed.md

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ vi commandsUsed.md

[1]+  Stopped                 vi commandsUsed.md

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git clone https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo.git
Cloning into 'P0-Dylan-Restivo'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ add Hello.sh
bash: add: command not found

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ cd ..

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting (main)
$ cd ./
Activities.md   Activity1/      Notes.md        ShellScripting/

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting (main)
$ cd ShellScripting/

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/ShellScripting (main)
$ mv Hello.sh c:/Revature/training-code/01Scripting/Activity1

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/ShellScripting (main)
$ cd ..

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting (main)
$ cd Activity1/

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ ls
Hello.sh  P0-Dylan-Restivo/  commandsUsed.md  movieList.sh*

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git add Hello.sh
warning: LF will be replaced by CRLF in training-code/01Scripting/Activity1/Hello.sh.
The file will have its original line endings in your working directory

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git branch
* main

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ code Hello.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ mv Hello.sh HelloCopy.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ cp HelloCopy.sh Hello.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ vi Hello.sh

[2]+  Stopped                 vi Hello.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ ./Hello.sh
./Hello.sh: line 9: $':\nThis is\na\nmultiline\ncomment\n': command not found
Hello World
Our Shell name is /usr/bin/bash
Our Shell version is 4.4.23(1)-release
Our Shell home directory is /c/Users/MMooKow
Our current working directory is /c/Revature/training-code/01Scripting/Activity1
The name is Dylan
The changed name Fred
./Hello.sh: line 31: unset: pi: cannot unset: readonly variable
the value of pi is 3.14
./Hello.sh: line 34: syntax error near unexpected token `read'
./Hello.sh: line 34: `function addNum(read num1 num2) {'

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ vi Hello.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Hello.sh

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../../../Notes/
        ../../../Week1/
        ../Activities.md
        .Hello.sh.swp
        .commandsUsed.md.swp
        HelloCopy.sh
        P0-Dylan-Restivo/
        commandsUsed.md
        movieList.sh
        ../Notes.md
        ../ShellScripting/
        ../../LICENSE
        ../../README.md


MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git remove Hello.sh
git: 'remove' is not a git command. See 'git --help'.

The most similar command is
        remote

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git add movieList.sh
warning: LF will be replaced by CRLF in training-code/01Scripting/Activity1/movieList.sh.
The file will have its original line endings in your working directory

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git commit -m "Added movieList.sh and Hello.sh due to confusion"
[main d67deda] Added movieList.sh and Hello.sh due to confusion
 2 files changed, 46 insertions(+)
 create mode 100644 training-code/01Scripting/Activity1/Hello.sh
 create mode 100644 training-code/01Scripting/Activity1/movieList.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git push --set-upstream origin Main
remote: Permission to 210726-wvu-net-ext/training-code.git denied to MMooKow.
fatal: unable to access 'https://github.com/210726-wvu-net-ext/training-code.git/': The requested URL returned error: 403

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git checkout -b dev-branch-dylanrestivo
Switched to a new branch 'dev-branch-dylanrestivo'

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream Origin dev-branch-dylanrestivo
fatal: 'Origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git remote add origin
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git remote add origin
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git remote add origin
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git remote add origin https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo.git
error: remote origin already exists.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
remote: Permission to 210726-wvu-net-ext/training-code.git denied to MMooKow.
fatal: unable to access 'https://github.com/210726-wvu-net-ext/training-code.git/': The requested URL returned error: 403

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git remote add origin https://github.com/MMooKow/P01-Nikhil-Gangaramani.git
error: remote origin already exists.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin https://github.com/MMooKow/P01-Nikhil-Gangaramani.git
fatal: invalid refspec 'https://github.com/MMooKow/P01-Nikhil-Gangaramani.git'

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
remote: Permission to 210726-wvu-net-ext/training-code.git denied to MMooKow.
fatal: unable to access 'https://github.com/210726-wvu-net-ext/training-code.git/': The requested URL returned error: 403

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push
fatal: The current branch dev-branch-dylanrestivo has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev-branch-dylanrestivo


MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
remote: Permission to 210726-wvu-net-ext/training-code.git denied to MMooKow.
fatal: unable to access 'https://github.com/210726-wvu-net-ext/training-code.git/': The requested URL returned error: 403

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git clone https://github.com/MMooKow/P0-Dylan-Restivo.git
fatal: destination path 'P0-Dylan-Restivo' already exists and is not an empty directory.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git clone https://github.com/MMooKow/P0-Dylan-Restivo.git
Cloning into 'P0-Dylan-Restivo'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ -git add Hello.sh movieList.sh
bash: -git: command not found

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git add Hello.sh movieList.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git commit -m "Added movieList and Hello.sh"
On branch dev-branch-dylanrestivo
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Hello.sh

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../../../Notes/
        ../../../Week1/
        ../Activities.md
        P0-Dylan-Restivo/
        commandsUsed.md
        ../Notes.md
        ../ShellScripting/
        ../../LICENSE
        ../../README.md

no changes added to commit (use "git add" and/or "git commit -a")

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
remote: Permission to 210726-wvu-net-ext/training-code.git denied to MMooKow.
fatal: unable to access 'https://github.com/210726-wvu-net-ext/training-code.git/': The requested URL returned error: 403

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push
fatal: The current branch dev-branch-dylanrestivo has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev-branch-dylanrestivo


MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git clone https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo.git
Cloning into 'P0-Dylan-Restivo'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git branch
* dev-branch-dylanrestivo
  main

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git add Hello.sh
warning: LF will be replaced by CRLF in training-code/01Scripting/Activity1/Hello.sh.
The file will have its original line endings in your working directory

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git commit -m "Added Hello.sh"
[dev-branch-dylanrestivo 0e60172] Added Hello.sh
 1 file changed, 9 insertions(+), 37 deletions(-)
 rewrite training-code/01Scripting/Activity1/Hello.sh (99%)

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
remote: Permission to 210726-wvu-net-ext/training-code.git denied to MMooKow.
fatal: unable to access 'https://github.com/210726-wvu-net-ext/training-code.git/': The requested URL returned error: 403

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ .git/config
bash: .git/config: No such file or directory

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git/config
bash: git/config: No such file or directory

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ ^C

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git clone https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo.git
Cloning into 'P0-Dylan-Restivo'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (4/4), done.
Receiving objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1
$ git branch
fatal: not a git repository (or any of the parent directories): .git

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1
$ git status
fatal: not a git repository (or any of the parent directories): .git

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1
$ git status
fatal: not a git repository (or any of the parent directories): .git

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1
$ cd ..

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting
$ cd Activity1/

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1
$ git status
fatal: not a git repository (or any of the parent directories): .git

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1
$ git init
Initialized empty Git repository in C:/Revature/training-code/01Scripting/Activity1/.git/

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Hello.sh
        P0-Dylan-Restivo/
        commandsUsed.md
        movieList.sh

nothing added to commit but untracked files present (use "git add" to track)

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (master)
$ got add Hello.sh
bash: got: command not found

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (master)
$ git add Hello.sh
warning: LF will be replaced by CRLF in Hello.sh.
The file will have its original line endings in your working directory

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (master)
$ git commit -m "
> added Hello.sh"
[master (root-commit) 15940ee] added Hello.sh
 1 file changed, 9 insertions(+)
 create mode 100644 Hello.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (master)
$ git checkout -b dev-branch-dylanrestivo
Switched to a new branch 'dev-branch-dylanrestivo'

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git commit -m "added Hello.sh"
On branch dev-branch-dylanrestivo
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        P0-Dylan-Restivo/
        commandsUsed.md
        movieList.sh

nothing added to commit but untracked files present (use "git add" to track)

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git add Hello.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git commit -m "Added Hello.sh"
On branch dev-branch-dylanrestivo
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        P0-Dylan-Restivo/
        commandsUsed.md
        movieList.sh

nothing added to commit but untracked files present (use "git add" to track)

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git remote add origin <repo_url><repo_url>
bash: syntax error near unexpected token `<'

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git remote add origin https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo.git

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 327 bytes | 327.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev-branch-dylanrestivo' on GitHub by visiting:
remote:      https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo/pull/new/dev-branch-dylanrestivo
remote:
To https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo.git
 * [new branch]      dev-branch-dylanrestivo -> dev-branch-dylanrestivo
Branch 'dev-branch-dylanrestivo' set up to track remote branch 'dev-branch-dylanrestivo' from 'origin'.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ gh repo fork https://github.com/MMooKow/P01-Nikhil-Gangaramani.git
bash: gh: command not found

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git repo fork https://github.com/MMooKow/P01-Nikhil-Gangaramani.git
git: 'repo' is not a git command. See 'git --help'.

The most similar commands are
        grep
        reflog
        remote
        repack

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ gh auth login --web
bash: gh: command not found

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ cd ..

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting
$ mkdir partnetFork

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting
$ cd partnerFork
bash: cd: partnerFork: No such file or directory

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting
$ cd partnerFork/
bash: cd: partnerFork/: No such file or directory

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting
$ mkdir partnetFork/
mkdir: cannot create directory ‘partnetFork/’: File exists

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting
$ cd partnetFork/

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork
$ git init
Initialized empty Git repository in C:/Revature/training-code/01Scripting/partnetFork/.git/

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork (master)
$ git clone https://github.com/210726-wvu-net-ext/P01-Nikhil-Gangaramani.git
Cloning into 'P01-Nikhil-Gangaramani'...
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 7 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (7/7), done.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork (master)
$ git checkout -b dev-branch-dylanrestivo
Switched to a new branch 'dev-branch-dylanrestivo'

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork (dev-branch-dylanrestivo)
$ git add Hello.sh
warning: LF will be replaced by CRLF in Hello.sh.
The file will have its original line endings in your working directory

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork (dev-branch-dylanrestivo)
$ git commit -m "Added my hello.sh"
[dev-branch-dylanrestivo (root-commit) f2a4f78] Added my hello.sh
 1 file changed, 9 insertions(+)
 create mode 100644 Hello.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork (dev-branch-dylanrestivo)
$

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork (dev-branch-dylanrestivo)
$ git remote add origin https://github.com/210726-wvu-net-ext/P01-Nikhil-Gangaramani.git

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
remote: Permission to 210726-wvu-net-ext/P01-Nikhil-Gangaramani.git denied to MMooKow.
fatal: unable to access 'https://github.com/210726-wvu-net-ext/P01-Nikhil-Gangaramani.git/': The requested URL returned error: 403

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork (dev-branch-dylanrestivo)
$ git remote add origin https://github.com/MMooKow/P01-Nikhil-Gangaramani.git
error: remote origin already exists.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
remote: Permission to 210726-wvu-net-ext/P01-Nikhil-Gangaramani.git denied to MMooKow.
fatal: unable to access 'https://github.com/210726-wvu-net-ext/P01-Nikhil-Gangaramani.git/': The requested URL returned error: 403

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork (dev-branch-dylanrestivo)
$

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/partnetFork (dev-branch-dylanrestivo)
$ cd ..

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting
$ cd Activity1/

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git add Hello.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git commit -m "new message"
On branch dev-branch-dylanrestivo
Your branch is up to date with 'origin/dev-branch-dylanrestivo'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .commandsUsed.md.swo
        .commandsUsed.md.swp
        P01-Nikhil-Gangaramani/
        movieList.sh

nothing added to commit but untracked files present (use "git add" to track)

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
Everything up-to-date
Branch 'dev-branch-dylanrestivo' set up to track remote branch 'dev-branch-dylanrestivo' from 'origin'.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git remote set-url origin https://github.com/MMooKow/P01-Nikhil-Gangaramani/branches

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
fatal: unable to access 'https://github.com/MMooKow/P01-Nikhil-Gangaramani/branches/': The requested URL returned error: 410

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git remote set-url origin https://github.com/MMooKow/P01-Nikhil-Gangaramani

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 586 bytes | 586.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev-branch-dylanrestivo' on GitHub by visiting:
remote:      https://github.com/MMooKow/P01-Nikhil-Gangaramani/pull/new/dev-branch-dylanrestivo
remote:
To https://github.com/MMooKow/P01-Nikhil-Gangaramani
 * [new branch]      dev-branch-dylanrestivo -> dev-branch-dylanrestivo
Branch 'dev-branch-dylanrestivo' set up to track remote branch 'dev-branch-dylanrestivo' from 'origin'.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git status
On branch dev-branch-dylanrestivo
Your branch is up to date with 'origin/dev-branch-dylanrestivo'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .commandsUsed.md.swo
        .commandsUsed.md.swp
        P01-Nikhil-Gangaramani/
        movieList.sh

nothing added to commit but untracked files present (use "git add" to track)

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ ls
Hello.sh*  P01-Nikhil-Gangaramani/  commandsUsed.md  movieList.sh*

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git stash
No local changes to save

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git add Hello.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git commit -m "new file"
On branch dev-branch-dylanrestivo
Your branch is up to date with 'origin/dev-branch-dylanrestivo'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .commandsUsed.md.swo
        .commandsUsed.md.swp
        P01-Nikhil-Gangaramani/
        movieList.sh

nothing added to commit but untracked files present (use "git add" to track)

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
Everything up-to-date
Branch 'dev-branch-dylanrestivo' set up to track remote branch 'dev-branch-dylanrestivo' from 'origin'.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git statuws
git: 'statuws' is not a git command. See 'git --help'.

The most similar command is
        status

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git status
On branch dev-branch-dylanrestivo
Your branch is up to date with 'origin/dev-branch-dylanrestivo'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    commandsUsed.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        P01-Nikhil-Gangaramani/
        movieList.sh

no changes added to commit (use "git add" and/or "git commit -a")

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ code Hello.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git add Hello.sh
warning: LF will be replaced by CRLF in Hello.sh.
The file will have its original line endings in your working directory

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git commit -m "new comment"
[dev-branch-dylanrestivo 234abed] new comment
 1 file changed, 3 insertions(+), 1 deletion(-)

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin dev-branch-dylanrestivo
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MMooKow/P01-Nikhil-Gangaramani
   fbed4fc..234abed  dev-branch-dylanrestivo -> dev-branch-dylanrestivo
Branch 'dev-branch-dylanrestivo' set up to track remote branch 'dev-branch-dylanrestivo' from 'origin'.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ ls
Hello.sh*  P01-Nikhil-Gangaramani/  movieList.sh*

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git pull
Already up to date.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dyla
$ git pull
Already up to date.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dyla
$ git pull
Already up to date.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dyla
$ git remote set-url origin https://github.com/210726-wvu-net-ext/P01-Nikhil-Gangaramani

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dyla
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 758 bytes | 189.00 KiB/s, done.
From https://github.com/210726-wvu-net-ext/P01-Nikhil-Gangaramani
 * [new branch]      dev-branch-Nikhil -> origin/dev-branch-Nikhil
   a21aaa3..f824fea  main              -> origin/main
Your configuration specifies to merge with the ref 'refs/heads/dev-branch-dylanrestivo'
from the remote, but no such ref was fetched.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dyla
$ git pull git remote set-url origin https://github.com/210726-wvu-net-ext/P01-Nikhil-Gangaraman
fatal: invalid refspec 'https://github.com/210726-wvu-net-ext/P01-Nikhil-Gangaramani'

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dyla
$ git pull
Your configuration specifies to merge with the ref 'refs/heads/dev-branch-dylanrestivo'
from the remote, but no such ref was fetched.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dyla
$ cd C:\Revature\training-code\01Scripting\Activity1\P01-Nikhil-Gangaramani
bash: cd: C:Revaturetraining-code01ScriptingActivity1P01-Nikhil-Gangaramani: No such file or dir

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dyla
$ touch commandsUsed.md

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ code commandsUsed.ms

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ code commandsUsed.md

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ code commandsUsed.sh

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ code commandsUsed.md

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git remote set-url origin https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git status
On branch dev-branch-dylanrestivo
Your branch is up to date with 'origin/dev-branch-dylanrestivo'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   commandsUsed.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        P01-Nikhil-Gangaramani/
        movieList.sh

no changes added to commit (use "git add" and/or "git commit -a")

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        commandsUsed.md
Please commit your changes or stash them before you switch branches.
Aborting

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git add commandsUsed.md

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git commit -m "made file"
[dev-branch-dylanrestivo f367913] made file
 1 file changed, 769 insertions(+)

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo'

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git clone
fatal: You must specify a repository to clone.

usage: git clone [<options>] [--] <repo> [<dir>]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting
    --reject-shallow      don't clone shallow repository
    -n, --no-checkout     don't create a checkout
    --bare                create a bare repository
    --mirror              create a mirror repository (implies bare)
    -l, --local           to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    -s, --shared          setup as shared repository
    --recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    --recursive ...       alias of --recurse-submodules
    -j, --jobs <n>        number of submodules cloned in parallel
    --template <template-directory>
                          directory from which templates will be used
    --reference <repo>    reference repository
    --reference-if-able <repo>
                          reference repository
    --dissociate          use --reference only while cloning
    -o, --origin <name>   use <name> instead of 'origin' to track upstream
    -b, --branch <branch>
                          checkout <branch> instead of the remote's HEAD
    -u, --upload-pack <path>
                          path to git-upload-pack on the remote
    --depth <depth>       create a shallow clone of that depth
    --shallow-since <time>
                          create a shallow clone since a specific time
    --shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --single-branch       clone only one branch, HEAD or --branch
    --no-tags             don't clone any tags, and make later fetches not to follow them
    --shallow-submodules  any cloned submodules will be shallow
    --separate-git-dir <gitdir>
                          separate git dir from working tree
    -c, --config <key=value>
                          set config inside the new repository
    --server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --filter <args>       object filtering
    --remote-submodules   any cloned submodules will use their remote-tracking branch
    --sparse              initialize sparse-checkout file to include only files at root


MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ $
bash: $: command not found

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git clone https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo.git
Cloning into 'P0-Dylan-Restivo'...
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 7 (delta 0), reused 2 (delta 0), pack-reused 0
Receiving objects: 100% (7/7), done.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo'

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git remote set-url origin https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git push --set-upstream origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo'

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (dev-branch-dylanrestivo)
$ git checkout main
Switched to a new branch 'main'
Branch 'main' set up to track remote branch 'main' from 'origin'.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git push --set-upstream origin main
To https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git pull
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 7 (delta 0), reused 2 (delta 0), pack-reused 0
Unpacking objects: 100% (7/7), 2.06 KiB | 234.00 KiB/s, done.
From https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo
 + f824fea...8d2976d main       -> origin/main  (forced update)
fatal: refusing to merge unrelated histories

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git push --set-upstream origin main
To https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/210726-wvu-net-ext/P0-Dylan-Restivo'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ git pull
fatal: refusing to merge unrelated histories

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
$ ls
Hello.sh  LICENSE  P0-Dylan-Restivo/  P01-Nikhil-Gangaramani/  README.md  movieList.sh*

MMooKow@DESKTOP-MNQ3ALS MINGW64 /c/Revature/training-code/01Scripting/Activity1 (main)
