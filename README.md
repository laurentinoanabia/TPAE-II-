# TPAE-II-

Projeto de extensão da disciplina TPAE II (UFPB) para atender uma demanda do **CORECON-PB**: um **site de glossário** com termos da economia explicados em linguagem simples para a população paraibana, em apoio ao programa **"PB sem dívidas"**.

Equipe 01: Ana Beatriz, Arthur Almeida e Gabriel Pinheiro. Orientador: Alessio.
Entrega final: banca no CORECON-PB em 15/12/2026.

## O que o site terá

- Glossário A–Z com busca.
- Verbetes agrupados por tema: preços e inflação, juros e crédito, trabalho e renda, dívidas e orçamento.
- Cada verbete: o que é, exemplo do dia a dia e por que importa.
- Perguntas frequentes e página sobre o projeto.

## Estrutura do repositório

```
index.html          site (estático, publicado no GitHub Pages)
data/glossario.json verbetes do glossário
docs/               plano de pesquisa e anotações
```

## Como adicionar um verbete

Edite `data/glossario.json` e acrescente um objeto com `termo`, `tema`, `definicao`, `exemplo`, `importa` e `fonte`. Toda definição deve citar a fonte.

## Como ver o site no seu computador

```
python3 -m http.server 8000
```

Depois abra http://localhost:8000.

## Histórico

A ideia inicial era educação financeira em escolas de João Pessoa. Em 22/10/2026 o escopo mudou para o site de glossário, a partir da lista de demandas do CORECON-PB.
