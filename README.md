HelloWorld
%date%
%time%
---

```sh

rem 1
git init

rem 2
gh repo create MyRepo-A --public

rem 3
git remote add origin https://github.com/samofor/MyRepo-A.git


rem 4
echo "# MyRepo-A .... Hello World" >> README.md

rem 5
git add README.md
git commit -m "First commit"
git branch -M main

rem 6
git push -u origin main

```