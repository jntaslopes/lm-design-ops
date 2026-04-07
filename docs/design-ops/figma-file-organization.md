# Guia de Organização de Arquivos no Figma

## Objetivo

Padronizar como projetos de produto são organizados no Figma para facilitar colaboração entre Design, Produto e Engenharia.

## Referência visual de projeto

Este padrão foi calibrado usando como referência visual o projeto compartilhado:
[LM Mobilidade no Figma](https://www.figma.com/files/team/1450851516371517780/project/499329596?fuid=1553118248689460826).

## Regra

Todo projeto deve ter arquivos de design no formato:

Nome oficial do arquivo:

`Prototype [Sufixo]`

Sufixos permitidos:

- `Ready for Dev`: itens que entram em sprint para implementação.
- `Validation`: telas e fluxos ainda em validação.
- `Draft`: estágio de trabalho interno do time de Design.
- `Exploration AI`: estágio anterior ao `Draft`, com exploração/geração assistida por IA.

### Nota de escopo

No contexto da referência visual, `Flow` é um arquivo de FigJam.
Documentação de padrão para FigJam está fora do escopo atual deste guia.

## Exemplos

Exemplos válidos:

- `Prototype [Ready for Dev]`
- `Prototype [Validation]`
- `Prototype [Draft]`
- `Prototype [Exploration AI]`
- `Prototype [Ready for Dev]` + `Prototype [Draft]` + `Prototype [Exploration AI]` no mesmo projeto, com estágios diferentes em paralelo.

Exemplos inválidos:

- `Prototype Ready for Dev` (faltam colchetes)
- `Prototype [Ready to Dev]` (sufixo não permitido)
- `Prototipo [Draft]` (nome base incorreto)
- `Prototype [Discovery]` (sufixo não permitido)

## Checklist

Antes de considerar um arquivo pronto para o estágio atual, valide:

- O nome segue exatamente `Prototype [Sufixo]`.
- O sufixo usado está na lista oficial de sufixos permitidos.
- O conteúdo do arquivo condiz com o estágio informado no sufixo.
- Não usar o arquivo `Flow` (FigJam) como parte da convenção de nome dos `Prototype`.
