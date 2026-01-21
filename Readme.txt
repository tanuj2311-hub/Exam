git init
touch p.txt q.txt
git add .
git commit -m "add in master"
git remote add origin [repo link]
git push origin master
git checkout -b b1
touch x.txt
git add .
git commit -m "added to b1"
git push origin b1
git checkout -b b2
touch v.txt
git add .
git commit -m"added to b2"
git push -u origin b2
