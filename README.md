# Repolex Knowledge Graph of klen/starter

RDF knowledge graph data for [klen/starter](https://github.com/klen/starter), parsed by [repolex](https://repolex.ai).

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
rlex download klen/starter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 24a65c10d4ac5a9ca8fc1d8b3d54b3fb13603f5f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 24a65c10d4ac5a9ca8fc1d8b3d54b3fb13603f5f
│           └── chunk-001.nq.gz
├── blob
│   ├── 002cb333f1219e27695fd8950018faee93f9b34c.nq.gz
│   ├── 032a5d4dcdc2643db7a0f1006c0ebe51f445a8f4.nq.gz
│   ├── 0b2ecd3ba2c88f840000e0e65793bc90296955b3.nq.gz
│   ├── 0c9f8251b4b9a104bcafe42774ba64e4efd54c77.nq.gz
│   ├── 16763a32445937e09a0817c2a065dd669dc5e492.nq.gz
│   ├── 220205de3273873bb0f2fc246a9cd376c0decb83.nq.gz
│   ├── 27a0f389284022a1f4136a2aa48a75e02d161b39.nq.gz
│   ├── 29fcb721dffb1d114a537752f265197a58611bea.nq.gz
│   ├── 2a88a2413c96898a122ee20fd73bd5d5d51cf80f.nq.gz
│   ├── 2c5a293cd8d0839e561cc81d8338c2de34503e8b.nq.gz
│   ├── 2fd808ede160633993349fbd079825bbfc4621d1.nq.gz
│   ├── 32edc9e2f8ed9e88a64c09df99cf51152a27aa8e.nq.gz
│   ├── 395527df662d5fdf4b00c5f1cd9b8d7ac048e127.nq.gz
│   ├── 3a012b56ed38d7151f601673f93c99b60b2bf2f1.nq.gz
│   ├── 3f07aa761e9d723baa1f74ee52491fa484a58992.nq.gz
│   ├── 41433da4792f140902c07accaf3101fa5a9ec299.nq.gz
│   ├── 442a144952e76f91cecc6f3d9f94af32d9c2ca89.nq.gz
│   ├── 491fdc19e59919a870d2276c704ccbe053830200.nq.gz
│   ├── 5306e60ae9ebf0134e73975b5be6bd49df1f962b.nq.gz
│   ├── 53ef5404eb4b7dd71ee77bd0aea840b4ca6ba80b.nq.gz
│   ├── 559c11db4b42093c882840c2d559d184de15cca3.nq.gz
│   ├── 58c9bdf9d017fcd178dc8c073cbfcbb7ff240d6c.nq.gz
│   ├── 5bf7a86c91730b569f5df4936b6cef7641630c3a.nq.gz
│   ├── 5e4090017a9bec5de60a745d17007a9e95f31a43.nq.gz
│   ├── 69986f39e3d4bcb5f37b582119cd3311872a929b.nq.gz
│   ├── 7690695df2a99ecfb0b78136213e7821a9155ab6.nq.gz
│   ├── 793e6df1fbab4e1601f939834cfd498f7548181b.nq.gz
│   ├── 7a5857f9546fc558cddf7b2f41693f2bb4c2149a.nq.gz
│   ├── 7ce1c94e707f14af7bcd92d651a9ab795663bf31.nq.gz
│   ├── 80ef40d5e2e0acc2053ecbaaf71bd4d9405a60f3.nq.gz
│   ├── 830bb2c35efeeb2623600c4949b6c736608c525b.nq.gz
│   ├── 8951ea8e619d97d651aa55e8dee549b29b31a746.nq.gz
│   ├── 9b16b0c8279906a4081f37ba539eb6aa42e23404.nq.gz
│   ├── a07ed187ae2f24dd711f3798c85e8e7abc678caa.nq.gz
│   ├── a14bdeee80a81e4f0f0b179bf0293aa14b74ac3a.nq.gz
│   ├── a449239544826f8180a1933b13cede671e9df491.nq.gz
│   ├── ac92ba834aac101329105e734112c45e7c77384b.nq.gz
│   ├── b0bdfdcf09fe10dcb8ad754a97bcacbe3b09300c.nq.gz
│   ├── b2f54fdf87137fe1451f7b09649184db0477839d.nq.gz
│   ├── b75f2f1728eafd761a94615543a7c462782127a9.nq.gz
│   ├── b790351fdb8c81a1df8d58743ef563d69ae82281.nq.gz
│   ├── bdb93b8b5ea5936e24492aca961ecdd6c52ed235.nq.gz
│   ├── bff77972f8ac5b6df260a9302151f7e25f0eca7e.nq.gz
│   ├── c33644feee0929af254fdc0f6c7bc02fe0401a65.nq.gz
│   ├── c5b19d86ddfa7aa03633bf145f56cbf90a094134.nq.gz
│   ├── ce9b6058111454e749c4cd28a7b493c28bd296d9.nq.gz
│   ├── d3f731b2cbf5f76e202dc6f17b1621e12564bc85.nq.gz
│   ├── d8c2f4def4e8fcad1c9ef2581b604fe59a5b4e98.nq.gz
│   ├── de2538729b574e89bf5a6c59eed3ba47fac6b0f8.nq.gz
│   ├── e370f19a451180fed9bbeaea5935a67e046c924b.nq.gz
│   ├── e408ff64b4d62135814a9948aca98639da8d5ea7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6c7d69a9e8746a37766293ed8a26bc99775b635.nq.gz
│   ├── e7ca4fecc5086fed4f916975f3966c172e44680b.nq.gz
│   ├── e90bd6d7d7b764e55e94e295b0c844b58f112dfd.nq.gz
│   ├── eb255d6882fd321d24848ca7aa82ebabf84fd431.nq.gz
│   ├── f176e98bc8cfc315ee6e3cdfce1dd1bb1aa2b241.nq.gz
│   ├── f4c42c1d9209bc22d7eacb21726c5f8a4b439e3a.nq.gz
│   ├── f6523cee72179324e3fe70511c24d1f64f761ee8.nq.gz
│   └── fb4e99dfced90b3ad4da6498bd1ac3f441bb99da.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 24a65c10d4ac5a9ca8fc1d8b3d54b3fb13603f5f.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 67 files
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

[klen/starter](https://github.com/klen/starter)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
