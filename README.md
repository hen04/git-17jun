git config --global user.name "Your Name"
git config --global user.email "your_email@whatever.com"

mkdir hello
cd hello
touch hello.html

git init

git add hello.html
git commit -m "First Commit"

git remote add ../hello.git
git push
