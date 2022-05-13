Answer 1
    git version 2.36.1.windows.1
Answer 2
    diff.astextplain.textconv=astextplain
    filter.lfs.clean=git-lfs clean -- %f
    filter.lfs.smudge=git-lfs smudge -- %f
    filter.lfs.process=git-lfs filter-process
    filter.lfs.required=true
    http.sslbackend=openssl
    http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
    core.autocrlf=true
    core.fscache=true
    core.symlinks=false
    pull.rebase=false
    credential.helper=manager-core
    credential.https://dev.azure.com.usehttppath=true
    init.defaultbranch=master
    user.name=js536718
    user.email=js536718@ohio.edu
Answer 3
        When typing “git add –help”, a website opens with information about the git-add(1) command
Answer 4        
        On branch master

    No commits yet

    Untracked files:
        (use "git add <file>..." to include in what will be committed)
            .vscode/
            README.md
            answers.md

    nothing added to commit but untracked files present (use "git add" to track)
Answer 5
       On branch master

    No commits yet

        (use "git rm --cached <file>..." to unstage)
            new file:   README.md

    Untracked files:
        (use "git add <file>..." to include in what will be committed)
            answers.md 
Answer 6
         On branch master

    Changes to be committed:
        (use "git rm --cached <file>..." to unstage)
            new file:   answers.md

    Untracked files:
        (use "git add <file>..." to include in what will be committed)
            .vscode/

    [master (root-commit) 46f7a71] Initial commit
    create mode 100644 answers.md  
Answer 7    
        [master (root-commit) 46f7a71] Initial commit
        2 files changed, 0 insertions(+), 0 deletions(-)
        create mode 100644 README.md
        create mode 100644 answers.md
Answer 8
    commit 46f7a71ad6db91d9329d22e7d2dc7eb904b27208 (HEAD -> master)
    Author: js536718 <js536718@ohio.edu>
    Date:   Fri May 13 10:54:33 2022 -0400
    Initial commit
Answer 9
    shulerj@OIT-SHULERJ:/mnt/c/Users/shulerj/OneDrive - Ohio University (1)/CS2400$ git push
    Username for 'https://github.com': js536718
    Password for 'https://js536718@github.com': 
    To https://github.com/js536718/git-lab
     ! [rejected]        main -> main (fetch first)
    error: failed to push some refs to 'https://github.com/js536718/git-lab'
    hint: Updates were rejected because the remote contains work that you do
    hint: not have locally. This is usually caused by another repository pushing
    hint: to the same ref. You may want to first integrate the remote changes
    hint: (e.g., 'git pull ...') before pushing again.
    hint: See the 'Note about fast-forwards' in 'git push --help' for details.
Answer 10
    Yes, the answers pushed to Visual Studio
Answer 11
    I got the same error at Answer 9
Answer 12
    I don't see my changes. I see:
    shulerj@OIT-SHULERJ:/mnt/c/Users/shulerj/OneDrive - Ohio University (1)/CS2400$ git pull
    remote: Enumerating objects: 9, done.
    remote: Counting objects: 100% (9/9), done.
    remote: Compressing objects: 100% (6/6), done.
    remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
    Unpacking objects: 100% (6/6), 2.22 KiB | 13.00 KiB/s, done.
    From https://github.com/js536718/git-lab
        d1e528d..6766f79  main       -> git-lab/main
    Your configuration specifies to merge with the ref 'refs/heads/main'
    from the remote, but no such ref was fetched.
Answer 13
    
