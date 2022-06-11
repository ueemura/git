# GIT

Sistema de versionamento de códigos distribuídos.

## Configuração

##### Setar usuário

    git config --global user.name "nome"

##### Setar e-mail

    git config --global user.email seuemail@email.com.br

## Repositório local

##### Criar novo repositório

    git init

##### Exibir estado dos arquivos/diretório

    git status

### Adicionar arquivo/diretório (ir para Staged Area)

##### Adicionar um arquivo

    git add meu_arquivo.txt

##### Adicionar um diretório

    git add meu_diretorio

##### Adicionar todos os arquivos/diretórios

    git add .	

### Comitar arquivo/diretório

##### Comitar um arquivo

    git commit nome_arquivo.txt

##### Comitar vários arquivos

    git commit nome_arquivo.txt arquivo_dois.txt

##### Comitar informando mensagem

    git commit meuarquivo.txt -m "escreva sua mensagem de commit"

### Remover arquivo/diretório

##### Remover arquivo

    git rm nome_arquivo.txt

##### Remover diretório

    git rm -r diretorio

## Repositório remoto

#### Listar de repositórios remotos

    git remote -v

#### Vincular repositório local com um repositório remoto

    git remote add origin git@github.com:ueemura/git.git

#### Enviar arquivos/diretórios para o repositório remoto

Primeiro push de um repositório (informar o nome do repositório remoto e o branch)
    git push origin master

Os demais pushes
    git push
    

#### Clonar um repositório remoto já existente

    git clone git@github.com:ueemura/git.git

## Estados

Modified - Modificado  
Staged - Preparado  
Comitted - Consolidado  
    

