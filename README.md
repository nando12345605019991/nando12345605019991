
Prática
Voltar ao curso
Prática
A entrega desse exercício consiste em:



Crie um repositório no Github, por exemplo: curso_ebac_frontend;

Criar um branch chamado exercicio_git no repositório recém-criado;

Na branch exercício_git deverá ser adicionado um arquivo nome.txt com seu nome completo;

Disponibilizar o link do repositório no portal do aluno.

Entrega: Exercício Módulo 2
Olá, estudante!
Uma informação importante: esse exercício foi atualizado, mas alteramos apenas a narrativa, o objetivo continua o mesmo. Se você já realizou a atividade e foi aprovado, pode seguir em sua jornada.
Bons estudos 😄
Fernanda Sousa
15 de março 15:52
# Cria um novo repositório local chamado 'curso_ebac_frontend'

git init curso_ebac_frontend

cd curso_ebac_frontend

# Cria um novo arquivo README.md e faz o primeiro commit

echo "#Curso EBAC Frontend" >> README.md

git adicionar README.md

git commit -m "primeiro commit"

# Adicionado o repositório remoto do GitHub (substitua 'seu_usuario' pelo seu nome de usuário do GitHub)

git remoto adicionar origem https://github.com/seu_usuario/curso_ebac_frontend.git

# Envia os commits para o repositório remoto no GitHub

git push -u mestre de origem

# Cria um novo branch chamado 'exercicio_git'

git checkout -b exercício_git

# Cria um arquivo nome.txt com seu nome completo (substitua 'Seu Nome Completo' pelo seu nome)

echo "Seu Nome Completo" > nome.txt

# Adicionado o arquivo nome.txt ao commit

git adicionar nome.txt

git commit -m "Adicionar nome.txt com meu nome completo"

# Envia o branch 'exercicio_git' para o repositório remoto no GitHub

git push -u origem exercicio_git

# Para criar uma nova branch:
git branch nome_da_branch

# Para trocar para a branch criada:
git checkout nome_da_branch

# Para criar um novo arquivo, você pode usar o editor de texto de sua preferência. Por exemplo, usando o touch no terminal:
touch nome_do_arquivo.ext

