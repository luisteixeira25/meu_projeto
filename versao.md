# função criada por Marcos Oliveira do
# site terminalroot.com.br
# curso de git/github

# função para git no ~bashrc

versao(){
    [[ -z "$*"]] && _c="Não á comentário para esse commit" || _c="$*"
    git add -A
    git commit -m "${_c}"
}

# executar:
source ~/.bashrc
