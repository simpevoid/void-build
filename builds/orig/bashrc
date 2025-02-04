#
# ~/.bashrc
#

# If not running interactively, don't do anything
[[ $- != *i* ]] && return

alias ls='ls --color=auto'
alias ll='ls -lh'
alias i='doas pacman -S'
alias u='doas pacman -Syu'
alias r='doas pacman -Rns'
alias yi='yay -S'
alias grep='grep --color=auto'
alias c='clear'
alias x='startx'
alias vi='nvim'
#export PS1="\[\e[36m\]\W\[\e[m\] \[\e[31m\]>\[\e[m\] "

export PS1="\[\e[1;36m\]\W\[\e[0m\] \[\e[1;31m\]>\[\e[0m\] "


set -o vi

eval "$(zoxide init --cmd cd bash)"

