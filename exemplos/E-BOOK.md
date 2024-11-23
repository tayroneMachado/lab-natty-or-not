## E-book: Aprenda JavaScript para Desenvolvimento Web - Guia para Iniciantes

## Introdução

Bem-vindo ao mundo do JavaScript! Este e-book foi projetado para iniciantes que desejam aprender JavaScript com foco no desenvolvimento web. Você irá aprender conceitos fundamentais, praticar com exemplos e resolver atividades práticas para reforçar seus conhecimentos.

## Estrutura do E-book

## O e-book é dividido em módulos, e cada módulo contém:

## Conteúdo teórico: Explicação clara dos conceitos.

## Exemplos práticos: Demonstrações aplicáveis ao desenvolvimento web.

## Atividades: Exercícios para praticar o que você aprendeu.

## Desafios extras: Para quem quiser ir além do básico.

## Módulo 1: Introdução ao JavaScript

O que é JavaScript?

Linguagem de programação voltada para a web.

Roda no navegador e permite interatividade nas páginas.

Parte essencial do trio de tecnologias web: HTML, CSS e JavaScript.

Como usar JavaScript no navegador

Abra o navegador (exemplo: Google Chrome).

Acesse o console de desenvolvedor (pressione F12 ou Ctrl + Shift + J).

Escreva códigos diretamente no console para testar.

Exemplo:

console.log("Hello, World!");

Atividade Prática

Abra o console do navegador.

Digite console.log("Estou aprendendo JavaScript!");.

Observe o resultado.

## Módulo 2: Variáveis e Tipos de Dados

O que são variáveis?

Contêiner para armazenar dados.

Declaradas com let, const ou var.

Exemplo:

let nome = "João";
const idade = 25;
console.log(nome, idade);

Tipos de Dados

String: Texto ("João")

Number: Números (25, 3.14)

Boolean: Verdadeiro ou falso (true ou false)

Atividade Prática

Declare uma variável nome e atribua seu nome a ela.

Declare uma variável idade e atribua sua idade a ela.

Exiba ambas as variáveis no console.

## Módulo 3: Operadores e Condicionais

Operadores

Aritméticos: +, -, *, /, %.

Comparativos: >, <, >=, <=, ==, ===, !=, !==.

Exemplo:

let a = 10;
let b = 5;
console.log(a + b); // 15
console.log(a > b); // true

Condicionais

Estruturas que tomam decisões com base em condições.

Exemplo:

let hora = 20;
if (hora < 12) {
  console.log("Bom dia");
} else {
  console.log("Boa tarde ou noite");
}

Atividade Prática

Declare duas variáveis: x e y.

Compare se x é maior que y.

Exiba mensagens diferentes com base no resultado.

## Módulo 4: Funções

O que são funções?

Blocos de código que realizam uma tarefa.

Exemplo:

function saudacao(nome) {
  return `Olá, ${nome}!`;
}
console.log(saudacao("Maria"));

Atividade Prática

Crie uma função soma que receba dois números e retorne a soma.

Chame a função passando valores diferentes.

Exiba os resultados no console.

## Módulo 5: Manipulação do DOM

O que é o DOM?

Document Object Model: representa a estrutura de uma página web.

Selecionando Elementos

Por ID: document.getElementById("id")

Por Classe: document.getElementsByClassName("classe")

Exemplo:

<button id="meuBotao">Clique aqui</button>
<script>
  const botao = document.getElementById("meuBotao");
  botao.addEventListener("click", () => {
    alert("Você clicou no botão!");
  });
</script>

Atividade Prática

Crie um arquivo HTML com um botão.

Use JavaScript para exibir um alerta quando o botão for clicado.

Desafios Finais

Construa uma página simples que receba o nome do usuário em um campo de texto e exiba uma mensagem personalizada ao clicar em um botão.

Adicione estilos simples com CSS para melhorar a aparência.

## Conclusão

Parabéns por completar este e-book! Agora você tem uma base sólida para continuar explorando o desenvolvimento web com JavaScript. Pratique, crie projetos e nunca pare de aprender.
