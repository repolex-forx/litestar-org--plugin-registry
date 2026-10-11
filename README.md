# Repolex Knowledge Graph of litestar-org/plugin-registry

RDF knowledge graph data for [litestar-org/plugin-registry](https://github.com/litestar-org/plugin-registry), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/plugin-registry
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 31c0ac397f4ef515bbae3d8652cd3c16b5647ddb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 31c0ac397f4ef515bbae3d8652cd3c16b5647ddb
│           └── chunk-001.nq.gz
├── blob
│   ├── 00f9651db49393818df6ad1ed227b2e3697df52c.nq.gz
│   ├── 04e785d0f4f1112705c05f7413fc63407580628f.nq.gz
│   ├── 09b15e9de6a7ecc4973abf3d032cf796acdad559.nq.gz
│   ├── 0c6a33dd1397a087ea63a48a6513774933b8a4bd.nq.gz
│   ├── 129fd5d535623e8bbd7ae3c40a5cf837b30ad6fa.nq.gz
│   ├── 157b466d97f8e765e9f8525b1d0c7f5f4019b817.nq.gz
│   ├── 1b60a0fef9be247b55b19fd12e907a6452f81c67.nq.gz
│   ├── 1c7aba37e9bcd988be165c7dc26284720e50f1c9.nq.gz
│   ├── 1f79d1512ab6798509dfde764b4fed7d21cb1a28.nq.gz
│   ├── 229143222178b9221d3354163ec492ca0cd50d4b.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 27b58e53da2df1fc2efff94d2a8f9ac8ba811ac4.nq.gz
│   ├── 2c8b0dad9fa065b42b90cb0f3994bdeb0642f73e.nq.gz
│   ├── 319a615bc3dbe519fd54fc19799c15a339c1de30.nq.gz
│   ├── 34857168686ba0f7830a5b6f37929ec57f32f52a.nq.gz
│   ├── 350cf26051967bd9055493a1b46b3818de837346.nq.gz
│   ├── 36761b15480b1e0375e0212b56db8ab80553acd1.nq.gz
│   ├── 42dd9f12f5707d408258692513e6cf5d2f51bc33.nq.gz
│   ├── 43aa91a246641faf81ce4e75ba048ce64c15de62.nq.gz
│   ├── 44a895e78cd6c66268b4998d34c49cb096e18d35.nq.gz
│   ├── 45ac612f770d3b3eef6d05415da7d31f4e472881.nq.gz
│   ├── 4e8ef9463d3b63822dd0974b38a4a83d0d66bee3.nq.gz
│   ├── 5d4342822fe886c47522bec34a19f4ebcb1efb9f.nq.gz
│   ├── 64b0bd806c1e3270c4221f5813cf8cd648c761f3.nq.gz
│   ├── 66be1462ebe8d2301e7063fe56b38f6891e98a40.nq.gz
│   ├── 6d4e0021f4381c84cad36cf159d10687e184a773.nq.gz
│   ├── 724a44e35b6ccdee32a642a141e2e214458ac6aa.nq.gz
│   ├── 734a55acf52a899d27ef80a995f9a758652c99ca.nq.gz
│   ├── 7360fa6761a3bfe0367fe3806b90ae33374243f5.nq.gz
│   ├── 7b65a51e58245e383dc20e9a4cdacef4796f18a8.nq.gz
│   ├── 85acd88f77b05be9047c28c7a1a9cec196bfd80b.nq.gz
│   ├── 94aa28ac651fff88d6d8f9d53c94d848485d717a.nq.gz
│   ├── 976bf62f2e36b5a26e25075a34eda812d394b798.nq.gz
│   ├── 9d76808af2ba5b2d40470222302c193b75211950.nq.gz
│   ├── a0f7ea5a96aaf3c6d7d8a883fb4fda08a64dbb46.nq.gz
│   ├── a21ed224c0506aac42facc648658a9f73eec6b31.nq.gz
│   ├── afad7979037f58fa92f77c3febf6524e3f3e7d2f.nq.gz
│   ├── b40521b5466ac6efee8e9654bbb92a3e80a22fb3.nq.gz
│   ├── bd7bb530e3d92cc4356bcffcd8813648ad23ad7e.nq.gz
│   ├── cdccd244a3800188fb7c31b819b8cbe03363d354.nq.gz
│   ├── cf6e81f7f22fabef972cda8cd2b97172bfad474f.nq.gz
│   ├── d98e3659c3951644332a98a69f36240acf49a582.nq.gz
│   ├── e20f51229034217116c0f4bcf1b0d7befbb29104.nq.gz
│   ├── e226ecc3befb91fbf1f629aa2a6b6cebdf577a5e.nq.gz
│   ├── e300e764f403f169c6075d92860ac1bb7a11c2ff.nq.gz
│   ├── e341e0d374e9da55a38876a32c9def26484778a0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8c1b27f3861d1fce7b86597bf4f51f7f15d453d.nq.gz
│   ├── f1cb291bf2c83a59b7821d012c13e1f093204ee7.nq.gz
│   ├── f5b8de98a677b90450276b368aa340314b81451f.nq.gz
│   └── fa63757625f7eb2045a4c97f70c97c8650e687d2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 31c0ac397f4ef515bbae3d8652cd3c16b5647ddb.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 58 files
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

[litestar-org/plugin-registry](https://github.com/litestar-org/plugin-registry)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
