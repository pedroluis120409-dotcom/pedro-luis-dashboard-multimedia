# MediaHub IA — Portal de Ferramentas Multimédia

**Disciplina:** Oficina de Multimédia — 12.º Ano — CRSI  
**Ano letivo:** 2026/2027  
**Autor:** Pedro Luís  
**Turma:** 12.º B  
**Repositório:** [pedroluis120409-dotcom/PedroLuis-dashboard-multimedia](https://github.com/pedroluis120409-dotcom/PedroLuis-dashboard-multimedia)  
**Aplicação Web:** [Inserir aqui o link do GitHub Pages ou Streamlit Cloud depois da publicação]

## 1. Visão geral do projeto

O MediaHub IA reúne, numa única página Web, ferramentas interativas para apoiar atividades escolares: um quiz de conhecimentos, um gerador de palavras-passe e um organizador de equipas. O objetivo é disponibilizar estas funcionalidades num dashboard simples e visualmente coerente.

**Proposta escolhida:** [Indicar Proposta 1 ou Proposta 2]

## 2. Estrutura do código e funcionalidades

A aplicação foi construída num único ficheiro HTML. O CSS, responsável pelo aspeto visual e pela adaptação do layout, e o JavaScript, responsável pela interação, estão incluídos nesse ficheiro; não existem ficheiros `app.py` ou `style.css` separados.

As funcionalidades integradas são:

- **Quiz multi-tema:** apresenta uma ronda de dez perguntas, baralha perguntas e opções, contabiliza pontos, respostas certas e séries, e dá feedback.
- **Gerador de palavras-passe:** permite gerar uma palavra-passe aleatória com opções de comprimento e caracteres, ou uma frase-passe; inclui botão para copiar e um indicador visual de força.
- **Organizador de equipas:** distribui os nomes inseridos por duas a quatro equipas e atribui nomes, lemas e cargos conforme a área selecionada.

O quiz foi inspirado num trabalho realizado em aula. Para o widget de palavras-passe foi consultado o site da 1Password, e para o organizador foi usada como referência a ideia de um gerador de equipas. As funcionalidades e conteúdos foram reunidos e adaptados ao dashboard.

O indicador de força da palavra-passe é uma estimativa visual simples, não uma análise de segurança certificada. As funcionalidades identificadas como “IA” na interface usam regras e conteúdos definidos no próprio código; a página não faz chamadas a um serviço de IA em tempo real.

## 3. Registo de utilização da IA

Os exemplos abaixo descrevem pedidos adequados às tarefas deste projeto. São reconstituições, não transcrições literais de prompts anteriores; devem ser substituídos pelos prompts originais se estes tiverem sido guardados.

### 3.1 Prompt para conversão Web/HTML

> Converte a proposta do meu dashboard escolar numa página HTML5 funcional, com CSS e JavaScript integrados. Organiza a página em secções claras e garante que os controlos são interativos e que o layout se adapta a ecrãs diferentes.

### 3.2 Prompt para ampliação de funcionalidades

> Amplia o dashboard com três ferramentas: um quiz de dez perguntas com pontuação e feedback, um gerador de palavras-passe com opções personalizáveis e um gerador que distribui participantes por equipas de acordo com o curso. Mantém as funcionalidades integradas na página e apresenta mensagens claras ao utilizador.

### 3.3 Dificuldades e erros corrigidos com IA

A integração de três ferramentas diferentes numa só página exigiu organizar o conteúdo em secções e manter os controlos e resultados de cada widget claros. Não foi fornecido um registo de erros concretos corrigidos com IA; por isso, não são atribuídas correções específicas à IA sem confirmação.

### 3.4 Otimização do layout

Um pedido de design adequado a registar seria:

> Organiza o dashboard em cartões separados, melhora a leitura com espaçamento consistente e bom contraste, usa uma paleta azul e verde, e torna os botões e controlos fáceis de identificar. Mantém o layout adaptável a telemóveis.

## 4. Estrutura de ficheiros do repositório

- [`Trabalho multimedia dezembro.html`](<./Trabalho multimedia dezembro.html>) — página principal; contém HTML, CSS e JavaScript.
- `README.md` — relatório e descrição do projeto.

Não existem, neste repositório, ficheiros separados `index.html`, `app.py` ou `style.css`, nem uma pasta de assets. Para experimentar a aplicação localmente, abre o ficheiro HTML num navegador.

## 5. Reflexão crítica e aprendizagem

O que correu melhor foi conseguir reunir ferramentas diferentes num só dashboard e reutilizar ideias de atividades e recursos que já conhecia. A maior dificuldade foi integrar o quiz, o gerador de palavras-passe e a distribuição de equipas sem tornar a página confusa. A Inteligência Artificial pode ajudar a transformar ideias em código, sugerir melhorias de organização e explicar erros; ainda assim, é importante testar o resultado, confirmar que funciona e adaptar as sugestões ao projeto.
