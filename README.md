# Repolex Knowledge Graph of zopefoundation/transaction

RDF knowledge graph data for [zopefoundation/transaction](https://github.com/zopefoundation/transaction), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/transaction
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5c0e211b9029521daa91bc13ac52c2b01a7faa48
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5c0e211b9029521daa91bc13ac52c2b01a7faa48
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a3d3cf3d76c6de84a1bcd5ee0621f852b225343.nq.gz
│   ├── 188120b692cc972bed5f7063baaa7ebd9dd5fcea.nq.gz
│   ├── 19e1d260cad0857e85f107b9221507d51026eecc.nq.gz
│   ├── 2700e03b17662e30c12e6d997fc62d0142bcf67c.nq.gz
│   ├── 2ae6cdc04fd9bb815f9c0fe9419598d3445a7540.nq.gz
│   ├── 2b3893f437a3741b27fe56153f6cf2e0ac38088b.nq.gz
│   ├── 2f30952b672a16dd38af38dae6d4d1ae7e3d9292.nq.gz
│   ├── 33aad2e44a0488853271732c9e3799fbb3ee4d77.nq.gz
│   ├── 52baa1532dda8f90a66056da855543c138264d90.nq.gz
│   ├── 609b21f284d07a22fc1fb734a39992c1c44616cf.nq.gz
│   ├── 60d55ef68e4bafcc014513af0f42722fd6c93015.nq.gz
│   ├── 654a43e44f90cf03998556bf4b8352737ebd5079.nq.gz
│   ├── 776ba2c28686287e5ac52cdcf25f415275481b84.nq.gz
│   ├── 792d6005489ebee62cde02066f19c5521e620451.nq.gz
│   ├── 79859e06010bf4967c5b4b044afea6ef39742938.nq.gz
│   ├── 79a4fec714c5b2b620aca957d69e04ffaa081b4a.nq.gz
│   ├── 8a1cde635fcfe005cc4438d504940505395236a7.nq.gz
│   ├── 8ca13f08d7705a601bd3bd80e0f9010b2def4c6d.nq.gz
│   ├── 8f566a26538ed03fa5bbeb23bfbcb96e542020b6.nq.gz
│   ├── 968b13fd387e144157965afdaaee2dae279a13d7.nq.gz
│   ├── 96f7482dd0ad87f34529f4020974c8c2ead773e6.nq.gz
│   ├── 987de34b9cc46c1c7e7de9a5dbf9f5adc691498a.nq.gz
│   ├── 9c0e9a53ef2cb1a4176aec387b0478f9eeef927f.nq.gz
│   ├── a3df1ed2dc539d0590216374fb1488de65c3ecc6.nq.gz
│   ├── a8aab0fe81c59c4f76aeba9b030e0789dacbc514.nq.gz
│   ├── ae7a161f9413d996124a1b566bceb635c1b304de.nq.gz
│   ├── b1292b9d397b8940b7131e0126542bf2caa92852.nq.gz
│   ├── b49ff173db657a73bffc05a262e5a41a9606ce7e.nq.gz
│   ├── b6b0ca25f6657a47a82dbb96a943fdabcb5ede9d.nq.gz
│   ├── c67dc0ee90ac22877890f6a2b4e85d7a5db285c1.nq.gz
│   ├── c6dd2ea8fdedea067b8fc2c637d1ad9d612f7246.nq.gz
│   ├── c7491175d431a2105b1c491e8e7c20654cd20b73.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── d0ebe9c30d9b40f3be6294a2d1ec228108a2cf83.nq.gz
│   ├── d1f09d5c8a1c07d4a470c1cf40df4e6726c3bb47.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── dadcac2bb45447c188e8c801530929007b5fa9c9.nq.gz
│   ├── dd67283c99ab5ca4c8982a86e1e9c9053b177193.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e3579011e1a5792ed2adb52fe79f1ac001b9c3bf.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e938a24815ff9c06661bfa38ca5c91c387c96fe4.nq.gz
│   ├── f7f0de20daa95a760a9e0656e840db33729f528e.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   └── ffb19b3d92a86a216d36c4602481a46f01192740.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5c0e211b9029521daa91bc13ac52c2b01a7faa48.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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

[zopefoundation/transaction](https://github.com/zopefoundation/transaction)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
