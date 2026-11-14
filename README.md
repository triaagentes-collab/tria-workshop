# TRIA Workshop · Raio-x da empresa + Construção com IA

Bem-vindo à **TRIA (Tríade da Inteligência)**. Esta pasta transforma o Claude no seu parceiro de workshop:

1. **Parte 1, com a Cris:** o Claude faz o **Raio-x da sua empresa** (Canvas da TRIA). Ele desenha o mapa ENTRADA · DENTRO · VOLTA, acha onde a empresa depende de você e fecha com a sua **Ficha de Passe**.
2. **Parte 2, com o William:** quando o William liberar no palco, o Claude monta um **plano de ação**, você aprova, ele **constrói** (site, banco de dados e projeto guardado no GitHub), testa e te entrega dizendo exatamente o que fez.

Você não precisa saber programar.

---

## Como começar (3 passos)

### 1. Baixe esta pasta
Nesta página do GitHub, clique no botão verde **`<> Code`** → **Download ZIP**.
Abra o arquivo baixado: vai aparecer a pasta **`tria-workshop-main`**. Arraste essa pasta para a sua **Mesa (Desktop)**.

> Sabe usar git? `git clone https://github.com/triaagentes-collab/tria-workshop.git` também serve.

### 2. Abra a pasta no Claude
Escolha **um** dos caminhos:

- **App Claude (Desktop)** → aba **Code** → escolha a pasta **`tria-workshop-main`** → comece uma sessão.
- **VS Code** com a extensão do Claude Code → **File › Open Folder…** → **`tria-workshop-main`** → abra o Claude.

Se o Claude perguntar se pode **confiar nesta pasta** ou **usar o servidor "tria"**, responda **sim**.

### 3. Escreva `oi`
Pronto. O Claude começa as perguntas. Responda do seu jeito, uma de cada vez.

- Quando um bloco terminar, espere a Cris e escreva **`próximo`**.
- O **código do evento** está no telão.
- No fim da Parte 1, o Claude **para e espera o William**. Quando o William liberar no palco, responda **`sim, quero continuar`**.

---

## O que você leva para casa
- O **mapa da sua empresa** e a **Ficha de Passe** (em `projetos/<seu-código>/canvas.md`).
- O **plano de ação** (em `projetos/<seu-código>/PLANO.md`).
- Um **site no ar** (`https://tria-<seu-código>-<nome>.pages.dev`).
- O **projeto guardado no GitHub** (`github.com/triaagentes-collab/tria-<seu-código>-<nome>`).

## Deu problema?
| O que aconteceu | O que fazer |
|---|---|
| O Claude não começou as perguntas | Escreva **`/comecar`**. |
| "Código do evento incorreto" | Confira o código no telão (letras e números). |
| "Ainda não foi liberado" | A Parte 2 só abre quando o William liberar no palco. Aguarde e escreva de novo. |
| O Claude diz que não acha o servidor "tria" | Feche a conversa, abra de novo e aceite o servidor **tria**. |
| A conversa caiu | Abra de novo na mesma pasta e escreva **`oi`**: o Claude continua de onde parou. |

## Para a equipe TRIA
- Cada participante recebe um **prefixo** (ex.: `limpezacarla_k7`). Tudo o que ele cria leva esse prefixo: tabelas `limpezacarla_k7_*` no banco, sites `tria-limpezacarla-k7-*` e repositórios `tria-limpezacarla-k7-*`.
- Nenhuma chave fica neste repositório. O acesso passa pelo **porteiro** (`https://tria-porteiro.tria-workshop.workers.dev`), que confere o código do evento e a liberação da Parte 2.
- As regras completas do Claude estão no [`CLAUDE.md`](CLAUDE.md). O Canvas original está em [`docs/`](docs/).
