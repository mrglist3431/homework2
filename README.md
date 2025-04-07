# homework2
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/reports/lab_2]
└─$ echo                          

                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/reports/lab_2]
└─$ ..
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/reports]
└─$ ..
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace]
└─$ cd homework2               
cd: no such file or directory: homework2
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace]
└─$ ls
lab02  lab3  master  node  projects  reports  scripts  tasks
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace]
└─$ git pull origin master                                                          
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace]
└─$ projects
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects]
└─$ ls
lab02  lab03  lab_2
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects]
└─$ mkdir homework2
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects]
└─$ homework2    
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git init              
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
Initialized empty Git repository in /home/kali/mrglist3431/workspace/projects/homework2/.git/
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add README.md
fatal: pathspec 'README.md' did not match any files
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ echo "#Homework2" >> README.md
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git init         
Reinitialized existing Git repository in /home/kali/mrglist3431/workspace/projects/homework2/.git/
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add README.md
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git commit -m"added README.md"                                                  
[master (root-commit) 0e69035] added README.md
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git branch -M main            
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git remote add origin https://github.com/${GITHUB_USERNAME}/homework2.git
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push -u origin main                                                  
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
To https://github.com/mrglist3431/homework2.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/mrglist3431/homework2.git'
hint: Updates were rejected because the remote contains work that you do not                                        
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push  origin main 
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
To https://github.com/mrglist3431/homework2.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/mrglist3431/homework2.git'
hint: Updates were rejected because the remote contains work that you do not                                        
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push  origin main
Username for 'https://github.com': ^C
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git pull origin main  
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 859 bytes | 859.00 KiB/s, done.
From https://github.com/mrglist3431/homework2
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint:
hint:   git config pull.rebase false  # merge
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint:
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: Need to specify how to reconcile divergent branches.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git --rebase                         
unknown option: --rebase
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
           <command> [<args>]
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git config  --global        
error: no action specified
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git config -e --global
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git pull origin main  
From https://github.com/mrglist3431/homework2
 * branch            main       -> FETCH_HEAD
hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint:
hint:   git config pull.rebase false  # merge
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint:
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: Need to specify how to reconcile divergent branches.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git config pull.rebase true 
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git config --rebase                           
error: unknown option `rebase'
usage: git config list [<file-option>] [<display-option>] [--includes]
   or: git config get [<file-option>] [<display-option>] [--includes] [--all] [--regexp] [--value=<value>] [--fixed-value] [--default=<default>] <name>
   or: git config set [<file-option>] [--type=<type>] [--all] [--value=<value>] [--fixed-value] <name> <value>
   or: git config unset [<file-option>] [--all] [--value=<value>] [--fixed-value] <name>
   or: git config rename-section [<file-option>] <old-name> <new-name>
   or: git config remove-section [<file-option>] <name>
   or: git config edit [<file-option>]
   or: git config [<file-option>] --get-colorbool <name> [<stdout-is-tty>]

Config file location
    --[no-]global         use global config file
    --[no-]system         use system config file
    --[no-]local          use repository config file
    --[no-]worktree       use per-worktree config file
    -f, --[no-]file <file>
                          use given config file
    --[no-]blob <blob-id> read config from given blob object

Action
    --get                 get value: name [<value-pattern>]
    --get-all             get all values: key [<value-pattern>]
    --get-regexp          get values for regexp: name-regex [<value-pattern>]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [<value-pattern>]
    --add                 add a new variable: name value
    --unset               remove a variable: name [<value-pattern>]
    --unset-all           remove all matches: name [<value-pattern>]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    -e, --edit            open an editor
    --get-color           find the color configured: slot [<default>]
    --get-colorbool       find the color setting: slot [<stdout-is-tty>]

Display options
    -z, --[no-]null       terminate values with NUL byte
    --[no-]name-only      show variable names only
    --[no-]show-origin    show origin of config (file, standard input, blob, command line)
    --[no-]show-scope     show scope of config (worktree, local, global, system, command)
    --[no-]show-names     show config keys in addition to their values

Type
    -t, --[no-]type <type>
                          value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    --[no-]default <value>
                          with --get, use default value when missing entry
    --[no-]comment <value>
                          human-readable comment string (# will be prepended as needed)
    --[no-]fixed-value    use string equality when comparing values to value pattern
    --[no-]includes       respect include directives on lookup

                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git pull origin main                                
From https://github.com/mrglist3431/homework2
 * branch            main       -> FETCH_HEAD
Auto-merging README.md
CONFLICT (add/add): Merge conflict in README.md
error: could not apply 0e69035... added README.md
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
hint: Disable this message with "git config advice.mergeConflict false"
Could not apply 0e69035... added README.md
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git rebase                                                               
fatal: It seems that there is already a rebase-merge directory, and
I wonder if you are in the middle of another rebase.  If that is the
case, please try
        git rebase (--continue | --abort | --skip)
If that is not the case, please
        rm -fr ".git/rebase-merge"
and run me again.  I am stopping in case you still have something
valuable there.

                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git rebase --continue
README.md: needs merge
You must edit all merge conflicts and then
mark them as resolved using git add
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ nano README.md     
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git pull origin main 
error: Pulling is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git commit -m"added README.md"
U       README.md
error: Committing is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git rebase --skip             
Successfully rebased and updated refs/heads/main.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git pull origin main
From https://github.com/mrglist3431/homework2
 * branch            main       -> FETCH_HEAD
Already up to date.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push  origin main
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
Everything up-to-date
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add helloworld.cpp
fatal: pathspec 'helloworld.cpp' did not match any files
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git mkdir helloworld.cpp
git: 'mkdir' is not a git command. See 'git --help'.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ cat > homework/helloworld.cpp <<EOF
#include <iostream>
using namespace std;
int main(){
cout<<"Привет, мир!";
}
heredoc> EOF
zsh: no such file or directory: homework/helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ cat > homework2/helloworld.cpp <<EOF
#include <iostream>
using namespace std;
int main(){
cout<<"Привет, мир!";
}
EOF
zsh: no such file or directory: homework2/helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ cat > homework2/helloworld.cpp <<EOF
#include <iostream>
using namespace std;
int main(){
cout<<"Привет, мир!";
}
EOF
zsh: no such file or directory: homework2/helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add helloworld.cpp  
fatal: pathspec 'helloworld.cpp' did not match any files
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add homework2.cpp 
fatal: pathspec 'homework2.cpp' did not match any files
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ mkdir helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ EOF
EOF: command not found
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ cat > homework2/helloworld.cpp <<EOF
#include <iostream>
using namespace std;
int main(){
cout<<"Привет, мир!";
}
EOF
zsh: no such file or directory: homework2/helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ ls
helloworld.cpp  README.md
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/…/workspace/projects/homework2/helloworld.cpp]
└─$ git add helloworld.cpp
fatal: pathspec 'helloworld.cpp' did not match any files
                                                                                                                    
┌──(kali㉿kali)-[~/…/workspace/projects/homework2/helloworld.cpp]
└─$ ..
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ rmdir helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ touch helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ nano helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git commit -m"added helloworld"
[main 910e631] added helloworld
 1 file changed, 6 insertions(+)
 create mode 100644 helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git pull origin main           
fatal: unable to access 'https://github.com/mrglist3431/homework2.git/': Could not resolve host: github.com
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push  origin main
fatal: unable to access 'https://github.com/mrglist3431/homework2.git/': Could not resolve host: github.com
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git pull origin main 
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (4/4), 1.78 KiB | 1.78 MiB/s, done.
From https://github.com/mrglist3431/homework2
 * branch            main       -> FETCH_HEAD
   383f8e7..989be92  main       -> origin/main
Successfully rebased and updated refs/heads/main.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push  origin main
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 362 bytes | 362.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/mrglist3431/homework2.git
   989be92..654a7da  main -> main
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ nano helloworld.cpp  
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git commit -m "update helloworld"
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   helloworld.cpp

no changes added to commit (use "git add" and/or "git commit -a")
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add helloworld.cpp           
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git commit -m "update helloworld"
[main caa07b7] update helloworld
 1 file changed, 4 insertions(+), 1 deletion(-)
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git pull origin main             
From https://github.com/mrglist3431/homework2
 * branch            main       -> FETCH_HEAD
Current branch main is up to date.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push  origin main
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 400 bytes | 400.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/mrglist3431/homework2.git
   654a7da..caa07b7  main -> main
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git branch patch1    
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git checkout patch1              
Switched to branch 'patch1'
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ nano helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git commit -m "update helloworld"
[patch1 b1db6c8] update helloworld
 1 file changed, 3 insertions(+), 3 deletions(-)
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push origin patch1           
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 400 bytes | 400.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'patch1' on GitHub by visiting:
remote:      https://github.com/mrglist3431/homework2/pull/new/patch1
remote: 
To https://github.com/mrglist3431/homework2.git
 * [new branch]      patch1 -> patch1
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ nano helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git commit -m "added comment"    
[patch1 2158ea8] added comment
 1 file changed, 1 insertion(+)
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push origin patch1       
fatal: unable to access 'https://github.com/mrglist3431/homework2.git/': Could not resolve host: github.com
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push origin patch1
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 361 bytes | 361.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/mrglist3431/homework2.git
   b1db6c8..2158ea8  patch1 -> patch1
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ nano helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git checkout main            
Switched to branch 'main'
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git pull origin main  
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 885 bytes | 885.00 KiB/s, done.
From https://github.com/mrglist3431/homework2
 * branch            main       -> FETCH_HEAD
   caa07b7..46a43ef  main       -> origin/main
Updating caa07b7..46a43ef
Fast-forward
 helloworld.cpp | 7 ++++---
 1 file changed, 4 insertions(+), 3 deletions(-)
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git log             
commit 46a43effd31da3d95d52a9ff8b0996e52b30f7bd (HEAD -> main, origin/main)
Merge: caa07b7 2158ea8
Author: mrglist3431 <ifedotov236@gmail.com>
Date:   Mon Apr 7 21:42:52 2025 +0300

    Merge pull request #1 from mrglist3431/patch1
    
    Patch1

commit 2158ea879e54f093005f5761916718a657d8c5ee (origin/patch1, patch1)
Author: mrglist3431 <ifedotov236@gmail.com>
Date:   Mon Apr 7 18:56:55 2025 +0300

    added comment

commit b1db6c811f0410bd7111be529723972a8e2494f6
Author: mrglist3431 <ifedotov236@gmail.com>
Date:   Mon Apr 7 18:31:18 2025 +0300

    update helloworld

commit caa07b70e521bda79d1299c72a5144cf7b884a2c
Author: mrglist3431 <ifedotov236@gmail.com>
Date:   Mon Apr 7 16:23:38 2025 +0300

    update helloworld

commit 654a7da33d2f1c1d2fffa2c09099341bbd12cebc
Author: mrglist3431 <ifedotov236@gmail.com>
Date:   Mon Apr 7 16:17:20 2025 +0300

    added helloworld

commit 989be92aa032afcc12301c888e37a7149ec111ac
Author: mrglist3431 <ifedotov236@gmail.com>
Date:   Mon Apr 7 15:31:02 2025 +0300

    Delete homework2.cpp

commit 52881d81e682ceff81c4fdd1dc6b76ecbe4d2256
Author: mrglist3431 <ifedotov236@gmail.com>
Date:   Mon Apr 7 15:29:59 2025 +0300

    Create homework2.cpp

commit 383f8e7c354f8858b7d2f84fb1c0f4d8bd3a6f80
Author: mrglist3431 <ifedotov236@gmail.com>
Date:   Mon Apr 7 15:14:29 2025 +0300

    Initial commit
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git branch -d patch1
Deleted branch patch1 (was 2158ea8).
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git branch patch2   
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git checkout patch2
Switched to branch 'patch2'
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ sudo apt install clang-format
[sudo] password for kali: 
clang-format is already the newest version (1:19.0-63).
Summary:
  Upgrading: 0, Installing: 0, Removing: 0, Not Upgrading: 1396
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ clang-format helloworld.cpp -style=Mozilla -i helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git commit -m "style changed"
[patch2 19dd4bb] style changed
 1 file changed, 9 insertions(+), 8 deletions(-)
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push origin patch2       
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 453 bytes | 453.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'patch2' on GitHub by visiting:
remote:      https://github.com/mrglist3431/homework2/pull/new/patch2
remote: 
To https://github.com/mrglist3431/homework2.git
 * [new branch]      patch2 -> patch2
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git checkout main            
Switched to branch 'main'
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ nano helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git commit -m "new comment"                                 
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   helloworld.cpp

no changes added to commit (use "git add" and/or "git commit -a")
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add helloworld.cpp     
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git commit -m "new comment"
[main a695917] new comment
 1 file changed, 1 insertion(+), 1 deletion(-)
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push origin main       
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/mrglist3431/homework2.git
   46a43ef..a695917  main -> main
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git pull origin main
From https://github.com/mrglist3431/homework2
 * branch            main       -> FETCH_HEAD
Already up to date.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git pull origin patch2
From https://github.com/mrglist3431/homework2
 * branch            patch2     -> FETCH_HEAD
Auto-merging helloworld.cpp
CONFLICT (content): Merge conflict in helloworld.cpp
error: could not apply a695917... new comment
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
hint: Disable this message with "git config advice.mergeConflict false"
Could not apply a695917... new comment
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git rebase --continue 
helloworld.cpp: needs merge
You must edit all merge conflicts and then
mark them as resolved using git add
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ nano helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git add helloworld.cpp
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git rebase --continue 
[detached HEAD ae51d16] new comment
 1 file changed, 8 insertions(+), 8 deletions(-)
Successfully rebased and updated refs/heads/main.
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push -f origin patch2
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/mrglist3431/homework2.git/'
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push -f origin patch2
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
Everything up-to-date
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push origin patch2 
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
Everything up-to-date
                                                                                                                    
┌──(kali㉿kali)-[~/mrglist3431/workspace/projects/homework2]
└─$ git push -f origin main  
Username for 'https://github.com': mrglist3431
Password for 'https://mrglist3431@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 458 bytes | 458.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/mrglist3431/homework2.git
 + a695917...ae51d16 main -> main (forced update)
