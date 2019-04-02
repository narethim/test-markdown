<!-- create a new repository on the command line -->

### Preparation
~~~bash
mkdir -p ~/projects/markdown/test-markdown
cd ~/projects/markdown/test-markdown

git config --global user.email "narethi@yahoo.com"
git config --global user.name "Nareth Im"

~~~

Create README.md and git-instruction.md

### ...or create a new repository on the command line
~~~bash
cd ~/projects/markdown/test-markdown

git init
git add .
git commit -m "first commit"

git remote add origin https://github.com/narethim/test-markdown.git
git push -u origin master
~~~

### ...or push an existing repository from the command line
~~~bash
git remote add origin https://github.com/narethim/test-markdown.git
git push -u origin master
~~~

### ...or import code from another repository
~~~bash
git remote add origin https://github.com/narethim/test-markdown.git
git push -u origin master
~~~

Use the following web site to convert mark-down text to html:
https://www.browserling.com/tools/markdown-to-html
