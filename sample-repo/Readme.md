## First commit here 

i'll create a new folder to initialize git in that 

```
mkdir/workspaces/tmp/new-project
cd /workspaces/tmp/new-project
git init
touch readme.md
open readme.md

# makes changes

git commit -a -m "add readme"
```

## three ways of ee adichan copy is as follows

let's create a temprory folder name tmp

```sh
mkdir tmp
cd tmp/
```

### HTTPS
### SSH
### GitHub CLI

```sh
git clone https://github.com/madhu2944/sample-resume.git 
```



 ## commiting

when  we have to commit code we can use the following command which will open an editor of oue choice 

```sh
git commit
```

>you will need a pesonal access token to access th eremote repo from local system with username instead of password we can use PAT.


to set global  editor 

```sh
git config --global core.editor emacs
```

to use vscode as editor

```sh
git config --global core.editor "code --wait"

```
wait means it tells git to wait till the file in vscode is closed

```sh
git commit -m "commit message"
```

that was for inline commit 


 ## branches

 ## Remotes

 ## Stashing


 When we want to make a file to be unstaged we can use

 ```sh
 git reset
 ```


 ## Git config

 this is the file which stores ur name mail etc etc
showing the contents of that file

 ```sh
git config --list
```

when iinstalled in pc 

```sh
git cofig --global user.name "Jhon Doe"

git config --global user.email xxx@gmail.com

```

## log

```sh 
git log
```

shows the latest git commit along with commit's hash