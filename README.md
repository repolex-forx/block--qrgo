# Repolex Knowledge Graph of block/qrgo

RDF knowledge graph data for [block/qrgo](https://github.com/block/qrgo), parsed by [repolex](https://repolex.ai).

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
rlex download block/qrgo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 450bf8305aa4a11e56b380686839b41dfe2efcda
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 450bf8305aa4a11e56b380686839b41dfe2efcda.nq.gz
│   └── repolex
│       └── 450bf8305aa4a11e56b380686839b41dfe2efcda
│           └── chunk-001.nq.gz
├── blob
│   ├── 03e53deb2d7036417196c2c5fb808774ca41c8e7.nq.gz
│   ├── 0c868f47b5bfa01b5de933970af1cfea97f33012.nq.gz
│   ├── 11ce2b0a9c7396d38883723fac61b5a2e7de1bb5.nq.gz
│   ├── 199ca3220aeed9e8a6c614fc81353e36a7abee2d.nq.gz
│   ├── 1aca35f536192941ad0de592663bf867c9387c86.nq.gz
│   ├── 1b23c095d99606e56d1593915341dc76e7aca127.nq.gz
│   ├── 1c53c09a988596b0391594424f20a2f3c457037c.nq.gz
│   ├── 20bc6efc04e89c11e4cb83e7041e31e9d1552c84.nq.gz
│   ├── 234cf759e66fccc07d3b302469f0a5c73df9c88f.nq.gz
│   ├── 25e8ed36e4b8916ce86c24aff35fc8999d2c550f.nq.gz
│   ├── 28e76866c0ceedc076e4a6dfb91a4fc524b6ccfa.nq.gz
│   ├── 2b3f1a56661ef807107b4447d81e827681376e56.nq.gz
│   ├── 2b7a412b8fa0fb7e985b0793321bd4e698f2b6cd.nq.gz
│   ├── 2bb9220371349a428983c34700fc93ee89bdaa0a.nq.gz
│   ├── 2dad4fc169854e2ceb645aedbe1d1ed478fa5a5b.nq.gz
│   ├── 31547eb7854791489146ceb7dc78a7e4c2313a35.nq.gz
│   ├── 343e263e220738d479fec483ab6ba5750a8b6c0e.nq.gz
│   ├── 35dc087cc8ac4b50d444dc34f02cf845595ca0ee.nq.gz
│   ├── 370cb64ce09653a127f075862ae218ec06ab4bf9.nq.gz
│   ├── 40c3c98fc4ba5bf9ef4b818bbb53b029ba2e867a.nq.gz
│   ├── 4157922aed9c7ca84675d6af299c6d1c5d1af640.nq.gz
│   ├── 42d6f11457961e54ff27acf4eaa0aca0852606be.nq.gz
│   ├── 443e72595a7c0994203da6f004ee8c3a20659ccd.nq.gz
│   ├── 47b80398ab6d12b4e68e3801596f9a4f0c83f1cf.nq.gz
│   ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
│   ├── 4bcbb9871ce1eb8245257c61051f36696ad29ced.nq.gz
│   ├── 4c205df4986dd33b8e4bfe3eac57141ddbf46701.nq.gz
│   ├── 565cf74031d9b8f3285a5e85e15f6f5a8e0adc75.nq.gz
│   ├── 5a1b85209687f21a601fc992a7ec7fcbc415e289.nq.gz
│   ├── 5b7ad6287b21807eb6244bbe470e75d7dcea7fcf.nq.gz
│   ├── 5bf9579912cf0d0ba29af38de97784c86fc90c35.nq.gz
│   ├── 5e9b35cedf60f6ade9eb5b470cc7d3e87582722b.nq.gz
│   ├── 64b5dd2d5b0cd8e52cb3e517ea222fdb5c9ed1d4.nq.gz
│   ├── 6528b04bc4e029cab82d6d53407180fd9c108e17.nq.gz
│   ├── 6a82ab3670ab0ff1cda6c870716b56a8ec09d6b7.nq.gz
│   ├── 6bb28198ecf18ce5cd44287a95f991480f53996d.nq.gz
│   ├── 71d0c0a5a5133ec17ba5d645ecaaa757748cda98.nq.gz
│   ├── 7371503bac14432ef68a6a3818701f9b61976da5.nq.gz
│   ├── 741af4a28383dbaf9d99d2d8c52c91c9ad7c4edc.nq.gz
│   ├── 7be6057c2513f16d1954877a90811ce2830004d1.nq.gz
│   ├── 7d7675220ca9567692af5f3d3ed859ed392c4470.nq.gz
│   ├── 7edf4c05644af149a3d9c02a38332739426d6efd.nq.gz
│   ├── 8f81aff9fcf3879a0e604e9d05d1b912dc342105.nq.gz
│   ├── 91ca79c29385d162cedfeffcacd93c32708397c6.nq.gz
│   ├── 9ccd619a79ee7260647c7c687ab87d6cefff702f.nq.gz
│   ├── a09bd6324603c90faa5e8a97b4edd19878020966.nq.gz
│   ├── a89367bb240a779cb5ba6a455dee4368ac180d7f.nq.gz
│   ├── afa859e1f7f468b15ae1d1e59680124b66c16cb2.nq.gz
│   ├── b1bc8a0ab1459362fd03ed5256b41fb647fbffe4.nq.gz
│   ├── b24d64be324648084cf2e2b433cbc7d231998897.nq.gz
│   ├── b52fb9fcd69faeb5321c7ed987d3dd6a1f00b98f.nq.gz
│   ├── b537dbd485fa966ca861f40b6f053e28818ba73e.nq.gz
│   ├── bdbe71a353c191a39be5ecc451966fb0a6973ff9.nq.gz
│   ├── bdf57e5084994d7631cb494a602eaab0df57881b.nq.gz
│   ├── be324d490440fd6e0e9a87a53f3b7940ad17b2f5.nq.gz
│   ├── c017b5e4a7cac5f36c84d3012de56f16c43dfb55.nq.gz
│   ├── cb0af2d01f4614c5a21816d892ce57f0725b6500.nq.gz
│   ├── cb4435ea4a537bf6456413b0454be115bfcc1529.nq.gz
│   ├── cee8679ea818f8f07a92a0b81fa4403913d603f8.nq.gz
│   ├── d211232d4fa5d4cc332d98fc4a56e028f81a828c.nq.gz
│   ├── d36701f83d0e88148e754bfff06d22dee941a7c6.nq.gz
│   ├── d379a7544224fe89c5f746ded3ca15b035759d74.nq.gz
│   ├── d45f5d13b77a418041bcb4786ca05ef8c2a2e30f.nq.gz
│   ├── d8486af367047bf995fb2394d575b86368ca18b5.nq.gz
│   ├── d99db9f415756789d9aef012a66c4cd903555fca.nq.gz
│   ├── d9e773b56842298917d1f5c005f2fbce3c650218.nq.gz
│   ├── dbfbc22cdd19046a9bb9b8a72457d7b4a22b5cc4.nq.gz
│   ├── e504c5f7b9ddfe2ee90d97b515fbdce3aa47abb2.nq.gz
│   ├── e7f32585e1c535e17aefc7b17f0d81f7047f1722.nq.gz
│   ├── e9589962fb3e3ae263d556e96b2cb39d7a01070f.nq.gz
│   ├── ead6ba388d5286c02f7aa60252d70b406cbcaee0.nq.gz
│   ├── eebe2a56b16fc90c92a501bc82e047fc35bc441a.nq.gz
│   ├── f042c853f7d4c664b9f74b9630991a6abcf93d65.nq.gz
│   ├── f4adde1f4ae198e915df51d5b215580ee3f71f57.nq.gz
│   └── f5f6b94b5ccec514698ac996035409b0f8bd705a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 450bf8305aa4a11e56b380686839b41dfe2efcda.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 84 files
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

[block/qrgo](https://github.com/block/qrgo)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
