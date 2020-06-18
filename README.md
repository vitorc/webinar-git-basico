# Webinar Git básico
Repositório para o Webinar - Git Comandos Básico

---

## Índice

  - [O que é Git?](#git)
  - [Conceito de Branchs](#branchs)
  - [O que é Git Hub](#github)
  - [Comandos Básicos](#comandos)
  - [Suporte](#suporte)
  - [Licença](#licena)

---

## Git

- O Git é um sistema open-source de controle de versão utilizado pela grande maioria dos desenvolvedores atualmente. Com ele podemos criar todo histórico de alterações no código do nosso projeto e facilmente voltar para qualquer ponto para saber como o código estava naquela data.

- Além disso, o Git nos ajuda muito a controlar o fluxo de novas funcionalidades entre vários desenvolvedores no mesmo projeto com ferramentas para análise e resolução de conflitos quando o mesmo arquivo é editado por mais de uma pessoa em funcionalidades diferentes.

## Branchs - Conceitos

> Entendendo como funciona a arquitetura de Branchs no Git

- Imagine que você esteja trabalhando no meio de uma grande funcionalidade, pode levar até 2 meses para terminá-la. Em uma bela manhã de sol seu chefe resolve pedir urgentemente uma alteração na versão em produção da aplicação, ou seja, você não pode utilizar o código em que está trabalhando pois o mesmo possui features inacabadas. Como resolver?

- As Branchs no Git são formas de termos uma mesma versão do código sofrendo alterações e recebendo commits de diferentes fontes e inclusive por diferentes desenvolvedores.

- Dessa forma, nós podemos manter um branch para nossa funcionalidade que irá levar mais tempo e trabalhar em outro branch com a versão em produção para realizar alterações mais urgentes. E fica tranquilo, no fim de tudo o Git ainda vai nos ajudar a unir os códigos desses dois ramos de forma muito simpática.

- Por padrão, você sempre está trabalhando em um ramo no Git, e mesmo quando você não cria um branch, o Git cria automaticamente um branch chamado master como padrão.

- Na imagem abaixo podemos ver um exemplo de trabalho com vários ramos e commits aplicados. Veja que em alguns pontos da história os ramos são unidos para que as alterações de um ramo sejam aplicadas a outro.

![Exemplo de Branchs](https://blog.rocketseat.com.br/content/images/2018/12/image-67.png)

- Nesse caso, “master”, “Hotfix”, “Release”, “Develop” e os “Feature” são os brancos enquanto que os círculos são os commits. As caixas com v0.1, v0.2 e v1.0 são versões (conhecidas por tags) que foram pra versão em produção e podem ser compostas por pontos na história de vários branchs.

>fonte: https://blog.rocketseat.com.br/iniciando-com-git-github/

## GitHub
> Definições básicas do GitHub
- Legal, até agora falamos sobre algumas funcionalidades do Git mas tem um grande problema aí: como os outros desenvolvedores do time terão acesso a todo esse código e poderão também adicionar seus branchs e commits?

- O Github é um serviço online de hospedagem de repositórios Git (como são chamados os projetos que utilizam Git). Com ele podemos manter todos nossos commits e ramos sincronizados entre os membros do time.

- Além de servir como hospedagem, o Github possui muitas integrações com serviços que auxiliam no deploy da aplicação através de integração contínua.

>Fonte: https://blog.rocketseat.com.br/iniciando-com-git-github/
## Comandos

> Comandos básicos do Git

- git clone <url_repositorio> - Copiar o repositório para sua máquina
- git checkout -b funcionalidade_x - Cria uma nova branch com nome funcionalidade_x 
- git status - Apresenta o status atual da branch local
- git add - Adicionar novos arquivos na branch local
- git commit -m "Mensagem de Commit" - Cria um commit com mensagem para a branch local
- git push - Coloca todos os commits locais na branch do servidor
- git checkout <branch_desejada> - Retorna para branch desejada
- git fetch origin - Exibe todo o histórico do repositório no servidor
- git pull origin branch_xpto - Atualiza a branch local com todas as alterações existentes no servidor
- git diff <branch origem> <branch destino> - Exibe as diferenças entre as brancas
- git merge <branch_destino_desejada> - Faz merge entre a branch local com a branch de destino desejada
- git remote add origin <servidor> - Conectar seu projeto a um projeto que não foi feito checkout
> Fonte: https://rogerdudler.github.io/git-guide/index.pt_BR.html

## Suporte

Linkedin: <a href="https://www.linkedin.com/in/vitor-cardoso-/" target="_blank">`Vitor Cardoso`</a>

E-mail: `scardosovitor@gmail.com`

---

## Licença

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2020 © <a href="https://www.linkedin.com/in/vitor-cardoso-/" target="_blank">Vitor Cardoso</a>
