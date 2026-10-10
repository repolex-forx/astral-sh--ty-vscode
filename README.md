# Repolex Knowledge Graph of astral-sh/ty-vscode

RDF knowledge graph data for [astral-sh/ty-vscode](https://github.com/astral-sh/ty-vscode), parsed by [repolex](https://repolex.ai).

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
rlex download astral-sh/ty-vscode
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 83712be51e27fc83566353d4cd7b22e3a9925159
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 83712be51e27fc83566353d4cd7b22e3a9925159
│           └── chunk-001.nq.gz
├── blob
│   ├── 014835144877ea9c926d027ece3e1a26290cf481.nq.gz
│   ├── 0a21a6043cb01beb639a6f01be3514dfa711f984.nq.gz
│   ├── 0b7b4e1b379177597273139ff7fb3ad5a1b9dfd6.nq.gz
│   ├── 1716e00ea0335b8d4b6f86a0f7483d46bd93fdca.nq.gz
│   ├── 1faf63d1e51eb4d12b7ade7142d35c39e7db94b6.nq.gz
│   ├── 1febb9f87852428471ec13a4cdb408996116bf21.nq.gz
│   ├── 2eb0c2181f34272e5a0d356e835593b694388e08.nq.gz
│   ├── 311ecaf8ffc2b6dfc5a178d014c3bdd2e34e959b.nq.gz
│   ├── 40beab648910e00ef8539e17425c38d746fb3a75.nq.gz
│   ├── 43fbe36b9b1b52aac61a8c95a96fbb7120d49f03.nq.gz
│   ├── 44ea751b4ea0470c2dab83327c170fa1f3dcec8e.nq.gz
│   ├── 455ce9557f87d95978538ea2b1ceed53c17265da.nq.gz
│   ├── 4561e703288c76f01919d64e5ffe3f334e7e591f.nq.gz
│   ├── 4870bea32326f818eeff6c814f9b7a860d8628ee.nq.gz
│   ├── 48babdc38f520784d784e7da263009f05602509e.nq.gz
│   ├── 496c608870e307f8f6f7cf7d137d3df764f2d370.nq.gz
│   ├── 49bb6730d72253f5582654ae03df1312adbf857a.nq.gz
│   ├── 515f2bd04a4c497a7dbc3b376ff7974407d08c6f.nq.gz
│   ├── 57dbdae42d37d5323806c24cefef6387b5770610.nq.gz
│   ├── 59432d46db0870a1d9afb8d74b4978162f038ff7.nq.gz
│   ├── 6ada25a3072424d00ce2ff415ed23ecf3ad363f8.nq.gz
│   ├── 6b923d6105c2ae45cf3defc3a205610780952133.nq.gz
│   ├── 6c6ab76d510d7c3e03e560dda7d83b91aa06fed5.nq.gz
│   ├── 6fcae5df9f30c66cf249935b9d0e1b02d13d807c.nq.gz
│   ├── 7163fe73daf7290b68d7bde753e55b962c718c6b.nq.gz
│   ├── 78cbf410a5cd43cc7702f71764d1efde59ff68fe.nq.gz
│   ├── 84c7440a3d77d41b9e5ee379d80f50d7a5457ece.nq.gz
│   ├── 85fa0d711274c77c1712b5e75cf001e9ca03e24f.nq.gz
│   ├── 8fac7295bdfa49c1cc291d1fe224894319ff991f.nq.gz
│   ├── a0bbfe3fe3d2d55a0db387927a4ec5aebbe6b7c2.nq.gz
│   ├── a22c5b4c3b6ca35b1c0dd77eb32ff3fd542c7905.nq.gz
│   ├── a338ab9ae8ee98d9791e16c1dcbbbcfbc3a17058.nq.gz
│   ├── ab36e8ce86fc392e609eb535c6f97acc5bde331a.nq.gz
│   ├── bb452adff76d8709fcb5cec4e14bf672f4e2fcb5.nq.gz
│   ├── c2dfc1afc8b3adb947e943d308fbee56e24302ce.nq.gz
│   ├── c36bd32d501b4a078999d0397315a788c29f5a86.nq.gz
│   ├── c55bead1cee00599702cd5a186b4c60816e59129.nq.gz
│   ├── cbc9bf2e0e59a81b6656b41e2cadc04a1383daf6.nq.gz
│   ├── ce360f78dcc05196e81d0d832a3ab1f51ba8d7c1.nq.gz
│   ├── cefd3d4e5a2704bda4c47929a3efdd16daed0ee0.nq.gz
│   ├── cfbbf7ce8eb10ccefcc68dd15e9b06dcd890926f.nq.gz
│   ├── d241d32069b7bf5606def5199888002be4e92f9b.nq.gz
│   ├── d4698529ffb4a7553ccede196cd16ab9e0a59ab2.nq.gz
│   ├── d63a59ce281aa34aded56588ffe33e0d2e3a1aea.nq.gz
│   ├── e2b6893e8a96576b85cfac4c0ec7e776d898bca2.nq.gz
│   ├── e3d361b42085bb1b89928ca56dfd9a30f5f336ad.nq.gz
│   ├── e5d1e8f2d280647aa62b107b34fb9b46d567321c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb3c92a81cbf637454b641d6abab878a57d315c6.nq.gz
│   ├── ec923af956a44859b2de7aa36e18f2ba9cba23ae.nq.gz
│   ├── ee1d7e4a7850beb1d555795408dbd20a4e0f428b.nq.gz
│   ├── efe022bc6ef7bf9cb6eed9d9aa07557b9b7921b4.nq.gz
│   └── fa8b9765fd0fec0c50760b918cfc2a346d5adb81.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 83712be51e27fc83566353d4cd7b22e3a9925159.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[astral-sh/ty-vscode](https://github.com/astral-sh/ty-vscode)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
