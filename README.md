# 📚 Sistema de Cadastro de Alunos

## 📌 Sobre o projeto

O **Sistema de Cadastro de Alunos** é uma aplicação web desenvolvida utilizando HTML, CSS e JavaScript. O objetivo é permitir o gerenciamento simples de uma turma de alunos, possibilitando cadastrar nomes e notas, consultar registros e visualizar a situação de cada estudante.

O projeto foi desenvolvido com foco na prática de conceitos fundamentais de desenvolvimento web e manipulação do DOM com JavaScript.

## 🚀 Funcionalidades

- **Cadastro de alunos:** permite adicionar alunos informando nome e nota.
- **Validação de dados:** verifica se o nome foi preenchido e se a nota está entre 0 e 10.
- **Classificação automática:** identifica se o aluno está aprovado ou reprovado.
- **Busca de alunos:** permite pesquisar alunos pelo nome.
- **Remoção de alunos:** permite remover um aluno da turma com um clique duplo sobre seu registro.
- **Atualização dinâmica:** atualiza a tabela automaticamente após alterações.
- **Mensagens de feedback:** informa ao usuário se uma operação foi realizada ou se ocorreu algum erro.

## 🛠️ Tecnologias utilizadas

- **HTML5:** estruturação da aplicação.
- **CSS3:** estilização e organização visual.
- **JavaScript:** lógica de programação, validações e manipulação do DOM.

## 📂 Estrutura do projeto

```text
cadastro-alunos/
│
├── index.html
├── estilo.css
└── script.js
```

## ⚙️ Como executar o projeto

1. Faça o download ou clone este repositório:

```bash
git clone URL_DO_REPOSITORIO
```

2. Abra a pasta do projeto no VS Code.

3. Execute o arquivo `index.html` no navegador.

Não é necessário instalar dependências ou configurar um servidor.

## 📖 Conceitos praticados

Durante o desenvolvimento foram utilizados conceitos importantes de JavaScript:

- Arrays e objetos.
- Funções.
- Estruturas condicionais (`if/else`).
- Estruturas de repetição (`for...of`).
- Métodos de array (`push`, `splice`, `filter` e `indexOf`).
- Manipulação do DOM.
- Eventos (`submit`, `input` e `dblclick`).
- Validação de formulários.
- Criação dinâmica de elementos HTML.

## 📊 Regra de aprovação

A situação do aluno é determinada automaticamente de acordo com sua nota:

| Nota | Situação |
|---|---|
| Maior ou igual a 6 | Aprovado |
| Menor que 6 | Reprovado |

## 🎯 Objetivo educacional

Este projeto tem como finalidade consolidar conhecimentos básicos de desenvolvimento web, especialmente a integração entre HTML, CSS e JavaScript, aplicando conceitos de lógica de programação em uma situação prática.

---

**Desenvolvido para fins acadêmicos e de aprendizado.**
