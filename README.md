# Learn the Hard Way - Git

```bash
apt install git
yum install git
pacman -S git
```
- [Git for Windows](https://git-scm.com/downloads)

Alpine Linux  
```bash
$ sudo apk add git
[sudo] password for tuyen:
fetch https://dl-cdn.alpinelinux.org/alpine/v3.17/main/x86_64/APKINDEX.tar.gz
fetch https://dl-cdn.alpinelinux.org/alpine/v3.17/community/x86_64/APKINDEX.tar.gz
(1/5) Installing brotli-libs (1.0.9-r9)
(2/5) Installing nghttp2-libs (1.51.0-r2)
(3/5) Installing libcurl (8.9.0-r0)
(4/5) Installing pcre2 (10.42-r0)
(5/5) Installing git (2.39.5-r0)
Executing busybox-1.35.0-r29.trigger
OK: 605 MiB in 144 packages
$ git -v
git version 2.39.5
$
```

```
git -v
git --version
git init
git init REPO-NAME-HERE
git status
git log
git log -NUMBER-HERE
git add FILENAME-HERE
git add .
git commit -m "MESSAGE-HERE"
git clone URL-HERE
git checkout -- .
```

## Terms
- Staging area:
- Commit:
- Tree:
- Blob: Binary Large OBject  
- hash:
- 

## Free Courses
[SAP Cloud Platform Version Control with Git](https://open.sap.com/courses/git1) by Arnaldo Cavazos

- [DataCamp: Introduction to Git](https://app.datacamp.com/learn/courses/introduction-to-git)

## Books
[Pro Git book](https://git-scm.com/book/en/v2)
