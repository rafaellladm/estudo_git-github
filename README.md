# GIT E GITHUB

Guia prático para iniciantes.

## Instalação (caso seus sistema seja Windows)

https://git-scm.com/download

# SCENES
- [x] Você deseja criar seu projeto

    - `git init` // inicia a linha do tempo

- [x] Você deseja criar pontos na história da produção do seu projeto

    - `git add` '+ nome do arquivo' // adiciona ou atualiza mudanças para irem para a linha do tempo
    - `git add .` // adiciona ou atualiza mudanças de todos os arquivos para irem para a linha do tempo
    - `git commit` `-m` 'observações do ponto' // adiciona um ponto na linha do tempo
        - `git commit` `-am` 'observações do ponto' // adiciona um ponto na linha do tempo sem precisar precisar atualizar antes

- [x] Você deseja verificar mudanças feitas no seu projeto

    - `git log` // visualiza os pontos na linha do tempo / commit
    - `git status` // informa o estado das alterações do nosso projeto
    - `git show` // apresenta determinado ponto na história

- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.

    - `git branch` 'nome da branch' // gerenciar novas linhas do tempo
    - `git checkout` // manipula as linhas do tempo

- [x] Você adiciona as novas funcionalidades ao seu projeto em produção

    - `git merge` // unir linhas do tempo

- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

    - `git branch` `-D` 'nome da branch' // delete a linha do tempo desejada.

- [x] Você quer colocar seu projeto na nuvem.

    - `criar repositório no seu Github`
    - `git remote add origin` + url do github // gera uma ligação entre o repositório local e remoto.
    - `git remote -v` // mostra repositórios remotos.
    - `git push` // envia alterações locais para o repositório remoto.
    - `git push -u origin master` // cria a branch master do repositório remoto.