# Configuration for git environment


## .gitconfig
[alias]
        ckt = checkout
        ft = fetch
        st = status
[core]
        excludesfile = /home/smartpanda/.gitignore_global
        autocrlf = input
[user]
        email = olivier.lefrancois@smartpanda.com
        name = olivier lefrancois
[merge]
        defaultToUpstream = true
[push]
        default = simple


## .gitignore_global
# git config --global core.excludesfile ~/.gitignore_global #

# Compiled source #
###################
*.com
*.class
*.dll
*.exe
*.o
*.so

# Packages #
############
# it's better to unpack these files and commit the raw source
# git has its own built in compression methods
*.7z
*.dmg
*.gz
*.iso
*.jar
*.rar
*.tar
*.zip

# Logs and databases #
######################
*.log
*.sqlite

# OS generated files #
######################
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db

# Dependencies folders #
########################
vendor/
node_modules/
bower_components/

# IDE config files #
####################
.idea/
*.history
out/
*.iml
.vscode
*.swp
