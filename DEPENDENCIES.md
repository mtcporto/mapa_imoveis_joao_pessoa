# Dependências do mapa estático

O repositório contém a exportação HTML do mapa e arquivos de distribuição, sem fontes ou tarefas de compilação do Leaflet.markercluster. O manifesto desse componente mantém nome, versão e licença, mas não declara mais ferramentas de desenvolvimento do projeto upstream (Karma/Jake/Mocha etc.), que não são utilizadas nem distribuídas aqui. Não há tarefa de compilação a executar nesse diretório.

jQuery foi atualizado de 1.12.4 para 3.7.1, tanto na cópia separada quanto na versão incorporada ao HTML. Origem oficial: https://code.jquery.com/jquery-3.7.1.min.js. A cópia separada e não referenciada do JavaScript Bootstrap 3.3.7 foi removida; os estilos e ícones usados pelo mapa permanecem.

Dependabot está habilitado. Bibliotecas incorporadas em HTML não são integralmente cobertas por sua análise de manifestos.
