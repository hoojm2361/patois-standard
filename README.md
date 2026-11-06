# Patois Standard

An open, community-agreed orthography for Jamaican Patois, developed by
speakers, writers, and linguists across the Jamaican diaspora.

## Why this exists

Deepgram and other ASR systems transcribe Jamaican Patois with roughly
30–40% word error rate. To fine-tune a model that does better, we need
consistent training labels. Right now, every diaspora writer spells
Patois differently — *kyahn* / *cyaan* / *kyaan*, *bwoy* / *bwai*,
*ting* / *tingz*. That variation is fine for human readers; it's fatal
for training data.

This repository is where a small group of collaborators agree a shared
spelling convention, document it publicly, and use it to build the first
Patois training corpus that a community actually consented to.

## How we work

- **Discussions** — open questions, no decision yet. "How do we spell
  the negative particle?"
- **Issues** — a specific proposal needs investigating. "Should we
  accept both *bwai* and *bwoy* in the corpus?"
- **Pull Requests** — a concrete change to `STANDARD.md` that we're
  ready to debate and vote on.
- **`DECISIONS.md`** — every decision made, dated, with the rationale
  and who agreed.

## Scope

- **In scope**: spelling conventions, tone marking (or not), punctuation
- **Out of scope**: grammar, syntax, vocabulary choices — we're not
  writing a dictionary or a grammar; we're settling on how to write
  what people already say.

## Prior art

This work builds on the Cassidy/JLU orthography developed by Frederick
Cassidy (1961) and adopted by the Jamaican Language Unit at UWI Mona.
Our standard does not replace Cassidy/JLU — it documents how Cassidy/JLU
relates to the spelling that ordinary diaspora speakers actually use.

See `sources/` for reference documents.

## License

CC BY-SA 4.0. The standard is a public good.
