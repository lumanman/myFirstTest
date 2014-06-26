git 

git add 1.txt

git commit -m "注释"

git log


正确的提交方式是：第一次修改 -> add -> 第二次修改 -> add -> commit
提交后，用“git diff HEAD -- readme.txt”命令可以查看工作区和版本库里面最新版本的区别：