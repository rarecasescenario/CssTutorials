
Useful links:
https://code.visualstudio.com/docs/editor/versioncontrol
https://www.hongkiat.com/blog/version-control-git-vs-code/
use of vs editor
https://www.youtube.com/watch?v=bJiIzz8mFMs


Create a new project
npm init

npm install bootstrap@3 --save

browser-sync start --server --files *.html, *.js, js/*.js, jquery/*.js css/*.css *.css --port 8081

https://github.com/vasyland/CssTutorials.git

…or create a new repository on the command line

echo "# CssTutorials" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/vasyland/CssTutorials.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/vasyland/CssTutorials.git
git push -u origin master


git\info\exclude add the folder you want to exclude
node_modules
and refresh project in vs code

// Other settings in git exclude file. this tis for node apps

# Logs
.logs
*.log
npm-debug.log*
yarn-debug.log*
yarn-error.log*

*.pid
*.seed
*.pid.lock

# nyc test coverage
.nyc_output

# Grunt intermediate storage (https://gruntjs.com/creating-plugins#storing-task-files)
.grunt

# Bower dependency directory (https://bower.io/)
bower_components

# node-waf configuration
.lock-wscript

#
# Optional npm cache directory
.npm
.eslintcache
.node_repl_history
*.tgz
.yarn-integrity
.env
.cache
.next
.nuxt
