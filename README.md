# 📒 Agenda de Contatos em C

Este projeto é uma agenda de contatos desenvolvida em linguagem C, utilizando conceitos fundamentais da programação estruturada, como:

- Structs
- Vetores
- Funções
- Manipulação de strings
- Modularização
- Busca e remoção de dados

O sistema funciona diretamente no terminal e permite cadastrar, listar, buscar e remover contatos.

---

# 🚀 Funcionalidades

✅ Adicionar contatos  
✅ Listar todos os contatos  
✅ Buscar contato pelo nome  
✅ Remover contato  
✅ Controle de limite máximo de contatos  
✅ Comparação de strings usando `strcmp()`  
✅ Organização do código em funções

---

# 🛠️ Tecnologias Utilizadas

- Linguagem C
- Biblioteca `stdio.h`
- Biblioteca `string.h`

---

# 📂 Estrutura do Projeto

```bash
agenda-contatos/
│
├── main.c
└── README.md
```

---

# 📌 Estrutura do Contato

Cada contato possui:

```c
struct Contato {
    char nome[50];
    char email[50];
    char tel[30];
};
```

---

# ▶️ Como Executar

## 1. Compilar o programa

No terminal:

```bash
gcc main.c -o agenda
```

---

## 2. Executar

### Linux / Mac

```bash
./agenda
```

### Windows

```bash
agenda.exe
```

---

# 📋 Menu do Sistema

```text
===== MENU =====
1 - Adicionar contato
2 - Listar contatos
3 - Buscar contato
4 - Remover contato
5 - Sair
```

---

# 🔎 Funcionalidades Explicadas

## ➕ Adicionar Contato

Permite cadastrar:

- Nome
- Email
- Telefone

O sistema verifica se o nome e o email são iguais usando:

```c
strcmp()
```

---

## 📃 Listar Contatos

Exibe todos os contatos cadastrados no sistema.

---

## 🔍 Buscar Contato

Busca um contato pelo nome digitado.

---

## ❌ Remover Contato

Remove um contato da agenda utilizando deslocamento de elementos do vetor.

---

# 🧠 Conceitos Aplicados

| Conceito | Aplicação |
|---|---|
| Struct | Armazenamento dos contatos |
| Vetores | Lista de contatos |
| Ponteiros | Controle do total de contatos |
| Funções | Modularização do sistema |
| Strings | Comparação e entrada de dados |
| Loops | Navegação no menu e buscas |
| Condicionais | Controle das operações |

---

# 📸 Exemplo de Uso

```text
Digite o número máximo de contatos: 3

===== MENU =====
1 - Adicionar contato
2 - Listar contatos
3 - Buscar contato
4 - Remover contato
5 - Sair
Escolha uma opcao: 1

--- Adicionar Contato ---
Digite o nome: Gabriel
Digite o email: gabriel@email.com
Digite o telefone: 61999999999

Contato adicionado com sucesso!
```

---

# 📚 Objetivo do Projeto

Este projeto foi desenvolvido para praticar:

- Programação em C
- Manipulação de arrays e structs
- Modularização com funções
- CRUD básico no terminal

---
<!-- colocando readme.md para maior facilitação no uso desse programa  -->
# 👨‍💻 Autor

Desenvolvido por G.Dickson  
Engenharia de Software 🚀
