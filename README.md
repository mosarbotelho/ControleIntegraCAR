Projeto IntegraCAR: Painel Interativo de Atividades
Este é um Painel Interativo de Acompanhamento (Single Page Application - SPA) para visualizar o progresso e as atividades detalhadas do Projeto IntegraCAR nos pilares de Infraestrutura, Capacitação, Fluxo Operacional e TI & Automação, com foco nos meses de Setembro e Outubro.

A aplicação utiliza HTML puro, Tailwind CSS (via CDN) para estilo, e Chart.js (via CDN) para gerar o gráfico de distribuição de atividades.

🚀 Funcionalidades Principais
Visão Geral (Overview Dinâmico):

Exibe a contagem total de atividades mapeadas no projeto.

Apresenta um Gráfico de Rosca que mostra a distribuição percentual das atividades entre os quatro pilares do projeto.

Navegação por Abas:

O conteúdo é segmentado em abas (Infraestrutura, Capacitação, Fluxo Operacional, TI & Automação) para facilitar a leitura e o foco em áreas específicas.

Fluxo Operacional Detalhado:

A aba de Fluxo Operacional exibe um diagrama sequencial de 6 etapas, ilustrando o processo completo de análise do CAR, desde o estudo de base até a finalização do processo (incluindo análise de documentos e mapas).

Entrada de Dados (TI & Automação):

A aba TI & Automação inclui um formulário interativo que permite ao usuário adicionar novas demandas de automação em tempo real.

Ao adicionar uma nova demanda, o painel é atualizado dinamicamente:

A nova demanda aparece na lista de "Demandas de Automação Mapeadas".

O contador de Total de Atividades na Visão Geral é incrementado.

O Gráfico de Rosca é recalculado para refletir o aumento das atividades no pilar "TI & Automação".

🛠️ Estrutura do Código
O projeto é contido em um único arquivo HTML (integracar_report_spa.html) seguindo o padrão de aplicação em arquivo único.

Componente

Uso

Tecnologia

Estilo

Layout e design responsivo.

Tailwind CSS (CDN)

Gráfico

Visualização da distribuição de tarefas.

Chart.js (CDN)

Navegação

Lógica de troca de abas e manipulação de classes.

JavaScript Puro

Interatividade

Adicionar novas atividades e atualizar contadores.

JavaScript Puro (Manipulação de DOM e dados)

🔗 Como Executar
Por ser uma SPA em arquivo único, basta abrir o arquivo integracar_report_spa.html em qualquer navegador moderno (Chrome, Firefox, Edge, etc.). Não é necessário servidor web ou dependências externas além das CDNs já incluídas.
