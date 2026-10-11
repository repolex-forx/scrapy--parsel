# Repolex Knowledge Graph of scrapy/parsel

RDF knowledge graph data for [scrapy/parsel](https://github.com/scrapy/parsel), parsed by [repolex](https://repolex.ai).

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
rlex download scrapy/parsel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8ee96b7239775b4dbf214fd17e51d49e95538f16
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8ee96b7239775b4dbf214fd17e51d49e95538f16
│           └── chunk-001.nq.gz
├── blob
│   ├── 0b3df8795a82bb42b9a119d89b3d437b1a17d365.nq.gz
│   ├── 1826912bbaf0043ef5306272ebfae6482fa527c9.nq.gz
│   ├── 1912c551c877b0553723ff3afb937b90d7ec512c.nq.gz
│   ├── 1f827b755335107b4572d602132300f5f1334251.nq.gz
│   ├── 2505266b4d8f84a5175f43e9b7ba677062ba312e.nq.gz
│   ├── 2a1abb2dc2549b0ecdf38dbae5f3b6e19ef848cb.nq.gz
│   ├── 39ec848961f008642d5a310d7921dfb31ac0859f.nq.gz
│   ├── 4264fd6b2791ec0d6d965d06a928126c73d767fa.nq.gz
│   ├── 4787b7e8030bf40fff070a9afabdb258dc218d19.nq.gz
│   ├── 4b656d6eef60a9bdb9591a532e7d4677197eb8da.nq.gz
│   ├── 4c807df9a5f5a8383ab77a36ad74b9079c0f4915.nq.gz
│   ├── 52324867a133cbaa7c8702d7d3d8c22249902e31.nq.gz
│   ├── 585b1d7342f832a4d1d452f45b810776d63613f8.nq.gz
│   ├── 5fb630341dfa6c87733d58862aed65cb405075cf.nq.gz
│   ├── 623d48cfa6b6f2ba551dde2435254ed5a1b63862.nq.gz
│   ├── 64113e366a676f7f526361a8f048c586fabcf81f.nq.gz
│   ├── 64e9e3a961c440f31aa1e033f433d17164c05243.nq.gz
│   ├── 6ead05eced18b8703d19b6b5fb1860da86843cd4.nq.gz
│   ├── 6ecf97c4828adb240548dfd198aa70da7172cfac.nq.gz
│   ├── 752d1a94701645b2ef150794bb6cec12a6e70230.nq.gz
│   ├── 75bfe0e325401e729d0c778794c05059fc189c75.nq.gz
│   ├── 75fb24cae3855e9b06bcc766a7c731eb1f364709.nq.gz
│   ├── 852e6a360be8b3bee9b39643e7649388899f8475.nq.gz
│   ├── 859e4ba6927ccc801d8358ef08d251f17f39d480.nq.gz
│   ├── 8838fd0609615d09471dcf827b36d23d6a807851.nq.gz
│   ├── 8f3b2400adb2c21281858251c15d77e798913f0d.nq.gz
│   ├── 95211b9a94491b2b0ea31ae00411f55ecdb39b41.nq.gz
│   ├── 9af9f454bef13dd6c9bddec6ab04c72786668f1c.nq.gz
│   ├── 9bad34d237352bcbb2574788bd835ac571a46fb8.nq.gz
│   ├── a291217496023ee819582c8b232b1c82c3792a77.nq.gz
│   ├── b4256076008d5536388c094acfbbc337e7e61118.nq.gz
│   ├── c789aa4a8acdff3f36a28b160bb10c8ca4b93e84.nq.gz
│   ├── d7bb37ab4dbe45343ba4bb5420f0e7e38f5086ce.nq.gz
│   ├── dcdeee8833233e79d3e0f30f9e1d183a29e9459f.nq.gz
│   ├── dd7655b8cc8710d88ebf3c4ec0dab1e9ae85e0b0.nq.gz
│   ├── e2ee038d8b68a50ec8453c744ae23ccdfd24cba2.nq.gz
│   ├── e37b17fa4340aed0d990fe41be0fdd2d892ab395.nq.gz
│   ├── e4a566e1d08cc3a1eb2fadb78339484806622c45.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e75c099dc1cc23514f71442da201e3d5b3ca5d3c.nq.gz
│   ├── ee81d9f571eef9289d7f4ec2b5f88a8671ca80ec.nq.gz
│   ├── f076a831c6f585b9b5d13aa35bf931df8334c9f3.nq.gz
│   ├── f1319634629509cbce9613cd46f57a50b37e2efb.nq.gz
│   ├── fa9aa073043a91de162b405b89b800f0c5881f9a.nq.gz
│   ├── fad34986087c893ba59e298cbe9e4bcce8e6f385.nq.gz
│   └── fb9e74529156e98f6398f1aed42368ef0975a0c5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8ee96b7239775b4dbf214fd17e51d49e95538f16.nq.gz
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

[scrapy/parsel](https://github.com/scrapy/parsel)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
