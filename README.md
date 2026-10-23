# Saber ENEM

Plataforma educacional estática feita com HTML, CSS e JavaScript puro, preparada para publicação no GitHub Pages.

## Arquivos
- `index.html`: estrutura, navegação e seções da plataforma.
- `style.css`: identidade visual, componentes e layout responsivo.
- `script.js`: biblioteca de materiais, busca e filtros, questões, correção comentada, indicadores temporários e interações de redação.

## Como executar
Abra `index.html` no navegador. Para uma verificação local mais próxima de hospedagem, sirva a pasta com um servidor estático (por exemplo, `python -m http.server 8000`) e acesse `http://localhost:8000`.

## Publicação no GitHub Pages
1. Coloque os três arquivos na raiz do repositório `Saber-ENEM`.
2. No GitHub, abra **Settings → Pages**.
3. Selecione a branch de publicação e a pasta `/ (root)`.
4. Aguarde a publicação e verifique `https://toriaestudando.github.io/Saber-ENEM/`.

Os arquivos CSS e JS usam caminhos relativos (`./style.css` e `./script.js`).

## Escopo atual do conteúdo
A plataforma inclui materiais desenvolvidos com explicações, exemplos e dicas em Linguagens, Humanas, Natureza e Matemática, além de questões autorais comentadas e recursos de estudo para redação. A biblioteca inicial é uma seleção curada, não uma cobertura completa de todos os tópicos possíveis do ENEM; ela pode ser ampliada pela lista `materials` em `script.js`. Os indicadores de questões duram apenas enquanto a página permanece aberta; não há login, cadastro, flashcards nem histórico persistente.
