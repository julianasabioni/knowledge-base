# knowledge-base

Camada de conhecimento consolidado — conteúdo que já passou pela fase de estudo, foi filtrado, organizado e vale manter como referência.

> Se ainda está em processo de aprendizado, o lugar é um repositório `estudos-*`. Aqui entra o que já virou conhecimento estável.

## Estrutura

```
knowledge-base/
├── arquitetura/
├── banco-de-dados/
├── cloud/
├── engenharia-de-dados/
├── ia/
├── programacao/
├── linux/
└── git/
```

| Pasta | Conteúdo |
|---|---|
| `arquitetura/` | Decisões estruturais, padrões de organização e design (ex.: organização de repositórios, arquitetura de sistemas) |
| `banco-de-dados/` | Modelagem, normalização, conceitos consolidados de bancos relacionais e não relacionais |
| `cloud/` | Conceitos e boas práticas de provedores cloud (GCP, AWS, etc.) |
| `engenharia-de-dados/` | Pipelines, pyspark, airflow, data quality — conhecimento já validado na prática |
| `ia/` | Conceitos consolidados de IA, LLMs, prompt engineering, agentes |
| `programacao/` | Boas práticas e conceitos de linguagens e paradigmas já dominados |
| `linux/` | Administração, shell, conceitos de sistema |
| `git/` | Fluxos de trabalho, convenções e boas práticas de versionamento |

## Conteúdo atual

- [`arquitetura/organizacao-github.md`](arquitetura/organizacao-github.md) — guia de organização de repositórios no GitHub (estudos, experimentação, projetos, portfólio)

## Quando algo entra aqui

Segundo a regra de decisão do guia de organização:

- **É conhecimento já consolidado?** → `knowledge-base`
- Se ainda está em formato de anotação solta ou aprendizado em andamento, prefira `estudos-*` ou `learning-log` até amadurecer.

## Convenções

- Um arquivo `.md` por assunto, nomeado de forma descritiva (`kebab-case`).
- Prefira conteúdo revisado e sem lacunas — este repositório é para consulta, não para rascunho.
- Ao mover algo de um repositório de estudos para cá, remova o material redundante do repositório de origem ou deixe um link apontando para a versão consolidada.
