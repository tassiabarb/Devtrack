# DevTrack

Um projeto de aprendizagem para organizar estudos de programação, acompanhar tarefas e registrar a evolução de uma futura desenvolvedora Full Stack.

## Aula 1 — HTML e CSS

### Objetivo

Construir a primeira tela visual do DevTrack e praticar estrutura semântica, seletores CSS, Flexbox, Grid e responsividade. Nesta etapa, a tela é estática: os links e botões ainda não armazenam nem alteram dados.

### Estrutura atual

```text
devtrack/
├── css/
│   └── styles.css
├── index.html
└── README.md
```

- `index.html` descreve o conteúdo e sua organização.
- `css/styles.css` controla cores, tipografia, espaçamento, layout e adaptação a telas menores.

Abra `index.html` no navegador para ver a página. No VS Code, a extensão Live Server também pode servir a página localmente e atualizá-la quando você salvar alterações.

### Conceitos para observar

1. No HTML, `header`, `nav`, `main`, `section`, `article` e `footer` dão significado às diferentes partes da página.
2. Os atributos `class` conectam elementos a regras visuais no CSS; por exemplo, `class="stats-grid"` é estilizada pelo seletor `.stats-grid`.
3. `display: flex` organiza itens em uma direção; `display: grid` organiza conteúdo em linhas e colunas.
4. As regras `@media` mudam o layout em telas menores. Redimensione a janela para observar a navegação e os cartões se reorganizarem.
5. A barra `<progress>` usa `value` e `max` para comunicar progresso também de forma estruturada.

### Exercício antes da próxima aula

Personalize a tela sem adicionar JavaScript:

1. Troque “Dev Learner” pelo seu nome em todos os lugares em que aparece.
2. Altere a cor principal editando `--purple` no início de `css/styles.css`.
3. Mude o título de uma tarefa e o progresso de uma trilha. Atualize tanto o texto percentual quanto os valores `value` e `aria-label` da barra.
4. Teste a página em uma janela estreita e corrija qualquer problema visual que encontrar.

### Critérios de conclusão

- [ ] Você consegue localizar o conteúdo no HTML e a apresentação no CSS.
- [ ] A página abre no navegador sem depender de um servidor ou serviço externo (as fontes personalizadas são um aprimoramento opcional).
- [ ] Você personalizou o nome, a cor principal e pelo menos uma tarefa ou progresso.
- [ ] A página continua legível em uma tela estreita.
- [ ] Você consegue explicar, com suas palavras, a diferença entre Flexbox e Grid.

### Git desde o primeiro dia

Depois de configurar seu nome e e-mail do Git, registre a primeira versão:

```bash
git init
git add index.html css/styles.css README.md
git commit -m "feat: criar primeira tela do DevTrack"
```

Crie um repositório vazio no GitHub e conecte-o seguindo os comandos de configuração mostrados pelo próprio GitHub. Depois, envie sua evolução com `git push`. Nunca publique senhas, tokens ou outros segredos.

## Caminho de aprendizagem

| Etapa | Foco | Evidência de conclusão |
| --- | --- | --- |
| 1. HTML e CSS | Semântica, seletores, Flexbox, Grid e responsividade | Dashboard estático compreendido e personalizado |
| 2. JavaScript | Lógica, DOM, eventos, funções, arrays, objetos e `localStorage` | Tarefas podem ser criadas, concluídas e preservadas no navegador |
| 3. APIs | HTTP, JSON, `fetch`, Promises, `async/await` e erros | Dados remotos carregam com estados de carregamento e erro |
| 4. React | Componentes, JSX, props, estado, hooks e APIs | Interface dividida em componentes reutilizáveis |
| 5. Back-end Node.js | API REST, rotas, controllers, validação e CRUD | API de tarefas testada com operações completas |
| 6. Full Stack | React, API, banco de dados, autenticação e persistência | Aplicação integrada com dados persistentes por usuário |

Ao fim de cada etapa, revise os conceitos, conclua os exercícios e valide a compreensão antes de avançar.
