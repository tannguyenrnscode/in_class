# in_class
mkdir <new_projectname>
cd <new_projectname>
git init
git add README.md
git commit -m "first commit"
git branch -M master/main
git remote add origin git@github.com:tannguyenrnscode/helloclass.git
/* change destination */
git remote set-url origin git@github.com:tannguyenrnscode/helloclass.git
/* current destination */
git remote -v

git pull --rebase origin main
git push -u origin main
/* create new file */
touch <newfile>

git log
git log --oneline
git log --since="1 week ago"
git log --author"sth"
