<h1 align="center">ERP Financeiro Pessoal — Dashboard Estratégico</h1>

<p align="center"><b>Do dado bruto à decisão:</b> um dashboard que mostra onde está o problema, o que fazer primeiro e se os dados são confiáveis.</p>

<p align="center">
  <a href="https://luiscarlossoarespro-cyber.github.io/erp-financeiro-pessoal/"><img src="https://img.shields.io/badge/%E2%96%B6%20Ver%20dashboard%20ao%20vivo-abrir%20demonstra%C3%A7%C3%A3o-5ee0a0?style=for-the-badge" alt="Ver dashboard ao vivo"></a>
  <a href="https://luiscarlossoarespro-cyber.github.io/"><img src="https://img.shields.io/badge/Portf%C3%B3lio-outros%20projetos-6fa8ff?style=for-the-badge" alt="Portfólio"></a>
  <a href="https://www.linkedin.com/in/luiscarlos-log/"><img src="https://img.shields.io/badge/LinkedIn-conectar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<!-- ARRASTE O VÍDEO AQUI (linha de baixo) -->


https://github.com/user-attachments/assets/fa39d502-ed7c-4e7b-b598-df693a0cb624



[![Prévia do dashboard — clique para abrir a demonstração ao vivo](assets/cover.png)](https://luiscarlossoarespro-cyber.github.io/erp-financeiro-pessoal/)

<p align="center"><sub>Demonstração com <b>dados 100% fictícios</b>. Nenhum dado financeiro real está neste repositório.</sub></p>

---

## O problema

Controlar finanças em planilha costuma parar no "quanto entrou e quanto saiu". O que realmente importa é outra coisa: **onde está o gargalo, o que fazer primeiro e se as decisões estão funcionando.** Sem isso, os mesmos erros se repetem todo mês.

## O que o dashboard responde

| Pergunta | Onde a resposta aparece |
|---|---|
| Qual é o maior problema agora e qual decisão resolve? | **Centro de comando** e **Gargalos** |
| Para onde foi o dinheiro e onde dá para cortar? | **Movimento** e **Onde está o dinheiro** |
| Quais contas venceram, subiram fora do normal ou estão duplicadas? | **Alertas** |
| Quanto devo, para quem e quando vence? | **Dívidas** |
| Quanto cada banco cobrou em tarifas e juros? | **Bancos** |
| O plano do mês está sendo cumprido? | **Sprint** e **Decisões** |
| Posso confiar nesses números? | **Confiança dos dados** |

## Destaques

- 🎯 **Centro de comando** — resultado do mês, comprometimento da renda, maior gargalo e próxima decisão em uma tela
- 🚨 **Auditoria automática** — aponta contas vencidas, aumentos fora do padrão e lançamentos duplicados
- 📅 **Movimento do dinheiro** — gráfico anual (realizado x previsto), fluxo diário e calendário com filtros
- 🧭 **Plano de decisões** — cada gargalo vira uma tarefa com prioridade, em ciclos curtos (sprint)
- ✅ **Confiança dos dados** — 7 verificações de qualidade antes de qualquer decisão
- ✨ **Visual com movimento** — números e gráficos surgem ao rolar a página ou trocar o filtro

## Como foi feito

| Etapa | Ferramenta |
|---|---|
| Base de dados e cálculos | Google Sheets |
| Dashboard | HTML, CSS e JavaScript (gráficos próprios, sem bibliotecas) |
| Desenvolvimento | Apoio de IA (Claude) a partir das regras e indicadores que eu defini |
| Métodos | Gestão ágil (sprint, backlog, kanban) aplicada às finanças |

## Resultado

O controle deixa de ser "olhar o saldo" e vira uma **rotina mensal de decisão**: cada problema encontrado gera uma ação com valor em jogo, prioridade e status.

<details>
<summary><b>Detalhes técnicos</b> (para quem quer ver por dentro)</summary>

<br>

- **Fonte:** 3 cadastros no Google Sheets (Receitas, Despesas e Dívidas), lançados no dia a dia.
- **Camada de cálculo:** duas abas de gestão (Gestão Estratégica e Decisões · Sprint) calculam tudo com fórmulas (LET, ARRAYFORMULA, FILTER, MAP/LAMBDA, QUERY). O dashboard só lê, não recalcula: uma única fonte da verdade.
- **Qualidade:** 7 verificações automáticas (campos vazios, vencidos, duplicidades) geram um índice de confiança.
- **Estrutura do dashboard (12 blocos):** Centro de comando · Gargalos · Caminho estratégico · Movimento · Onde está o dinheiro · Alertas · Dívidas · Bancos · Sprint · Decisões · Ficha e busca · Confiança.
- **Versões:** `index.html` é a versão atual (demonstração com dados fictícios). A versão 1 fica como histórico: `dashboard.html` (painel ligado à planilha real, por isso abre sem dados fora do Claude) e [`demo.mp4`](demo.mp4) (vídeo da versão 1).

</details>

## Próximos passos

Saldo real por conta, metas anuais e uma versão em Power BI.

---

<p align="center">
<b>Luis Carlos Machado Soares</b> · mais de 16 anos em operações e logística, aplicando Análise de Dados à tomada de decisão<br>
<a href="https://www.linkedin.com/in/luiscarlos-log/">LinkedIn</a> · <a href="https://luiscarlossoarespro-cyber.github.io/">Portfólio</a> · <a href="https://github.com/luiscarlossoarespro-cyber">GitHub</a>
</p>
