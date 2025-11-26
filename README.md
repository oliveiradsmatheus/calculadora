## 🧠 Calculadora Interativa em JavaScript

💻 **Disciplina:** Linguagens de Programação I  
📚 **Curso:** Ciência da Computação — FIPP / UNOESTE  
👨‍💻 **Autor:** Matheus Oliveira da Silva  

---

### 📖 Sobre o Projeto

Este projeto consiste no desenvolvimento de uma **calculadora web interativa** capaz de realizar **equações matemáticas simples** (adição, subtração, multiplicação e divisão).

O foco principal do desenvolvimento foi a **manipulação da árvore DOM** (Document Object Model) e o **controle de eventos em JavaScript** para criar uma experiência funcional e responsiva. A interface foi estilizada com **CSS** para ser amigável e esteticamente agradável.

---

### 🎯 Objetivos

- **Manipulação DOM:** Utilizar JavaScript para ler entradas do usuário e atualizar o visor da calculadora.
- **Controle de Eventos:** Implementar *event listeners* para processar cliques nos botões numéricos e de operação.
- **Lógica de Cálculo:** Desenvolver funções em JavaScript para executar as operações básicas.
- **Interface e Estilização:** Construir uma **interface amigável** utilizando **HTML** e **CSS** (Grid/Flexbox).
- **Funcionalidade de Tema:** Incluir um botão para alternar entre os temas **Escuro** e **Claro** (*Dark/Light Mode*), demonstrando manipulação de variáveis CSS.

---

### ⚙️ Funcionalidades Principais

- 🔢 **Operações Básicas:** Realiza Adição (`+`), Subtração (`-`), Multiplicação (`×`) e Divisão (`÷`).
- 🧠 **Controle de Estado:** Gerenciamento do estado de cálculo (`calculado = true/false`) para permitir que novos números substituam o resultado anterior ou continuem a equação.
- 🎨 **Seleção de Tema:** Botão para alternar entre o **Tema Escuro** (padrão) e **Tema Claro**, alterando dinamicamente as variáveis de cor CSS.
- 🔙 **Controle de Visor:** Funções para **Limpar** (`C`) o visor e **Apagar** (`<`) o último caractere.

---

### 💡 Implementação da Lógica (JS)

A lógica central da calculadora utiliza:

1.  **Funções Separadas:** Cada operação básica (`soma`, `subtracao`, etc.) é encapsulada em sua própria função.
2.  **Função de Orquestração (`operacao`):** Uma função genérica que recebe dois números e a função da operação a ser executada, demonstrando o uso de **funções como argumentos**.
3.  **Processamento da Expressão (`calcular`):** A função `calcular()` percorre a string do visor, identifica o primeiro operador, separa os dois operandos (`a` e `b`) e invoca a função de operação apropriada através de um `switch`.
4.  **Troca de Tema (`trocarTema`):** Usa `classList.toggle` e a manipulação de `root.style.setProperty` para alterar as **variáveis CSS** (custom properties), garantindo a troca de tema eficiente.

---

### 🖼️ Apresentação

![calculadora](imagens/calculadora.gif)
