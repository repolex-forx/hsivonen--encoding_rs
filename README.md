# Repolex Knowledge Graph of hsivonen/encoding_rs

RDF knowledge graph data for [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs), parsed by [repolex](https://repolex.ai).

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
rlex download hsivonen/encoding_rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 08604915e6f1a3b7a93398aec0bb92d7a6611a6a
│   │   │   └── chunk-001.nq.gz
│   │   └── 662cb427013c13eb4444e7e51e8579c9457f5e6b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 662cb427013c13eb4444e7e51e8579c9457f5e6b.nq.gz
│   └── repolex
│       └── 662cb427013c13eb4444e7e51e8579c9457f5e6b
│           └── chunk-001.nq.gz
├── blob
│   ├── 038b7a133d596cdf61e1ee62ec8b1ffe9daa905e.nq.gz
│   ├── 09fd4ff2aa36f85e439025969c203da34fc4da84.nq.gz
│   ├── 0a7df99a4f65d37105144e9bc5383f2b91f97b58.nq.gz
│   ├── 0ba4e1606af7e7e5c05756bee1c0162d40b0db2a.nq.gz
│   ├── 0f429e7b103f51f869d41f545a5d16f3e535f31a.nq.gz
│   ├── 116e8593f0914537546c673ef013bc3d9db708c8.nq.gz
│   ├── 117bbd49811031252b46a1ff161be7e8c201efc9.nq.gz
│   ├── 19570a3b7a4042c67b2f7a19d3de80bbdf0fdcaa.nq.gz
│   ├── 1ae5bbb12cbf72da712747771a52a843adfccb97.nq.gz
│   ├── 20cd54967363fd803084def40788bc0db7ed8145.nq.gz
│   ├── 2353225de3a447011693a713777932a8e7a53f89.nq.gz
│   ├── 2398df06d40ae701cddf9932586048b7ccdd8013.nq.gz
│   ├── 244d39e5d38c0254b29625d820b9f1e4d6c55fa7.nq.gz
│   ├── 24d6215d971f7ec28dbea77a65dc0a617767f5be.nq.gz
│   ├── 24f0df3d19949235eb6384e43a64ad18f7ecf9a9.nq.gz
│   ├── 26491a93a40115179c8cf243f183e0bb4e58b495.nq.gz
│   ├── 2703ad763befd323487d5ac2a9744d3abbd7fba3.nq.gz
│   ├── 288e65a686e701decba16caecde9daf954229cc5.nq.gz
│   ├── 298df0916ad8ef29b272db14500a4d1158d51019.nq.gz
│   ├── 2fb7d00e9c8872f75df030e05d8e10892a0a37cb.nq.gz
│   ├── 30e684546d2dba29a89673f2350f09227f527873.nq.gz
│   ├── 30f080b7630694b185e3a2014de79000adfc731e.nq.gz
│   ├── 3163f56ac9d93c3bb50bd46b117da8fefffb4916.nq.gz
│   ├── 32e970923be1dd1fc51f86ed58e5eab54eb97eb2.nq.gz
│   ├── 3317c82e2f677cf6d16b1ac57672bfdab2b15066.nq.gz
│   ├── 33c12d21bdfe79290df584907068f8a4eadbbbe5.nq.gz
│   ├── 38bf2ef4e64b146f1c99ecb232722895fee1cd8a.nq.gz
│   ├── 3a98e8b986fe87a8ba5f34ec23665460d4061f36.nq.gz
│   ├── 3b023126a30515d73ce12913f6d48370b21ba810.nq.gz
│   ├── 3b9d7c36655cafb84249dfb97bbb3fed00611f6f.nq.gz
│   ├── 3d161b5612bc3372fef60cfbf3ef92b6fe9764a5.nq.gz
│   ├── 3d1bcc1f57cc765217946e0cf2cbecbbc44d7c68.nq.gz
│   ├── 3e4833bf19619e1f6823b447cd3842a0062c4a8e.nq.gz
│   ├── 403a07c11197292e1edde5c30aca754134a9b0fb.nq.gz
│   ├── 40449c4398ecdc1b6de0d5d3005c24e06b3b3801.nq.gz
│   ├── 41774ec5423292bf21bd5c6c32f6c4a9b973ad35.nq.gz
│   ├── 41f63926ec967c138670401dd5522cbbe3044397.nq.gz
│   ├── 44fac4c60954cc0c6e8fd984660e1dfb5cf93d9b.nq.gz
│   ├── 46dcfe7659b3e0d76c1a5e5708c328f9cc7f6947.nq.gz
│   ├── 4c70c22583bd2c6604c77462a68e96e2f62f7e6b.nq.gz
│   ├── 51cc6900825c14e9242921e30d8a3f554f7a2b0b.nq.gz
│   ├── 540cbc88dd6cda6e6d0bf429182182d8a5046ca1.nq.gz
│   ├── 58d3e52bebba4423354dbcb3033b56da0a40145f.nq.gz
│   ├── 61e8fd58011d815ed629e8947a98b52f293e7463.nq.gz
│   ├── 65713a1e9ff5758fff857e2bf94802352be67dad.nq.gz
│   ├── 68264ca1ba63b170b73f413eebc2406559f42bb5.nq.gz
│   ├── 73f9b6ff711dd5bd634c582f42506fd66eab93dc.nq.gz
│   ├── 79111e2f7d91125f87be84e41fe968322d059b24.nq.gz
│   ├── 820e7cd94ccd206922de1d65382f595a36c013af.nq.gz
│   ├── 83d3ece1409969472684a03fe7de2b6cc343ffda.nq.gz
│   ├── 86ec39ce600551a562f3b13570fc5d0d1a0b27c5.nq.gz
│   ├── 871ff42139ffe82b3d34c7fb4faf80dab8109399.nq.gz
│   ├── 87727fc8c4eee7665ffa86c6b1d0a67c1c456acb.nq.gz
│   ├── 897dcc500e01a554799315b99a8da8b077056739.nq.gz
│   ├── 8aca388e7c639ce342ed447e463e3d29860f8a6d.nq.gz
│   ├── 8bf217fecd8d107c5b3281daf94e611730109800.nq.gz
│   ├── 8d45d59665ab63f83904ebfc19e30d2397606d7a.nq.gz
│   ├── 8ee54fc1e6b834910b312c7c9a226fe78f93b822.nq.gz
│   ├── 922896a8829ae1a445191e7f82fbb47dbfc35ca7.nq.gz
│   ├── 925547e6567127d59067fb515174cb66727c3b4b.nq.gz
│   ├── 931156f4fe34343da96915e33d25a5b5fe81a0e8.nq.gz
│   ├── 9645611e2309b1457a9c89daed03bd927ecbda10.nq.gz
│   ├── 96e38ef4a09633c8086ec51a7afc2b5c672d12e1.nq.gz
│   ├── 9e9c3f6c130f84700385be703933ad0c7194196f.nq.gz
│   ├── a11cb3239724035eb15bb9b84838f19faa7a1144.nq.gz
│   ├── a263745ef14a4be5b433e52c046df89203290fda.nq.gz
│   ├── aa5c5e6d38917fd2c7e301027bb33de48af5520e.nq.gz
│   ├── ac3b3d9e836bb6acd9ca16b0e0ec727600e1e151.nq.gz
│   ├── ad0225ffac0a873f8419795efc9aec2ed38c1243.nq.gz
│   ├── af005915da911c596d89065ccea3afb9d46624c9.nq.gz
│   ├── afbbf0901924c6eb2925e32908cfb367e3e9c204.nq.gz
│   ├── b10d669a539cc6cf4b0158e8761ae5f73a41cce0.nq.gz
│   ├── b5519a122c00f9c496eb819619e634d465814fe5.nq.gz
│   ├── b73e572e1540c55da630fb2ffc9bd04acbb89a89.nq.gz
│   ├── b78ed38e41520cac661de77700d144eb0ad59269.nq.gz
│   ├── b982ab5b3e0907e0e1b6dc0f71364a208b79e95d.nq.gz
│   ├── c2a0d3ebb07f1fb07639d9b6c1d4fba40493a120.nq.gz
│   ├── c39b0503b834ddc2682d911b4108a90e35717a23.nq.gz
│   ├── c462ce8f7f7dd80a5d71970d5c065ad88f684ee5.nq.gz
│   ├── c5600e38fe3ab012e961a928c70d3db4da02208e.nq.gz
│   ├── c7dc69ea6ffef331c4ba8babfa180282c8c79a95.nq.gz
│   ├── c8b37b8512813bf579c50944eb598c216535f298.nq.gz
│   ├── cbcf86dc1cb669807f92aea5b0a6e18c52c1ca9d.nq.gz
│   ├── cdc2ab8664b776005e0fe825d0681eb13cbae96a.nq.gz
│   ├── d00fece7c8705a376e8b14145420c0ddfda04b75.nq.gz
│   ├── d1ae50bf08bf69b824bafb491606b5c7bb549182.nq.gz
│   ├── d5e1f9bc300d0bed8e3c7f6e525b3eab15fe34c8.nq.gz
│   ├── d613fbe25ca3d8126eb33ceabede1e7e76b420cf.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d711b216921e59a381935efc763c700e34abf445.nq.gz
│   ├── d7fa6a21f68e5b7c237acc18a28321ea24b52a04.nq.gz
│   ├── d8c2c502386024ee96aa9d3d7e6551041411d535.nq.gz
│   ├── ddbc71143f06c4eed0dcfd201822042f04676efc.nq.gz
│   ├── e00ddc662ee0ef4e6887ffcbe03196c0a007eb89.nq.gz
│   ├── e026726c46546b5723a81eeb6bfb389c1d60e2f9.nq.gz
│   ├── e05207ed6626503350ab8a7cb6e458f19d689653.nq.gz
│   ├── e2ca55c90dad6aaf798fc7aa6f104afc5d81ca0f.nq.gz
│   ├── e38698b11b828ab7b3aaca9aa037cf08042a9742.nq.gz
│   ├── e57516dca8300660041843bff5431c15729a0826.nq.gz
│   ├── e6278c97fac93bd006d398e5c0e532311d7e042e.nq.gz
│   ├── e6fccdda14fe38f71c92010348e35ab6c42be6a5.nq.gz
│   ├── e7ac1014edb6ea4045c0b7aeea51ea8792d2624a.nq.gz
│   ├── e9dd6346b3530d4223b857c1f55774d3003e340d.nq.gz
│   ├── edcacd9037122e952cfb6f9add5da3635d07e979.nq.gz
│   ├── ee853f21bb36f39cfc44157961a3820d05f1394b.nq.gz
│   ├── ef24c980e06fe576dd9a371cc507b6f0ef8622af.nq.gz
│   ├── ef45c03ea153b4eb685f8516eab10434282e90e3.nq.gz
│   ├── f544635acfaf7e3f0bd2a697b12a79693b401173.nq.gz
│   ├── f6209b282aa8647461562159b63f57fe4afda518.nq.gz
│   ├── f690e71965909bac7e62b84603ade9fa7a9cca54.nq.gz
│   ├── fc3fad21d4f36d6b3d39145ff9cad02f4724803c.nq.gz
│   ├── fc45e26ad7f93dfa97222d77248b561134d20307.nq.gz
│   ├── fc6753b65898f053a95bec551dac25fcd5022464.nq.gz
│   ├── fd13adcabdfedb46a19259aac78de7c4c0a72851.nq.gz
│   └── fe48481dfe95d22cb135bf5d282b30ec14e4a1a6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 662cb427013c13eb4444e7e51e8579c9457f5e6b.nq.gz
├── filetree
│   ├── 08604915e6f1a3b7a93398aec0bb92d7a6611a6a.nq.gz
│   └── 662cb427013c13eb4444e7e51e8579c9457f5e6b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

16 directories, 127 files
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

[hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
