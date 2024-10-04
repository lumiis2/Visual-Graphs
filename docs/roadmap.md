# Visual Graphs - Roteiro Interno

Este documento interno tem o objetivo de acompanhar o progresso do projeto Visual Graphs e delinear os próximos passos de desenvolvimento.

Regras:
 - separar em dias.
 - ter tópico de próximos passos com datas.
 - anotar por reunião
 - commits e nomes de arquivo e etc. em inglês, documentação interna em português

---

## Dia 04/10 - Primeira Reunião: Definição das Ideias Iniciais

### Brainstorming

**Algoritmos que queremos implementar**:
- DFS (Busca em Profundidade)
- BFS (Busca em Largura)
- Dijkstra
- Kosaraju (Componentes fortemente conectados)

**Decisões de tecnologia**:
- Linguagens a serem utilizadas: C++ e Python
- Bibliotecas visuais: Pesquisar e definir bibliotecas que atendam nossas expectativas em termos de renderização gráfica e animação (em python/c++).

### Funcionalidades e Interface

- **Configuração de Atalhos e Estilos**:
  - Modos de estilo para os programa (ex: light mode/dark mode).
  - Atalhos configuráveis para facilitar a navegação e as ações no ambiente gráfico.

- **Interação do Usuário**:
  - A interação deve ser restrita ao desenho direto do grafo (drag-and-drop).
  - Interface intuitiva, semelhante ao **Draw.io** (_Gabriel_ opinar).

- **Representação Visual**:
  - Exibir visualmente vértices e arestas conectando-os.
  - Incluir um menu de formas geométricas para criar os nós e arestas de forma intuitiva e visual.

- **Menu de Estilos**:
  - Opção para alterar o estilo dos elementos selecionados (cor, espessura de linha, forma dos nós, etc.).
  - Definir estilos padrão a priori, permitindo que o usuário personalize seu grafo antes de desenhar.

- **Opções de Fundo**:
  - Fundo customizável com as opções: vazio, grid (grade), pontilhado.

- **Botão de Configurações**:
  - Menu de configurações gerais para ajustar preferências do usuário, atalhos, temas, etc.

### Funcionalidades Adicionais

- **Login de Usuário**:
  - Implementar um sistema de login para salvar preferências e progresso dos projetos.

- **Banco de Dados e Exportação**:
  - Armazenamento de dados:
    - Possibilidade de salvar gráficos como imagem (visual).
    - Exportação para XML para salvar os atributos e configurações, permitindo que o usuário retome um projeto antigo.

### Modularidade e Expansão

- Criar um "esqueleto" modular para o projeto, que permita fácil expansão no futuro.
  - Exemplo: novos algoritmos, novos tipos de grafos e novas funcionalidades gráficas podem ser adicionadas com facilidade.

### Estética Latex

- Ter a possibilidade de exibir os gráficos com uma estética similar ao **LaTeX** (para uma apresentação mais acadêmica ou formal).

---

### Definindo Passos Futuros

**Para dia 12/10**: 

Responsável: _Luisa_ , _Gabriel_
1. **Pesquisa sobre o que já é feito nesse estilo**:
   - Avaliar bibliotecas e projetos já existentes no estilo que estamos pensando.
   - Pesquisar bibliotecas usadas por essas soluções e identificar pontos de partida.
   - Definir as linguagens e bibliotecas com base na pesquisa, com a ideia de ter **três opções** de bibliotecas para testar.

2. **Desenhar e definir o design final**:
   - Esboçar a interface e aparência final da aplicação (ferramentas, cores, layout, etc.).

3. (Passo a ser definido).

---

Essas ideias servirão de base para o desenvolvimento do projeto, e cada uma delas será detalhada conforme o progresso.
