# Ideias de micro SaaS no Brasil: 101 ideias em 15 nichos, com nota e fontes

Dataset aberto com 101 ideias de aplicativo e de micro SaaS para o mercado brasileiro, em 15 nichos. Cada ideia tem a
dor que resolve, o número de concorrentes encontrados, o preço que eles cobram e uma nota de 0 a 10 em quatro
critérios. As fontes de cada nicho vêm junto.

Pesquisa feita em 03/11/2026 com o [Gerador de apps do FakeForge](https://fakeforge.com.br/gerador-de-apps). A versão
navegável, com uma página por nicho, está em [fakeforge.com.br/ideias-de-app](https://fakeforge.com.br/ideias-de-app).

[English below](#english)

## Arquivos

| Arquivo | O que tem |
|---|---|
| `dados/ideias.csv` | Uma linha por ideia (101 linhas), em UTF-8 com BOM para abrir direto no Excel |
| `dados/ideias.json` | Os 15 nichos com as ideias, os achados conferidos na fonte e a lista de fontes |

Colunas do CSV: `nicho`, `publico`, `mercado`, `posicao`, `ideia`, `dor`, `nota`, `demanda`, `espaco_na_concorrencia`,
`disposicao_a_pagar`, `facilidade_de_construir`, `concorrentes_encontrados`, `preco_dos_concorrentes`,
`data_da_pesquisa`, `pagina`.

## Os números

- 15 nichos, 101 ideias, 1.097 fontes lidas.
- Maior nota: 6,5 de 10 (Agronegócio, Pets e Viagem e turismo).
- Média das notas por nicho: de 4,6 a 5,3.
- 11 ideias sem nenhum concorrente direto encontrado.

## Como a pesquisa foi feita

Para cada nicho, o Gerador de apps fez de 7 a 8 buscas na web e leu de 65 a 78 fontes: sites e páginas de preço de
concorrentes, notícias, fóruns e lojas de aplicativo. A partir disso, uma IA propôs de 5 a 8 ideias e deu a cada uma
uma nota de 0 a 10 em quatro critérios:

- **Demanda**: quanta gente tem a dor e procura solução.
- **Espaço na concorrência**: quanto espaço sobra entre quem já vende.
- **Disposição a pagar**: se o público já paga por algo parecido.
- **Facilidade de construir**: o esforço para uma pessoa ou um time pequeno colocar no ar.

A nota final é a média dos quatro. Ela compara as ideias de um mesmo nicho entre si; comparar notas de nichos
diferentes é aproximado.

## O que ficou de fora

- Páginas de reclamação de consumidor e os achados que só tinham esse tipo de página como fonte. Por isso a lista de
  fontes do JSON tem 878 endereços, e não os 1.097 lidos.
- Achados sem a marca de conferido na fonte.
- Qualquer dado de quem fez a pesquisa.

## Limites

- A nota é dada por IA, a partir do que estava publicado na web em novembro de 2026. Ela não diz se a ideia vai dar
  certo. Antes de construir, converse com quem tem a dor.
- Preços de concorrentes marcados com "≈" são estimativas da pesquisa, não preço conferido.
- O mercado muda. Confira concorrentes e preços antes de usar os números numa decisão.

## Licença

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.pt_BR). Pode copiar, adaptar e usar inclusive em
projeto comercial, citando a fonte:

> Paula, Everton. Ideias de micro SaaS no Brasil: 101 ideias em 15 nichos (03/11/2026). FakeForge.
> https://fakeforge.com.br/ideias-de-app

Para rodar a mesma pesquisa no seu nicho, com o público e o país que escolher:
[fakeforge.com.br/gerador-de-apps](https://fakeforge.com.br/gerador-de-apps).

---

## English

Open dataset of 101 app and micro SaaS ideas for the Brazilian market, across 15 niches. Each idea has the pain it
solves, the number of competitors found, what they charge, and a 0 to 10 score on four criteria: demand, room in the
competition, willingness to pay and ease of building. The sources for each niche are included.

Research run on 2026-11-03 with the [FakeForge app idea generator](https://fakeforge.com.br/gerador-de-apps). The data
is in Portuguese. Browsable version: [fakeforge.com.br/ideias-de-app](https://fakeforge.com.br/ideias-de-app).

- `dados/ideias.csv`: one row per idea (101 rows), UTF-8 with BOM.
- `dados/ideias.json`: 15 niches with ideas, source-checked findings and the source list.

Scores are AI-assigned from what was published on the web in November 2026 and compare ideas within the same niche.
Consumer complaint pages were left out of the sources. License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/),
with attribution to "Everton Paula, FakeForge, https://fakeforge.com.br/ideias-de-app".
