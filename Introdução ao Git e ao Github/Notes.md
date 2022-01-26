# Introdução ao Git e ao Github

## Tipos básicos de objetos do git

### Blobs

Os arquivos do git são guardados dentro do objeto chamado "blob" que contém metadados

### Trees

- As trees armazenam blobs
- Podem apontar tanto para blobs (que são os arquivos) quanto para outras ásvores
- Elas contem os nomes, diferente dos blobs

### Commit 

- É o objeto que junta tudo
- Ele aponta para uma arvore, para o último commit gerado antes dele (parente), para o autor e para uma mensagem
- Também tem um timestamp (data e hora em que foi criado)

## Comandos

**mv <arquivo> <diretório>** -> move um arquivo para um diretório
**git init** -> cria um repositório e uma pasta .git
**git status** -> mostra informações do working directory e local rep
**git config --list** -> mostra todas as configurações do git na máquina
**git config --global --unset <propriedade>** -> para remover alguma configuração para setar novamente
**git pull origin master** -> puxa a versão remota para a máquina, juntando alterações
**git clone <url>** -> clona um repositório do git para a máquina
