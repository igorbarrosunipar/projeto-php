# Configurando a conta Git

- git config --global user.name "seu-nome"
- git config --global user.email "seu-email"

# Usando o Git (comandos)
# 1.0 - Crie uma nova pasta, abra-a e execute o comando, para criar um novo repositório:

- git init

# 1.1 - Crie uma cópia de trabalho em um repositório local executando o comando:

- git clone /caminho/para/o/repositório ou diretamente no repositório

# 1.2 - Propor mudanças:

- git add <arquivo>
- git add --all (Todos)

# 1.3 - Para realmente confirmar estas mudanças (isto é, fazer um commit), use:

- git commit -m "versão 1.0"

# 1.4 - Para enviar estas alterações ao seu repositório remoto:

- git push origin master (branch master)
- ou
- git push origin main (branch main)

# 1.5 - Para atualizar seu repositório local com a mais nova versão, execute:

- git pull

# 1.6 - Para obter e fazer merge (mesclar) alterações remotas, para fazer merge de um outro branch ao seu branch ativo (ex. master), use:

- git merge
