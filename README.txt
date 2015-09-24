$ cat ~/.inputrc 
set editing-mode vi
set keymap vi

$ cat ~/.bash_profile 
alias ll='ls -G'
alias ll='ls -la'
alias his='history'
alias grep='grep -i --color=auto'

case "$TERM" in
    xterm-color) color_prompt=yes;;
esac

export PS1="\[\e]0;\w\a\]\[\e[32m\]\u@\h \[\e[33m\]\w\[\e[0m\]\n\$ "
