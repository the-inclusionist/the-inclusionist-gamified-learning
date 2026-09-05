# The Inclusionist — aprendizagem gamificada

> ## ⚠️ ESTE REPOSITÓRIO ESTÁ VAZIO. O SISTEMA AINDA NÃO FOI CONSTRUÍDO.
>
> Ele existe porque o endereço está **declarado em registro**, e endereço declarado é onde o
> trabalho pode ser arquivado — a regra anterior (criar só no primeiro commit) deixou o backlog de
> seis sistemas no rastreador da engine, parecendo trabalho da engine. Ver **ADR-0067**.
>
> **Esta advertência sai no commit que a desmentir.** README que mente sobre estar vazio é pior do
> que repositório vazio.

## O que é

As **atividades** — que se comportam como minijogos dentro dos jogos e por isso se chamam
ATIVIDADES — mais o gerador de questões.

O profissional autora atividade com escopo no estudante que ele atende (ADR-0052): é **dado**, na
forma do ADR-0032. Não é código, não é plugin, não vaza para o catálogo, não vaza para outro aluno e
**não alimenta a calibração de dificuldade**, que é derivada de população.

## Quem responde por ele

**Secretaria de Educação** — parte do sistema Inclusionista.

## O que precisa existir antes do primeiro commit de produto

- A fronteira de idioma do CLAUDE.md: o enunciado sempre traduz; em disciplina de idioma o
  **conteúdo linguístico** não traduz, porque ele é a matéria. A moldura mora na chave, o conteúdo
  atravessa por `{param}`.
- Quem assina a atividade autorada aparece com registro profissional visível (ADR-0052).

## Licença

Código: **AGPL-3.0-or-later** (ADR-0064) — o `LICENSE` desta raiz.
⚠️ **A arte NÃO é AGPL.** Programa é o que a Lei 9.609 define; arte segue a Lei 9.610 e pertence a
quem a fez. O que governa o quê está em `docs/LICENSES.md`, na engine.

⚠️ **A titularidade patrimonial é do MUNICÍPIO** (Lei nº 9.609/1998, art. 4º), não do desenvolvedor.
A publicação do código é objeto de **pedido** no requerimento — ato do Poder Executivo — e por isso
este repositório é **privado** (ADR-0066 §3).

---

Decidido em: **ADR-0058** (topologia) · **ADR-0066** (hospedagem) · **ADR-0067** (criação).
Os registros vivem na engine, em `docs/2-Architecture/adr/` — **não** há pasta `adr/` aqui, e isso é
decisão (ADR-0068 §5): trezentos lugares para decidir arquitetura são trezentos lugares para
contradizer o que já foi decidido, caladamente.
