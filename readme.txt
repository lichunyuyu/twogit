Git is a version control system.
Git is free software.
Git is a distributed version control system.
Git is free software.
查看文件内容变化
$ git diff readme.txt
diff --git a/readme.txt b/readme.txt
index 3a94755..248596d 100644
--- a/readme.txt
+++ b/readme.txt
@@ -1,2 +1,4 @@
 <U+FEFF>Git is a version control system.
+Git is free software.
+Git is a distributed version control system.
 Git is free software.
\ No newline at end of file
查看文件内容
$ cat readme.txt
Git is a version control system.
Git is free software.
Git is a distributed version control system.
Git is free software.
diff --git a/readme.txt b/readme.txt
index 3a94755..248596d 100644
--- a/readme.txt
+++ b/readme.txt
@@ -1,2 +1,4 @@
 <U+FEFF>Git is a version control system.
+Git is free software.
+Git is a distributed version control system.
 Git is free software.
\ No newline at end of file
查看提交日志
 --pretty=oneline 以行的形式，简写
$ git log --pretty=oneline
版本回退
$ git reset --hard 1094a
查看每一次操作的命令（记录）
$ git reflog