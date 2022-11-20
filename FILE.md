1 echo "# sp3-rdunn06-gitbranching-v1" >> README.md
2 git init
3 git add README.md
4 git commit -m "first commit"
5 git branch -M main
6 git remote add origin git@github.com:ryanrdunn/sp3-rdunn06-gitbranching-v1.git
7 git push -u origin main
8 git branch bug-fix
9 git checkout master
git commit -m "commit 1"
