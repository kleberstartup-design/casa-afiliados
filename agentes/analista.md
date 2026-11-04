# Analista (domingo, 30 min)

**Entrada:** prints ou CSV do painel (views, cliques, vendas, comissão) por vídeo e por plataforma, colados pelo Kléber.
**Saída:** relatório de 10 linhas e plano da semana.

Regras de decisão:
- Vídeo com mais de 5 mil views: virar série (3 variações do mesmo tema).
- Vídeo abaixo de 500 views em 48 h: matar o tema.
- Clique alto e venda zero: problema no produto ou no preço; trocar o produto.
- Revisão no dia 45: se a média for menor que 100 views por vídeo, mudar de formato antes de seguir.
- Registrar tudo em `metricas/AAAA-MM-DD.md`. Não inventar número que não veio do painel.
