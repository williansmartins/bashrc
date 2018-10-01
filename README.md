# bashrc
meus atalhos para serem utilizados no .bashrc

## referências
https://superuser.com/questions/602872/how-do-i-modify-my-git-bash-profile-in-windows

https://natelandau.com/my-mac-osx-bash_profile/

## run
`source .bashrc`

## comandos
`
function gacp(){
  git add . && git commit -m "comite atomico - gacp" && gpush
}
`

`
function gacp2(){
  git add . && git commit -m "$@ - gacp2" && gpush
}
`
`
function editarBash(){
  s ~/.bash_profile
}
`

`alias c='clear' # c: Clear terminal display`

`alias l='clear && pwd && ls -alFG '`

`alias gs='printf "\033c" && git status'`
