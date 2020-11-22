# ZSH Aliases

```sh
# easier navigation: .., ..., ~ and -
alias cl="clear"
alias ~="cd ~"
alias ..="cd .."
alias cd..="cd .."
alias ...="cd ../.."
alias ....="cd ../../.."
alias .....="cd ../../../.."
alias show="ls -ltr"

# easier git commands
alias gst="git status"
alias gb="git branch"
alias gc="git checkout"
alias gl="git log --oneline --decorate --color"
alias gmaster="git checkout master"
alias gamend="git add . && git commit --amend --no-edit"
alias gcommit="git add . && git commit -m"
alias gdiff="git diff"
alias gforce="git push --force"
alias gnuke="git clean -df && git reset --hard"
alias gpull="git pull"
alias gpush="git push"
alias gresolve="git add . && git commit --no-edit"
alias gunstage="git restore --staged ."

# easier npm
alias node_nuke="rm -rf package-lock.json && rm -rf node_modules"
alias node_restore="rm -rf package-lock.json && rm -rf node_modules && npm install"
```
