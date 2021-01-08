#this is text
#second text
#third text
#fourth text
#fifth text
#color for css and desiging
Tomato
Orange
DodgerBlue
MediumSeaGreen
Gray
SlateBlue
Violet
LightGray



///COMMANDS//////

Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Try the new cross-platform PowerShell https://aka.ms/pscore6

PS D:\testing\gittwo> git --version
git version 2.30.0.windows.1
PS D:\testing\gittwo> git config --global user.email "a.yashwantreddy31@gmail.com"
PS D:\testing\gittwo> git config list
error: key does not contain a section: list
PS D:\testing\gittwo> git config --list
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
http.sslbackend=openssl
diff.astextplain.textconv=astextplain
filter.lfs.process=git-lfs filter-process
credential.helper=manager-core
core.autocrlf=true
core.fscache=true
core.symlinks=true
pull.rebase=false
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=yashwant
user.email=a.yashwantreddy31@gmail.com
PS D:\testing\gittwo>


    Directory: D:\testing\gittwo


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----         1/8/2021  11:25 AM                my-project


PS D:\testing\gittwo\my-project> cd ..
PS D:\testing\gittwo> ls


    Directory: D:\testing\gittwo

Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----         1/8/2021  11:25 AM                my-project

commit a0beaf12d1859d6d9789741a3d1ca8723cc947c9 (HEAD -> master)
Date:   Fri Jan 8 11:30:30 2021 +0530

PS D:\testing\gittwo> git log
commit ca84b142c84173562eed9e10e07db7ffd3de18d6 (HEAD -> master)                                                                                                           commit ca84b142c84173562eed9e1
Date:   Fri Jan 8 11:30:30 2021 +0530

    first commit
PS D:\testing\gittwo> git remote add origin https://github.com/yashwant-reddy/test.git
PS D:\testing\gittwo> git remote
origin                                                                                                                                                                     PS D:\testing\gittwo> git remo
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/yashwant-reddy/test.git'
PS D:\testing\gittwo> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/yashwant-reddy/test.git'
PS D:\testing\gittwo> git commit -m "initial commit"
On branch master
nothing to commit, working tree clean
PS D:\testing\gittwo> git commit -m "initial commit"
On branch master
nothing to commit, working tree clean
PS D:\testing\gittwo> git commit -m "initial commit"
>> git push origin master
On branch master
nothing to commit, working tree clean
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 488 bytes | 488.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/yashwant-reddy/test.git
 * [new branch]      master -> master
PS D:\testing\gittwo>