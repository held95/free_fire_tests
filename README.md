🏝️ Island Fire – Sistema de Mochila
Sistema interativo de inventário usando Vetor e Lista Encadeada (HTML, CSS e JavaScript)

Este projeto é uma simulação visual inspirada em jogos Battle Royale, onde o jogador gerencia itens dentro de duas estruturas de dados clássicas:

Vetor (Array) – capacidade limitada, ordenável, suporta busca binária.

Lista Encadeada – dinâmica, sem limite fixo.

O objetivo principal é apresentar, de forma prática e visual, como essas estruturas funcionam, comparando desempenho de buscas e manipulação de elementos.

🎮 Objetivo do Projeto

Este sistema foi criado para fins didáticos, permitindo que o usuário:

Adicione, remova e liste itens em duas mochilas distintas.

Compare o número de comparações entre:

busca sequencial em vetor

busca binária em vetor

busca sequencial em lista encadeada

Observe como ordenação, estrutura de dados e capacidade impactam o desempenho.

Visualize logs de ações em tempo real como um “diário de batalha”.

🧱 Estruturas Utilizadas
📌 1. Mochila Vetor

Implementada como um array JavaScript.

Limite de 10 itens.

Permite:

Inserção

Remoção

Busca sequencial

Ordenação por Selection Sort

Busca binária

Contadores de comparações são exibidos para análises de desempenho.

📌 2. Mochila Lista Encadeada

Implementada via objeto No contendo:

this.item = { nome, tipo, quantidade };
this.proximo = null;


Sem limite de capacidade.

Possui:

Inserção ao final

Remoção por nome

Busca sequencial

Também exibe contador de comparações.

🖥️ Interface

A interface é construída 100% em HTML + CSS, com visual inspirado em jogos de sobrevivência:

HUD com barras de vida e zona de perigo

Painéis futuristas com sombras e gradientes

Log das ações simulando rádio/comunicações

Layout responsivo (funciona em desktop e mobile)

⚙️ Funcionalidades Principais
✔️ Adicionar itens

O usuário preenche:

Nome

Tipo (arma, munição, cura, ferramenta)

Quantidade

E adiciona o item ao vetor ou lista encadeada.

✔️ Remover itens

A remoção é feita pelo nome exato.

✔️ Busca Sequencial

Percorre elemento por elemento exibindo quantas comparações foram feitas.

✔️ Ordenação (somente vetor)

Ordenação implementada com Selection Sort, comparando itens por nome.

✔️ Busca Binária (vetor ordenado)

Busca rápida, apropriada somente após ordenação.

✔️ Logs

Cada ação registrada com timestamp:

[14:32:11] Item "AK-47" adicionado ao vetor.

✔️ Renderização de inventário

Cada mochila é listada em uma tabela dentro de um painel estilizado.

📁 Estrutura do Código

O arquivo HTML contém:

🔹 Cabeçalho HTML

Metadados e carregamento do CSS.

🔹 Estilo (CSS)

Tema escuro, futurista, responsivo, com:

gradientes

sombras

painéis arredondados

componentes HUD

🔹 Corpo (HTML)

Seções:

Header com título

Painel HUD

Painel de inventários

Rodapé

🔹 Lógica (JavaScript)

Funções para:

Criar item

Inserir/Remover

Pesquisa sequencial e binária

Ordenação

Renderização das tabelas

Manipulação da lista encadeada

Sistema de logs

🚀 Como Executar

Salve o código em um arquivo .html

Abra o arquivo em qualquer navegador:

Chrome

Firefox

Edge

Opera

Não requer servidor, frameworks ou dependências externas.

📚 Objetivo Educacional

Este projeto é ideal para:

Trabalhos acadêmicos

Demonstrações em sala

Visualização clara de estruturas de dados

Entendimento prático de algoritmos de busca e ordenação

Comparação direta entre Vetor × Lista Encadeada

🛠️ Possíveis Extensões

Você pode evoluir o projeto com:

Sistema de pesos e capacidade total da mochila

Busca por tipo de item

Ordenação por quantidade

Gráficos de desempenho

Conversão para Typescript ou React

Backend simulando progressão do jogo

📝 Autor

Desenvolvido para fins educacionais, ilustrando conceitos de Estruturas de Dados dentro de uma ambientação temática de jogos battle royale
