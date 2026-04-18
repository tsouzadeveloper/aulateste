
## Batalha Naval - Posicionamento de Navios (Nível Novato)

------------------------------

Este projeto é uma implementação técnica em linguagem C que simula a lógica de posicionamento de embarcações em um tabuleiro de Batalha Naval. O foco principal é demonstrar o uso de matrizes, loops aninhados e manipulação de índices para representação de dados em grade.
## 🚀 Funcionalidades

* Tabuleiro 10x10: Representação matricial robusta utilizando tipos primitivos.
* Renderização Dinâmica: Sistema de exibição no console com coordenadas alfabéticas (A-J) e numéricas (1-10) para melhor UX.
* Lógica de Posicionamento:
* Inserção de navios de forma horizontal e vertical.
   * Uso de loops for para evitar redundância de código ao preencher as células.
* Tratamento de Alinhamento: Formatação de saída para garantir que a grade permaneça estruturada mesmo com números de dois dígitos.

## 🛠️ Tecnologias e Conceitos Aplicados

* Linguagem C: Base do projeto.
* Matrizes (Arrays Multidimensionais): Armazenamento do estado do jogo (0 para água, 3 para navios).
* Estruturas de Repetição: for para inicialização e renderização do tabuleiro.
* Manipulação de Coordenadas: Lógica de transposição de índices para o posicionamento estratégico.

## 📋 Como Executar

   1. Certifique-se de ter um compilador C (como o GCC) instalado.
   2. Salve o código em um arquivo chamado batalha_naval.c.
   3. Compile o código via terminal:
   
   gcc batalha_naval.c -o batalha_naval
   
   4. Execute o programa:
   
   ./batalha_naval
   
   
## ⚓ Visualização do Jogo
O sistema imprime no console uma grade organizada, onde:

* 0 representa as áreas de mar aberto.
* 3 representa as partes integrantes das embarcações posicionadas.

------------------------------
Desenvolvido como parte dos desafios de lógica de programação em C.
------------------------------

