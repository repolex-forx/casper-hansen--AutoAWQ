# Repolex Knowledge Graph of casper-hansen/AutoAWQ

RDF knowledge graph data for [casper-hansen/AutoAWQ](https://github.com/casper-hansen/AutoAWQ), parsed by [repolex](https://repolex.ai).

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
rlex download casper-hansen/AutoAWQ
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 88e4c76b20755db275574e6a03c83c84ba3bece5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 88e4c76b20755db275574e6a03c83c84ba3bece5
│           └── chunk-001.nq.gz
├── blob
│   ├── 04dddd9c4db3bb3f3582bb881a4c018eeb9784fe.nq.gz
│   ├── 076d238fa7d8d0f5259522b3207bd5df02c13cb8.nq.gz
│   ├── 083ce26609122a53ae227a5f1203a85fbe68e83c.nq.gz
│   ├── 0e6cb193a079776fe27176b29e499e78eb1fb8a0.nq.gz
│   ├── 0fbfc3a21e939c6cba21e6685b866aecbb6baa69.nq.gz
│   ├── 126074c33d1d0f2829bce13958db97e2f0ec09c3.nq.gz
│   ├── 12edb8fb142360381e9aa6a3c9ed5eab80ee73f2.nq.gz
│   ├── 14bc0de7a04bd2787aabe0fe7b06ab49cd9afbab.nq.gz
│   ├── 178d49a9bde1ef9997f64fb2e2accbff2004bf71.nq.gz
│   ├── 1ad1a4b6003c92c923ed077251e7fc709c1b0823.nq.gz
│   ├── 1dddfeb28b36920d278c4571e099978217926581.nq.gz
│   ├── 25a523ea3be098108f067bf69efa33978b5757b4.nq.gz
│   ├── 2bcf36a18e308baa8258e24706be212623557923.nq.gz
│   ├── 2e699d12f75d01e79bae22a86af0547c338a48f8.nq.gz
│   ├── 31dd50836b28a82947b5c2d403492af977f058bb.nq.gz
│   ├── 3209d0c18ecab7631934cc47985082d26348f1fb.nq.gz
│   ├── 3260379f7365c973fe3e451494f6cf0f1610df46.nq.gz
│   ├── 350b3264f0fabcbb363a26781ed30e609dc5811b.nq.gz
│   ├── 36ea956a1812f98e5bfa92d1448a95457aaa986d.nq.gz
│   ├── 370de9ab48400b9c8509f837b565184536f6fd96.nq.gz
│   ├── 37b7dd93b460c2e0aac235849b9d68f627a8cc9f.nq.gz
│   ├── 3a6d0f7d5fae392a69542bc1fdb44432051187f5.nq.gz
│   ├── 3b8513d410bf4177ea6cfa43196a3af3958939c8.nq.gz
│   ├── 3ebaa1b68f12fa044b1989407eb533f4719e2f93.nq.gz
│   ├── 4980db3d986f42e1879dfa62f29becbb0ab03f87.nq.gz
│   ├── 4ab9b7f7b90c382a35789100a44418a109b18e8c.nq.gz
│   ├── 51f8ca8adac1e65ab24d06efe3b1cf45b3255d16.nq.gz
│   ├── 523e6074c57084713400d1bc46a9989f5f75fa62.nq.gz
│   ├── 53aaf303c80859fc92dc8e16319c567b9b7aaa4f.nq.gz
│   ├── 53e8a4e154f49392ec219111757e52bde224909b.nq.gz
│   ├── 543532f26c70ed69802b0f572b7af765f27f894b.nq.gz
│   ├── 5439f386ce0ce514a2828f1f60b2b5f87ad917cf.nq.gz
│   ├── 56b789a081558f2286b8cb92d1071b5476ba3c02.nq.gz
│   ├── 577e04aedca01e0b7d6c1df64ea22c4cfb9ec34e.nq.gz
│   ├── 57d7824bbf2f75c4889461715ea0c0a133ff04ae.nq.gz
│   ├── 5a611089b187b7a8f6b86d78eb392d61baeb15df.nq.gz
│   ├── 5b1305c9b9cdefa888eaae7769d2927e4521ff80.nq.gz
│   ├── 6739300d23a13f3e37b0a9e21221fb06186094bd.nq.gz
│   ├── 6d0a1ebdfb78043950217209a590a3c495413703.nq.gz
│   ├── 73fb7f1b1063c666b736a428596453b8a53a1103.nq.gz
│   ├── 761b2b4efe6ffe1946a6830167c1c4151b1a7ba6.nq.gz
│   ├── 819d67076b5c9a1109f0e2c1e1bfc376e3332cad.nq.gz
│   ├── 82f24f9b019e92f6cafb2d77003e100d438eb134.nq.gz
│   ├── 849103b3e16e98c9b664c0ec994e7b8dd39fbe44.nq.gz
│   ├── 8da98e1947c8bf465152389fab79c6867c1661bf.nq.gz
│   ├── 8e35e06f5b193cc71be451bd7ddc34bb4a686f7c.nq.gz
│   ├── 8e5d058568d2766eb824e91123aa96da89401b2d.nq.gz
│   ├── 8eb4a823c1f813a00c1f118a843a78fd8a204480.nq.gz
│   ├── 8ffb0c5a78ca1247b93c5f91cd5ece1f4acf0a0c.nq.gz
│   ├── 91bcb2449a8ca2f5cf5d3ccf05b55d05d48a0d61.nq.gz
│   ├── 9236109b79256bb822ca5e0c2b544c0462d0c471.nq.gz
│   ├── 923e97661a913d5b9e356c3f915d44a9ac89b195.nq.gz
│   ├── 987c6014206de47c1cb1364772dd96625ea7d23c.nq.gz
│   ├── 98dddb56baa864ae1dfc2ecaa9e3da80f7dc8a55.nq.gz
│   ├── 992350e2f122e766b3821096c46f8930d9febdf2.nq.gz
│   ├── 9c25c4fe064befc29fea13780609d0ef8826c88a.nq.gz
│   ├── 9d6108ad07501c7e6b084454953de4eb89b90031.nq.gz
│   ├── 9e136bed5ecc2c4ed448c6ca3569a90fcd12a179.nq.gz
│   ├── a1d780105ebe3764599695eac3db3a66c1407175.nq.gz
│   ├── a6af32b571c18f2622d1a37b25f19272d2419e78.nq.gz
│   ├── aa601a633f79fba0211ea35451859ac186dc9e15.nq.gz
│   ├── aba64f324f6d7ac1afdbb3932754992d53df5bca.nq.gz
│   ├── aca327a505563c97f6ce15cbb88098e8e72f3965.nq.gz
│   ├── ae148bc63cb7a564e5e3468f70a5435915a1a6b4.nq.gz
│   ├── b042e1629c9b75df0c334ae31ac88d6ab05f9d71.nq.gz
│   ├── b1c8000d01facdc58a6883e7b8f0a62159fb3987.nq.gz
│   ├── b2191f65f72f186cb65575c7c93780040ae61b3e.nq.gz
│   ├── b3ed65db4686c49990ec0019133282574587e5ca.nq.gz
│   ├── b659b4d07f15451b5b7a565e1bd8a4aa83448e38.nq.gz
│   ├── b741cb753a6185189c88420a0e29d7699bc67aa4.nq.gz
│   ├── b7912675f8cff6ac2318076c9ac13aceebbcae63.nq.gz
│   ├── bc284a2a9a1b1bb9c58ca64334f7d11040e717bb.nq.gz
│   ├── c0efc6c165f2082144009d7de0e3c2db5db385a7.nq.gz
│   ├── c445c085ed4a51a533aca23483567abc61584056.nq.gz
│   ├── cea82dfff91ad926f9ce03507d2b21b65d6094f6.nq.gz
│   ├── cf797c53700e20c9296de6dfac978dda6dace659.nq.gz
│   ├── d15290fbf768c688875ebf9db056e56510cf3943.nq.gz
│   ├── d24efe182642d28e428cbb7ab7f4a0d365d169d2.nq.gz
│   ├── d311137eb7662abf2992d02e3a1a97fbdb0ae1f5.nq.gz
│   ├── d362574d0cfd78ba4ca4c7212f0b9aa9e6c4e4d1.nq.gz
│   ├── d3b5e2662c7c48b4681db9b63870f66f5c9c313a.nq.gz
│   ├── db9ecc3cfe94ad79ee00155fc0a723ab1509cb85.nq.gz
│   ├── e108a781ff33a53f3ff10440aa4c5483ac1595ca.nq.gz
│   ├── e26da2b30a2c83a41ffbdd68bdabf7b0303360fa.nq.gz
│   ├── e6304179de12c2a404b1f0f23363af567fee9433.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8a9324f1388827e5ef99254073287cddac059da.nq.gz
│   ├── e9a44b6fac855fbea6ac4a07f41645cbf66d5a60.nq.gz
│   ├── ee54e1b0776dcc83f9ac6ea36d8103e5f1bb7c44.nq.gz
│   ├── f0397e3141becf53c1e3d718476ef0d7204fc193.nq.gz
│   ├── f2845d34c43ebd9ec157fd3c8d7ad03226ab810d.nq.gz
│   ├── f3c02a1f2e3a9e0a1e93e2d8290605d3a205fd5f.nq.gz
│   ├── f99c925a985551e0cf396bd4a452b8859f5fcc97.nq.gz
│   ├── fbdae92fc5a8550668037db3464967af323640d5.nq.gz
│   └── fe26188b992a880bb7e87d8645685b4932a4176e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 88e4c76b20755db275574e6a03c83c84ba3bece5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 103 files
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

[casper-hansen/AutoAWQ](https://github.com/casper-hansen/AutoAWQ)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
