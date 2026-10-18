# Repolex Knowledge Graph of schematics/schematics

RDF knowledge graph data for [schematics/schematics](https://github.com/schematics/schematics), parsed by [repolex](https://repolex.ai).

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
rlex download schematics/schematics
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3a144be0aa50f68a4da917e8d957b924dedf9a52
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3a144be0aa50f68a4da917e8d957b924dedf9a52
│           └── chunk-001.nq.gz
├── blob
│   ├── 009c93964c5650025c4e470e26947082dd832642.nq.gz
│   ├── 05c85edb0d2808cf1896f3da273c10fa05fe61e0.nq.gz
│   ├── 0d09aee1e9c492dc5c94269ad13b95cc4c4122c8.nq.gz
│   ├── 13295ab644feadd2e6473432f2e4469a21a0f530.nq.gz
│   ├── 1664cdef783aa8f8148d2d053e464fa319694d65.nq.gz
│   ├── 1a7f872736e2f0855dd4cfca803729112e1be3b4.nq.gz
│   ├── 1c2c06c8e9b949cd818199b785b50e7f223a9402.nq.gz
│   ├── 204274f4ab6f115f3d83b06239fced72c7f2ef5d.nq.gz
│   ├── 22e6aadea57aebdc25f30bb64b88df5b2e0287a6.nq.gz
│   ├── 244cc066c7a9ddf088180482fb44bb8d75f0cbee.nq.gz
│   ├── 276f03efe74c017d457fae414891bf9ee349d343.nq.gz
│   ├── 2b50509431cd9b52d7cdf7675db0d7358c4eb5c5.nq.gz
│   ├── 2f4cb597bb0ec2b28b973292be7f6f2b41f9b363.nq.gz
│   ├── 3020245dcbbebbb4cf725607e2082da3c96909e3.nq.gz
│   ├── 305c948d715c4efeb726928441f4480835fc2370.nq.gz
│   ├── 331c338e314ed862df4a0ed8880fb9ece3dc4278.nq.gz
│   ├── 34dbb0c3d88cf7957b407ea05017e8209fd18532.nq.gz
│   ├── 380c03ee6d08087795e34c5a1ecde6cec1898b8d.nq.gz
│   ├── 3b74f4aa7bb9fe89fb70c980101774a0991d1599.nq.gz
│   ├── 3d4db342c900a07db2bd7502f9d26b31f196b24d.nq.gz
│   ├── 3f1dfd54759cb0eeec034ca738722e93c340fdce.nq.gz
│   ├── 40270c772a781e7c3883701ad58069fa166f0357.nq.gz
│   ├── 435af62672d69c64c3ad3dcf3991f8aa21165ef3.nq.gz
│   ├── 44feed690aacceeafc28673f30bd6ddf6722e650.nq.gz
│   ├── 49646693c97916b3797b61be64045522528c966b.nq.gz
│   ├── 4e39c7590e488cefecaf95a5062f0b5657cbaa1b.nq.gz
│   ├── 4f877669a596b7997e3bcae7f2c0768d21cdb4c1.nq.gz
│   ├── 5413da9bcd3c0de7aa7c3cb0fcb831980a242039.nq.gz
│   ├── 54defadc786481a2c90a1f44c0b0203ab0c99acb.nq.gz
│   ├── 562d12643a2f2847b4dcc7bfe2c6e7ef78a6de63.nq.gz
│   ├── 5cc91ade51de8175abe1e9133b7400bd56887b2c.nq.gz
│   ├── 5e5e859f65ad94f85211ff9e3b69adcc6f830fce.nq.gz
│   ├── 609ffe2fee81f93ed8af9a046967dee9f9c5062c.nq.gz
│   ├── 60ebf73c460f434e85d43656010e38b6694504be.nq.gz
│   ├── 63c3014a41fdb45458b54f3d824e06be5217b782.nq.gz
│   ├── 64f140d6cfc5edf046449f3d7baf73f95698cf5b.nq.gz
│   ├── 64f9ec572cfc5bbe0ad00a64599a18087862a5bf.nq.gz
│   ├── 650b349711c395a2c90e125bc25d0c2fbdd99f35.nq.gz
│   ├── 6abfab586e1362a89dde2b9ad73f300f0048f166.nq.gz
│   ├── 6bfe95dedc2145a76f1aefe2948def7d6742132b.nq.gz
│   ├── 6c5d81ee31bf39292c88947fb0499bb103ff5768.nq.gz
│   ├── 6cc58fa9ebbf844c7497f2ddff59f77b844e427a.nq.gz
│   ├── 7092e86f8aa629b03bf74e77b239055416fc4086.nq.gz
│   ├── 7156de33a4901501bae5030cbd9147dd6c201915.nq.gz
│   ├── 71c3ba0c090ff45cf762277c692b788ed3aaa4b7.nq.gz
│   ├── 788664e5b92e3ee01156e512ba4a9fb7268455b9.nq.gz
│   ├── 7d7c1be74b2a61d7ab19c5f9181ca64c0c71e03a.nq.gz
│   ├── 7f9e9e1be4dcdd29a6c68b20a6c2bb72d6231bed.nq.gz
│   ├── 8047da2c26967b87ea0cf92fd2b1db804f3663a0.nq.gz
│   ├── 8194383ec6384b23f7eb920dc30bcba83d33f11d.nq.gz
│   ├── 8565ce4d8308fc722df90c0cee222f58abfad671.nq.gz
│   ├── 860766f5b7e396034ed70275ab698c4665993ebb.nq.gz
│   ├── 89051de1d289769d66baf7f660059451055f5976.nq.gz
│   ├── 8a3d3a1ec7b4514a4f1bf3a3f32a6973dc0368d3.nq.gz
│   ├── 8a5d88f36adad6c77abd6128522e249f8275b438.nq.gz
│   ├── 8ba59cebde87416b16be99c6fc37a1243ae0fde1.nq.gz
│   ├── 8c2ed0657cfd8f83ea821640a4868d8ff2556135.nq.gz
│   ├── 8c38f3f3dad51e4585f3984282c2a4bec5349c1e.nq.gz
│   ├── 8c932a29bc0e5067eaa41d4541a6b0318ba94986.nq.gz
│   ├── 8cf4bb0a8b5a420a86ac3e2a39ce1d4e5c5b98e3.nq.gz
│   ├── 8d0fbbe9c4daf872ffd4ed96a13b579cefb3516d.nq.gz
│   ├── 8db433dc3e9316178f35435be91f24e72ba3929c.nq.gz
│   ├── 90b31b54ac7f495477c60d87086b10f875c9e2dd.nq.gz
│   ├── 948c7044060859b67e2ca740f53f536ba494c9f0.nq.gz
│   ├── 9f2a633c595382a733c736be014994a12ed93780.nq.gz
│   ├── a16f83b8fd62c1ca3a90d31f7a55bfc8832005af.nq.gz
│   ├── a42aeff13d40c7a7519d6eb6b9c710e7243696a6.nq.gz
│   ├── a60280ea95fc50c93404a78a1a36d3d45c8723f7.nq.gz
│   ├── a94234562cbcc1819e476455c97e51c9bccdcf4a.nq.gz
│   ├── abfbfbafaa930e92c63fcb1cbda673af5991989e.nq.gz
│   ├── ac12157f027b005aad91ae9f8d637f49dcc31e91.nq.gz
│   ├── ad8e6e574c502b4d5547f1252fabd9b5c3cc1b72.nq.gz
│   ├── b01722fcf5a6c3db68fca35b055a5545d8f48609.nq.gz
│   ├── b3c0c86ddeef5f77d898155d9aac343721d648ce.nq.gz
│   ├── b821abe12967166a2d3056d232c8399dc0933806.nq.gz
│   ├── b8b0c092d7628819743c8a5176f183f24787d4e1.nq.gz
│   ├── b8e518a25d7e4643deaa7afabaa06c8397b50257.nq.gz
│   ├── baf13eb303a02b9872d1d110578c71557fc3c5f4.nq.gz
│   ├── bb6ac6bb6ee5c2d9b00c38c90bf7b75884aad3e9.nq.gz
│   ├── c25d21305f76ca1bea55c2bdbc221a55b2f0d824.nq.gz
│   ├── c30e928e14dc3bba676486489e31a8ce871030f5.nq.gz
│   ├── c3ba0114b2f757c986dffb1be9adc1917ceb99d4.nq.gz
│   ├── c490339ab43b508cf5c96ca59bc5770c92cbc89f.nq.gz
│   ├── c6026c8416f32a9721fa2891e0adbb1d10ffc06f.nq.gz
│   ├── cb436a881e36891121c21426b338a6476fc824ba.nq.gz
│   ├── cd77449079e450f1adb3d17ae61a321bffd54850.nq.gz
│   ├── cfc1f5a455be105b9d72bdd1224f8ab445c9055f.nq.gz
│   ├── cfd6f57613b20b43c7c810d08371b060021729be.nq.gz
│   ├── d22eeb3e1d93fe57734a345f7f7a981537583667.nq.gz
│   ├── d4fd528f9ec0250b1a1515ab19aa77c8ef6e09ea.nq.gz
│   ├── d5d819141e0b841202cf12e50e484956844316e4.nq.gz
│   ├── d6ee84415732df19cf1859b99ffade10aa510ced.nq.gz
│   ├── d8a57a31d26b987b20936c3cf40a63efdac90196.nq.gz
│   ├── d9d557fb3b50972819a560d46447ab4090f0ea10.nq.gz
│   ├── dde17bc838e940d8d58a51b2df508dcefe5c89ab.nq.gz
│   ├── df5a9d9e2898dc805c6b04152aa488abaaaea51e.nq.gz
│   ├── dfb34069b8bf02198ca474394c97d7e2a82124c4.nq.gz
│   ├── dfc93f42c53a1f5077e0fa518482e0a46419c387.nq.gz
│   ├── e29874c04c47f25db8c6f7388979964e506a422c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73cea5017481e768eeef3415f4bbc5d0dc6928f.nq.gz
│   ├── ee38c119bc7ecd13b6e34f8fe1150fdd9ae23d97.nq.gz
│   ├── f2df9113acbf1aa446c75ca012dc47539526f556.nq.gz
│   ├── f82ab03b9eec424e5cfd551c5db498fc94c6c980.nq.gz
│   ├── fb2f20cca0d25705b28f367afbffb90e2cf8dd0f.nq.gz
│   └── fc0e21fbd7530bc25f8e0f80a617a106bc3225d0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3a144be0aa50f68a4da917e8d957b924dedf9a52.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 114 files
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

[schematics/schematics](https://github.com/schematics/schematics)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
