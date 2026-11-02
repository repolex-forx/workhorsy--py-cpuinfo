# Repolex Knowledge Graph of workhorsy/py-cpuinfo

RDF knowledge graph data for [workhorsy/py-cpuinfo](https://github.com/workhorsy/py-cpuinfo), parsed by [repolex](https://repolex.ai).

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
rlex download workhorsy/py-cpuinfo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f3f0fec58335b9699b9b294267c15f516045b1fe
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f3f0fec58335b9699b9b294267c15f516045b1fe
│           └── chunk-001.nq.gz
├── blob
│   ├── 002c77fa67604c2d4436fd3c52f8b56f4df33fc5.nq.gz
│   ├── 03de2161258fc24619802fb45e1d4b990bc7df9e.nq.gz
│   ├── 15b5c8f85ed0b2479d25a6696f80ee116ccaebdb.nq.gz
│   ├── 18b8638be0776eb74a0589f66c8604bf92cc4246.nq.gz
│   ├── 21ffef5cb60731331b90580c55e1253db4e75114.nq.gz
│   ├── 27fdfd1313f911154ad1f2745cfea31aa21ec6f7.nq.gz
│   ├── 291080ed47ed604ccf84904b49ea2b8037f88b7e.nq.gz
│   ├── 33c702e9b82a2680e95e5ad763055223dbabbb47.nq.gz
│   ├── 33e18d73e109c5ce629b35cc50d9c71eb9b14414.nq.gz
│   ├── 34e6c68b6b8ac6de43dfe50c6b5de6beabe09b2a.nq.gz
│   ├── 36c95f634416a82ae6b9d72c6dc2d8fd8ec45155.nq.gz
│   ├── 382cfe1b8944830ebb7231a4509e31d7fd0b75dd.nq.gz
│   ├── 38438c121a8731fcf91c7cb6cb268baccf24fc4c.nq.gz
│   ├── 396c3be4310d9d3541ca0832cdecb86a187435af.nq.gz
│   ├── 3a52bdb9a7f407fef85800319e1ee2f7824fdc29.nq.gz
│   ├── 3e4073b7aca8b90f9cc57c1a5b4e4d73d1715ae5.nq.gz
│   ├── 467548a1e9131c38fbd50989f19a1bb50a4341ba.nq.gz
│   ├── 4805b298c209575bd14efe219cd4355ca1be6005.nq.gz
│   ├── 4caaae15eabff73e69350e2a121aefbaf2dbab59.nq.gz
│   ├── 4cc1188f09ef8bbcc76f29add2bd5b3f1a3cc3e1.nq.gz
│   ├── 4cebd3c0dd539be1b8e18029b1846a068c2603f8.nq.gz
│   ├── 4d3bb6749c0df63f084e0f266068b01ee7fc2500.nq.gz
│   ├── 4d9c8d1d039ce8d8e57d9d8e50e9f8ceb16e03c4.nq.gz
│   ├── 4e61ed2f0f9d15ff5b53e8898f4b22c72339ab55.nq.gz
│   ├── 5256e8bef55f599e4f5e2e3066d9259479f6a4ca.nq.gz
│   ├── 526aeb2816a8828b67172dd003c7a33b123f205e.nq.gz
│   ├── 534f2de0f4bf48203c0cb46d587f71d632714a03.nq.gz
│   ├── 58a92d5cfdc9fa30656c4783ef48b1c8315264d6.nq.gz
│   ├── 61f164ff2897bc34cd5b1ced3055ae0cfb570e72.nq.gz
│   ├── 61fd9d2bb402df1114c6b74e5fad46eafbe0c6eb.nq.gz
│   ├── 6209d41ae6895c84edfd7c1685d351ca89ee94ac.nq.gz
│   ├── 66d1624b0bb7decae8cfa60c637642cc05460860.nq.gz
│   ├── 67744438a72a31c0eec8862c3d3c1ba4078bcac9.nq.gz
│   ├── 6b27fe77df4b6f229d59dc0ad1579b3518c54968.nq.gz
│   ├── 76ea01192a86a5d63c0fb8a0c25250023bf7f236.nq.gz
│   ├── 7809093f727f923c93d5c1efcbb519235dc042e3.nq.gz
│   ├── 7d4756baacd2cdc658c226d0c9ae1b0a7e8cd870.nq.gz
│   ├── 7da42b9b89783ec856d2e851603074311e1ee53c.nq.gz
│   ├── 7ec2fe9a9fe260a0356ef1ab7ac0eb9dc5f7a21f.nq.gz
│   ├── 808931586e520ea7eb88738e09101f9ec0fae276.nq.gz
│   ├── 87324ed7b4d96b25ab90edf52c136f66f710992d.nq.gz
│   ├── 8e9c683799fe11b453c1f07dec9c97e6b234d84e.nq.gz
│   ├── a62496d3287e578d2ee21dd85dd507f3d2b2cb10.nq.gz
│   ├── a6b19850388dd814256bf1bc411047809a01b978.nq.gz
│   ├── adc2a9493e90a28700d1dd70b36ea917aed7b25f.nq.gz
│   ├── af9ca5bcf589ce2cb68e2d1ac6ed87497a6d2ca1.nq.gz
│   ├── b143f0474303ea3940c3966f5e2a90f0b66e2560.nq.gz
│   ├── b41890492697180dcf8a991123b1e57b42954f53.nq.gz
│   ├── b56d8e0e762f687e6efa1d7c51d9fbfaf7e3e4ba.nq.gz
│   ├── b57f5a452c8c7a84487d900cb9740a456d35c8e7.nq.gz
│   ├── b748e3e7f3235cd4fe1d0d085627a3e511302b2e.nq.gz
│   ├── bb273ed0602c3b8ad102c54ef19b13ff3ce9c924.nq.gz
│   ├── bb59222418ca8e133ea06a77ce5bff9c3f8eeedd.nq.gz
│   ├── ca83b5fd9fab3d3e86d89112618364770c310412.nq.gz
│   ├── d94fbe1e7e11b2ae01a3cd58b3e639015cdaef11.nq.gz
│   ├── dbfb62fdb7b037be47c5b35685d30f454e7f77a9.nq.gz
│   ├── dc51122570ac6cf411f70a8ee910339512ccdd18.nq.gz
│   ├── dd56d50afa783633a517697b25e68f9cfe1ba0a0.nq.gz
│   ├── e0a5f979032e563d81cb6eab41872d4fe27a5390.nq.gz
│   ├── e28ef90f795ac05e5e7df8f434a6c50782feda22.nq.gz
│   ├── ec5bafd6277f8096075c6ac69469d1fe67fd981f.nq.gz
│   ├── f1cf8ad9a829687f36a3a8e7c9448012bdb7c306.nq.gz
│   ├── f3f6542cf751471853d2c6f844e90b37a16deae0.nq.gz
│   ├── fa0d93438adcee59e6b32cb1f2b3c21038b49431.nq.gz
│   └── fb9a3a192ac870675428f51e8e9420bfbd154ca9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f3f0fec58335b9699b9b294267c15f516045b1fe.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 73 files
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

[workhorsy/py-cpuinfo](https://github.com/workhorsy/py-cpuinfo)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
