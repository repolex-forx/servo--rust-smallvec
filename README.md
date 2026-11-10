# Repolex Knowledge Graph of servo/rust-smallvec

RDF knowledge graph data for [servo/rust-smallvec](https://github.com/servo/rust-smallvec), parsed by [repolex](https://repolex.ai).

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
rlex download servo/rust-smallvec
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2328868060b1e43394c994475f86b53bb55cc954
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2328868060b1e43394c994475f86b53bb55cc954
│           └── chunk-001.nq.gz
├── blob
│   ├── 06d52032bf92d6377d3c72686efaa8583ee9e87e.nq.gz
│   ├── 0a8a80491500d40c9f5a4c70f4c976d4758aeab2.nq.gz
│   ├── 0ce6622a09e636a1e73d644e5b4f8b857c12332c.nq.gz
│   ├── 0dd814ca91655ff7b70c55a048525c0b8def10b3.nq.gz
│   ├── 0e2dd15ec17a67a71e4785a27924df26e43f91da.nq.gz
│   ├── 1615945f0cf995b5ab7131746639088f805027ef.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 17129d3496a7309147f48a114e15939bbde626ff.nq.gz
│   ├── 18ca667ea8cdcbc7112c2aa93e4bd1cf23d93ef5.nq.gz
│   ├── 1a45eee7760d240bfa8ac1989088e0349169f264.nq.gz
│   ├── 28f16f943d0fb1592ba24ede754beb7370e506ff.nq.gz
│   ├── 2b586e2a6c039fbb15dfe5bab8b81df75da65843.nq.gz
│   ├── 2ba895b0f73e41a2c830c0d49900919f6119a0c1.nq.gz
│   ├── 3c4e54416cc2ed8490308b79ccb74a8e9b69c3af.nq.gz
│   ├── 3f8d9cbc7b4a5464ac960ba17e08c2984207e87d.nq.gz
│   ├── 3facf68c5af6cc0212a91923a00f7b897b57ff25.nq.gz
│   ├── 43d919b3a5d3d9bb7b450a6c3ac29d4593a23e9c.nq.gz
│   ├── 4855d0a284d644a78dc947a31659a5546cd01b21.nq.gz
│   ├── 528156567bc9ac1b8934a042ba8a39af7d63b473.nq.gz
│   ├── 54983026b429b8927717d514782613014df6050e.nq.gz
│   ├── 5784ef85f31fd018bac4981cd6bfc0cd094beacc.nq.gz
│   ├── 58ace77659fe6d7af9b5212110e3a71ab056dba1.nq.gz
│   ├── 5ab0453e8544bb26ff6a241858810b45778d1398.nq.gz
│   ├── 5b5fa14ee507478d9bda63389cac01bc8e269781.nq.gz
│   ├── 5f5008371c1e9d7e9ff9de5daf5171e0f0306df2.nq.gz
│   ├── 604698e8ec8960e88b090e910cd232e8742b5d7b.nq.gz
│   ├── 60c558769333dc5bf4792192749ed670f630d8fc.nq.gz
│   ├── 63346d6faf3ce88a8c2fff0fa86db53a7a528c43.nq.gz
│   ├── 67c29462ffe3c8797edc39aa8ed6618d8d43eefb.nq.gz
│   ├── 6d1ec0e192f82881053c7dcf9d8358e2bc817987.nq.gz
│   ├── 6d94c24a02c56210f279a8026adc49490c0e0c30.nq.gz
│   ├── 7094f84237b049083e682b15a52c88faa3aee4b7.nq.gz
│   ├── 72c6e8071fccd29fcf49608d2dc0a975b1aec6c1.nq.gz
│   ├── 789535146e949b58f686396effb6f5da1cd66be3.nq.gz
│   ├── 7973a51e2dd34f6f28eff8ae190dbec10dbaac31.nq.gz
│   ├── 7cbbbd46a93013f49f5af35eb386829f7f6e3e01.nq.gz
│   ├── 7cf2330bcb64ec193f1cf596ed20b4932e2c74de.nq.gz
│   ├── 7db704e099ab998e64a52dea0995defb50cc644d.nq.gz
│   ├── 82a6a71244042ece37fcbc83166356130d6fa445.nq.gz
│   ├── 88bde239ed07032ead3e5db22dd9105814c417ac.nq.gz
│   ├── 890c2694433ccf17a583b5c87654b843bc216949.nq.gz
│   ├── 90ee4a8a796ef2cbd2ae963dc00808511bc651c2.nq.gz
│   ├── 91b8f6157ffbe11e1595ea05f4eefed9207bb29e.nq.gz
│   ├── 92ca4436f9c3aaeaddcd27e1c0395ad3151f07d9.nq.gz
│   ├── 9553e0c22d96d5272e6ed748e44ad9bcc27c1b4d.nq.gz
│   ├── 9729c1284e1bff82ca875abbf0fb4ec540804cd6.nq.gz
│   ├── 9d77847405235d3b19caf98d0c18c8c40ae6d024.nq.gz
│   ├── a5899f8a0c7c5f3e253162b929835109c2a2ea93.nq.gz
│   ├── a5e57c3e3ce68bb9ad3a3b05a83f81efd7b003de.nq.gz
│   ├── abe5a505f94fea3d72d1255eaef7b1f2a39c8d5d.nq.gz
│   ├── aca1bb1b96c59ee316cbbc1a723d6a65562c51bf.nq.gz
│   ├── af6f3859d1021442a9a4ec555785476a15c05056.nq.gz
│   ├── b93bda7e8d5dde47f0f234966d71e49910bfb1dd.nq.gz
│   ├── c19b663230e552b1389190d64203b2859339a877.nq.gz
│   ├── c5a025c25df030e83714c18b10aa7d6b498353be.nq.gz
│   ├── d3d643f29dfc977c8dc334fe9f3cb8c9a22a8ea8.nq.gz
│   ├── dafcb773909857903dd8b3772fc0551265e48f2e.nq.gz
│   ├── dd50fb9493b1d28de09acba6a49fd02eb6e8e1a4.nq.gz
│   ├── dfdbea99acca9eaff03133f7a0bb7449ed8e939d.nq.gz
│   ├── e11f0792f5cacd8753cbd9c9be600ce085854571.nq.gz
│   ├── e8ae442d0f501d6292f70c44b02814af7f3eed0c.nq.gz
│   ├── eb5a316cbd195d26e3f768c7dd8e1b47299e17f8.nq.gz
│   ├── ef389510a6ea6552a80400a5eba86ecb512e7844.nq.gz
│   ├── f28c76c7915ba060ee5ba577795def6a0299c9e7.nq.gz
│   ├── f367b7e9c7f8fca2b3ddd799b59086bc0e5a45e9.nq.gz
│   ├── f4648ab7b7abf2fd75d24561487c5644916f44f0.nq.gz
│   ├── f8e674774abad42add6856ac0dc4d9834882baac.nq.gz
│   ├── fc39666a318dfd47b291dc10ec70c57b9200d87f.nq.gz
│   └── fcd7dd6de58ec99628b503bd244519d05a389e12.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2328868060b1e43394c994475f86b53bb55cc954.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 77 files
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

[servo/rust-smallvec](https://github.com/servo/rust-smallvec)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
