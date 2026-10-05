# Gerador de Gabaritos de Chicotes V2

## Novidades

- Analisa PDFs com texto pesquisável usando PDF.js.
- Localiza identificações de conectores.
- Procura dimensões numéricas próximas.
- Calcula confiança da associação.
- Sugere posição horizontal e direção.
- Permite revisar resultados antes de adicioná-los ao gabarito.

## Publicação no GitHub Pages

1. Substitua o `index.html` do repositório pelo arquivo desta versão.
2. Confirme o commit.
3. Aguarde a publicação do GitHub Pages.
4. Atualize a página com Ctrl+F5.

## Limitações

- PDFs digitalizados como imagem ainda não são lidos.
- A associação dimensão-conector é uma heurística por proximidade.
- Linhas e ramificações ainda não são reconhecidas.
- A biblioteca PDF.js é carregada pelo cdnjs. Se o domínio for bloqueado, a análise não funcionará.
- Todo resultado deve passar por conferência técnica antes de fabricação.
