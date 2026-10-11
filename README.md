# Repolex Knowledge Graph of agronholm/serge

RDF knowledge graph data for [agronholm/serge](https://github.com/agronholm/serge), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download agronholm/serge
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 12e2d63319d5e204eb0f757ae664dde58ce2023c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 12e2d63319d5e204eb0f757ae664dde58ce2023c
│           └── chunk-001.nq.gz
├── blob
│   ├── 003f9fe076681ce5400a60dbfacef2702cf3aba1.nq.gz
│   ├── 034f38c0b53aec5a249b2e9fb7f675f0e78ee298.nq.gz
│   ├── 06cf6cdf86b7edc56c4f2d7fd9066c3d5271c07d.nq.gz
│   ├── 084377a033b9432d29cf12cf6994c0bfa97b78ee.nq.gz
│   ├── 1260fb039a7a3278e5b94a45f2b5c6933789223c.nq.gz
│   ├── 1567720fdff658d2bdcb50f7e658f8c282cefa55.nq.gz
│   ├── 19e751991e0643f730e8dd66e9e22af31bcea2af.nq.gz
│   ├── 1bca150f9a7ea1939834fa15c12d985e9c670ab7.nq.gz
│   ├── 1fe9fa96ad1ca7b9a17d9466a95ac54a8968ab2d.nq.gz
│   ├── 24e477eb84aaa40076b76f9e2af3205654da6583.nq.gz
│   ├── 31b7de362c6d99bfc62da201d64d273e060a0b22.nq.gz
│   ├── 33ad091d26d8a9dc95ebdf616e217d985ec215b8.nq.gz
│   ├── 3582b368b27db83bdeb2a502b678cce4202eaed6.nq.gz
│   ├── 376ef1e02d425d4b08541edd52f12082b1ea3a44.nq.gz
│   ├── 39daaa88a96d01c6672da81efc28bd984db4fb01.nq.gz
│   ├── 5012be14999a7de11a1d051604490e784a6c4637.nq.gz
│   ├── 55e12e72f578bd5420c244e6866e71825dc059af.nq.gz
│   ├── 5835d4083e4b028e7934e72719b3da6a10c44681.nq.gz
│   ├── 5c1696d5b31d54e239513184c7cb1d66a9eada77.nq.gz
│   ├── 6635cf5542756197081eedaa1ec3a7c2c5a0b537.nq.gz
│   ├── 6769e21d99a63338394e47bc4c7d0aba1e88d5a5.nq.gz
│   ├── 6ae0c8c44d08a78140c9c62c1b0f745edd05e804.nq.gz
│   ├── 6fbd3c2153779ac10b8f010c56621b82d4e90c26.nq.gz
│   ├── 7110a4458a248a4b3108f5a16dc2608d06add5ba.nq.gz
│   ├── 7126d216a8a5ad47c8f1c0a9d678e51b363bd368.nq.gz
│   ├── 7391e7593f9e1a879abf67ecab80686e2688953b.nq.gz
│   ├── 76f67efdc6470081b512a8db5bf2b1d4962d9c3c.nq.gz
│   ├── 825b9e65af7c104cfb07089bb28659393b4f2097.nq.gz
│   ├── 82d3a433eccba355988b0a578a76ea54b6507a33.nq.gz
│   ├── 82e68c65521c6d9900f0dfff55ad77afa9aa220f.nq.gz
│   ├── 88ffea51f4a478a6504e34907ce060510f2182b8.nq.gz
│   ├── 894f98180172f71f37c2e342832ad292763e9748.nq.gz
│   ├── 8a59c0cb007fea904ee0ba8c309ab46fdf6ff5df.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8cef4f25d568edcde57584e4b1ee89cee730d012.nq.gz
│   ├── 9485ab4b47a49aed1012f5542653214daaaa3603.nq.gz
│   ├── b5c61c956711f981a41e95f7fcf0038436cfbb22.nq.gz
│   ├── b6f27f135954640c8cc5bfd7b8c9922ca6eb2aad.nq.gz
│   ├── b731a05a1af0ec5483124e4d2897f2d7349cb548.nq.gz
│   ├── c29b545c7d88c01bbb45f8f29bb8f24a4f558b21.nq.gz
│   ├── c9eb16a10b67b9163d2f9c1c86519f4c0954c896.nq.gz
│   ├── ccad3beac62ce9d7c5fd13da3f19427b7f6db679.nq.gz
│   ├── d295eabd29851295c305e1fc7a5e916a5ab95505.nq.gz
│   ├── da13f24116997927924dc5c569f7ca2be08e55b4.nq.gz
│   ├── dac95018a03a8bae3da7df3c86f3874f9e662c40.nq.gz
│   ├── e2b68ed7ee1acdbc673ba66c425324e7a09d9c6b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e82a87499ede7776bc2c6869a7dd2472a8d812b4.nq.gz
│   ├── f31a64b613b1033c10358616c9bdf7a30257a657.nq.gz
│   ├── f31eb8976a5e11227211b3c919a8919aaade2011.nq.gz
│   ├── f4b38985bde25a7aecbe49e6af0587d0c1323882.nq.gz
│   └── f59b884c51ed3c31fc0738fd38d0d75b580df5e4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 12e2d63319d5e204eb0f757ae664dde58ce2023c.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 58 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[agronholm/serge](https://github.com/agronholm/serge)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
