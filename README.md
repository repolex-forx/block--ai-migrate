# Repolex Knowledge Graph of block/ai-migrate

RDF knowledge graph data for [block/ai-migrate](https://github.com/block/ai-migrate), parsed by [repolex](https://repolex.ai).

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
rlex download block/ai-migrate
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 573536ef6a640726b3bf7f950724b17f193984ea
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 573536ef6a640726b3bf7f950724b17f193984ea.nq.gz
│   └── repolex
│       └── 573536ef6a640726b3bf7f950724b17f193984ea
│           └── chunk-001.nq.gz
├── blob
│   ├── 001b6dadcde01cfec95fb1bdcb63022f44a4e215.nq.gz
│   ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
│   ├── 0803b8cb4c01450a51b19209557ab1b32e9e3b7b.nq.gz
│   ├── 081cbe83449cf8e625a3e2e79b6b35415c4e1503.nq.gz
│   ├── 092dc87199367f4d06ec3c67b3fc3898c6043e4b.nq.gz
│   ├── 1e0ac7a2bf8d36e78fc7fd5302f8df6864b3ca7d.nq.gz
│   ├── 1effc3ec30548d69097a0ac9add527c253e0fbe5.nq.gz
│   ├── 25dbac399c9c447eecfd597ee39e2cef6d703f58.nq.gz
│   ├── 29de030fffa468bb7feb047c85b8e57e0180229d.nq.gz
│   ├── 2a5029fe41578b253262adeb9c7f3f0a858b97d9.nq.gz
│   ├── 31559b7d115e3c105b328cce9b9dcd9774025061.nq.gz
│   ├── 3622a637a0ce96118abd1a1e26b13abc6c375a5c.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 3a72515893dfc6123d349045e9008e80c8611056.nq.gz
│   ├── 3cd62220739cf89ef70ed7013f0e13c2ddd95cc6.nq.gz
│   ├── 3d6323dc9eb730826300ae40f35afe131044b56a.nq.gz
│   ├── 3ffbf3cdc101b182edd95926de856ef916f91b6c.nq.gz
│   ├── 43c133c8eecd27a82c106d72319d100888b942c0.nq.gz
│   ├── 44f186d15d7ee6f666a731a16756f49c3cfe2f5d.nq.gz
│   ├── 479a27ddb022e7a8b41bd0bc4b1febb2c6054a9f.nq.gz
│   ├── 490735a44d22449c61e57f0e4bc41dbb3e10bb77.nq.gz
│   ├── 4fed3ea58b1c619ff9293d843d8eee5fbfb1f8e7.nq.gz
│   ├── 527f350820890555ee81d9ceac13e4fd46c0029e.nq.gz
│   ├── 59a4a589d07f6584d5b8c4d9f510e58630a39a8c.nq.gz
│   ├── 65dce00582e27268060e25473d6c58754ada6d32.nq.gz
│   ├── 66d8126ec0aa0d09b0e7b364f3b12c08d3a3671e.nq.gz
│   ├── 70232dab2cacfa146ee4886c84538263775ca106.nq.gz
│   ├── 7f8ba9a08add20d9b5a2ad015ded290f5556878a.nq.gz
│   ├── 881b6dc1a3c65f31a8bdb44ad05e4b3ebc6a2437.nq.gz
│   ├── 92bba033a65f75c871e69de85ecbbe98e41cbeae.nq.gz
│   ├── 96fd6231aeff523f9112b8b51f54211b5e15e577.nq.gz
│   ├── 9790052bf1cb4f56d8f561e3d200792c6fdd3219.nq.gz
│   ├── 9f0c4fcd52ae535fa8b0c19b0be1a770dbd47171.nq.gz
│   ├── 9f69d32873138b3e3209d8b7faa5f35bad98e7e9.nq.gz
│   ├── a438b6c247ae71845350faaa1456dd30a93eb85e.nq.gz
│   ├── a5b196fad3b1f6f8d3ee1a22f567ac04a463f904.nq.gz
│   ├── a65ced06cf5137810a6aafb1761a9558442c050c.nq.gz
│   ├── abeaf77be0b54f50b4deded522c4ce606ccb96d4.nq.gz
│   ├── b07e1119ca026674c660090e1a4d5aa62debb7d5.nq.gz
│   ├── b57831ee421d6adc437ca47045aa2df5abb7d584.nq.gz
│   ├── ba2c0c27555a005c0838c357ed4734df6bdda3d8.nq.gz
│   ├── bc1ada674cdf6b345a9be3e0d9a083895e4fccb7.nq.gz
│   ├── c474906e309397417fd73054f2faa6174e893ac8.nq.gz
│   ├── c544cbe86dbaaf9f9edd1490fd8e32488fa54814.nq.gz
│   ├── c7ffad163dc7e73221b59dd62455445a87fe3054.nq.gz
│   ├── ca2adcf3c822ee573f8f3ed94be6d3143718d88b.nq.gz
│   ├── d15dde484ed76cc91a84968f16ed9cfc80e631a1.nq.gz
│   ├── d54fd8d51cbf857286d7c37cb46ecbc7b187b795.nq.gz
│   ├── d6b3e6be5314ffb61be31d0d745b18a3606a3025.nq.gz
│   ├── d904a88aae1a6f244ef8af14f02afda13ad10691.nq.gz
│   ├── e4f862e452b129ee437df465ee2deb3fa0c7fe18.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── f1a82070ed98123e06790a2b6faf4e469f6eaf17.nq.gz
│   ├── f4824f70b83be6abce186e7cef86301c137865a8.nq.gz
│   ├── f73be85e3f88e3cfc772569d9ee7eabe041cdce9.nq.gz
│   ├── fb8152781c31307adeda632286934dd3502a5815.nq.gz
│   ├── fccf7cc02fb5573c0b9466039897deb0b2c32a74.nq.gz
│   └── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 573536ef6a640726b3bf7f950724b17f193984ea.nq.gz
├── filetree
│   └── 573536ef6a640726b3bf7f950724b17f193984ea.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 68 files
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

[block/ai-migrate](https://github.com/block/ai-migrate)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
