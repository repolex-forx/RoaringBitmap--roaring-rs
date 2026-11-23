# Repolex Knowledge Graph of RoaringBitmap/roaring-rs

RDF knowledge graph data for [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs), parsed by [repolex](https://repolex.ai).

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
rlex download RoaringBitmap/roaring-rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0ce3fc8b55b193ce220253bfbc0c3e09bd171375
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0ce3fc8b55b193ce220253bfbc0c3e09bd171375.nq.gz
│   └── repolex
│       └── 0ce3fc8b55b193ce220253bfbc0c3e09bd171375
│           └── chunk-001.nq.gz
├── blob
│   ├── 0680bf252b72b6adbdb9ed2e0cb7aca0d5ea7ed1.nq.gz
│   ├── 0685544fc1883cc361aee5a793741f4d9b3e7c6b.nq.gz
│   ├── 08fa4627b65911a21d94fe294ad82635166f5d30.nq.gz
│   ├── 0ecade04bf7cee21ea9ff4dee30d3bab92e6f4f2.nq.gz
│   ├── 132733acf6fa992fb49993f44c6ac72b5769f420.nq.gz
│   ├── 14dc5d142de2d96bea2815bffe1fc069843e1f12.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 186464d0bddcdc45b838ec5ed4c8d15b6b966c6a.nq.gz
│   ├── 1a45eee7760d240bfa8ac1989088e0349169f264.nq.gz
│   ├── 1d19ac8709814176cc76d3460c56f885713e13b4.nq.gz
│   ├── 23f6a6c348f3ca2bf92bb8627bf6d08d95bda6c7.nq.gz
│   ├── 2869c42fd3a41c222dba45bcf235eec73c60e5cc.nq.gz
│   ├── 2a15ed63c0e0b0ee28b2700046e86110390bcbd6.nq.gz
│   ├── 2a35f0230c690eacba4dab137a959376ebf02ece.nq.gz
│   ├── 2ab50f8bab18580e86c48594d563f2a5e450ed4a.nq.gz
│   ├── 2dba2bf5e67eb80351410aaf5ed83407e4747d54.nq.gz
│   ├── 2f3296b1ca09e105dd6363c400ea189468fdf72f.nq.gz
│   ├── 3334f86519e6a004ed085b3da2a2b9868971eba0.nq.gz
│   ├── 34e250ef56346e09940ca121799b44f3a3ae9262.nq.gz
│   ├── 370bfb0848eb39fb0469dafbb309f89ca7098831.nq.gz
│   ├── 39375ee73b6ad80e9a40f2a33dceb6008edd474d.nq.gz
│   ├── 3a0adba60ee2ffbed5abbdd80d3dea7a9a3d5b90.nq.gz
│   ├── 3bae76c0f44e28bf55f685837833d5c1b2575738.nq.gz
│   ├── 4337dbdbcd48657dae27c3acbe45f7d1c512ad64.nq.gz
│   ├── 49a5cbc521014c4db73fa78ae8a59854d263f2cd.nq.gz
│   ├── 4a330087226a0f37d19482480682ab47afea9d4a.nq.gz
│   ├── 4ba588aa6d603057e062e90845cc2eb977e6b80b.nq.gz
│   ├── 4c312bb628dbdd48ef874d6f54f4e2fd4e99eaa6.nq.gz
│   ├── 51a22d02fa069aea271820e0d61d65fe5cb6e4fd.nq.gz
│   ├── 54b9c07d53952ab7aa7adf0e582d4ea9432c9ab5.nq.gz
│   ├── 55839c6446aa3528d4b7a254830a48f13571f04e.nq.gz
│   ├── 5652c751b4467a8e29dffead9fe387987cba1511.nq.gz
│   ├── 568de01d7e4dae2e424e27a8c536b75e9de39251.nq.gz
│   ├── 5800c454ca801890c4c64caf99034c31364b5526.nq.gz
│   ├── 5abb784be172bc67290a5e1aa3cd0673bfca08df.nq.gz
│   ├── 5d56faf9ae08cb604e06df9aa6281e2b51ce5809.nq.gz
│   ├── 5ed243753e169295a32d6251db66180f23ceac06.nq.gz
│   ├── 62dbd8c24515c0df7d881d438afa7c8c9bc63a67.nq.gz
│   ├── 6abaee3000d985e52c3bb86ac9d2c1abb82c9609.nq.gz
│   ├── 6c3bbf2f69fe0cb8917c061cb4be3eb9beaf05d7.nq.gz
│   ├── 6c8e096a5eb9a742c03f69e3ba15477b4721cf21.nq.gz
│   ├── 6cec735fc9211d5bd2d64ba142d752ce727277e8.nq.gz
│   ├── 6fc14a9aa8aa20d9427fb6701186f013fae75d56.nq.gz
│   ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
│   ├── 765b829518046dde4b5da4c90bbcee3c03126e2b.nq.gz
│   ├── 78e010a5fbd40d5c2faacab3c5e5bfc0d1b69692.nq.gz
│   ├── 7903eed2610290b1d90fc15e9cf4b99f9389c82a.nq.gz
│   ├── 7953c39655dbfbd094f64a794ea5dd06ac06d4db.nq.gz
│   ├── 80a4896eee834fbd2c5945f5e6d9b463a57d7c4c.nq.gz
│   ├── 8545b3f49aa15cc3c9fcb5cc1ce9314919e462bc.nq.gz
│   ├── 88eb7d520d4c3b2112a88bdc1d5f45b619ac19ff.nq.gz
│   ├── 8f3f05a42c4a094a64680c8e071a8646eec92d52.nq.gz
│   ├── 91d4cd352ab26c36fa0b4897d56ede6c91f579d3.nq.gz
│   ├── 9372938d1acbde523143e06696edf06d64d2662e.nq.gz
│   ├── 93ca126dc7afc8d59d6e7b3ca3b3025b5f2b4c83.nq.gz
│   ├── 94883779a99043b9e89e811bb599b65a379c7b8d.nq.gz
│   ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
│   ├── 9bf9a5a9390c00a38b9a92195f222f0c436d0308.nq.gz
│   ├── 9e4c30c3ca3aab259ea8b978264731d71b3612fb.nq.gz
│   ├── a3b6743f74a87c392fa80bb9de11c5b36dc36adf.nq.gz
│   ├── a568cefebbd8248707cd908d6ef79d055ecb26c3.nq.gz
│   ├── a794a6c3e59d194a2e10433ab46f6666ba93b220.nq.gz
│   ├── a99fd50aff79b98fa93b3219fc6226fa238d72e2.nq.gz
│   ├── aac60da8d0dc67827664d27c41354e5e16fe51c2.nq.gz
│   ├── add18dfd1a41a3a2708041310d4d9dd5156d946c.nq.gz
│   ├── af767bd6721d3f637e580246c6439c8971bc63d6.nq.gz
│   ├── b11a6446830678856748e1f9dd330cb3af15b9c4.nq.gz
│   ├── b3c50c010c49e5c5c2363fc299f156ea139b2d79.nq.gz
│   ├── be5b9a6eb0e4b3628c78ee450d705c208e3552bc.nq.gz
│   ├── c162c9451bd97e3ba6ec92460bf666050536bb79.nq.gz
│   ├── c5e9c15f4cd5c3bebd5a3e962973b885b40d13c3.nq.gz
│   ├── c96e6045ccda5d77c244513bac7c7ed7e1297534.nq.gz
│   ├── ca32e2b522e05ab2f37a8a937eaa49704f1e433e.nq.gz
│   ├── cce50270f6acebba6eb0da5a2b9aa26e5d20d344.nq.gz
│   ├── d66f15f531acdf0ea239807f7ac96b9a04f4707f.nq.gz
│   ├── d6a0b520096689316dae29360b4efc02e5f2e9ab.nq.gz
│   ├── d7293d7b233cd3ec8aace51e28c33cbc5450febb.nq.gz
│   ├── d7b699c4ee2a8d6b5ad0721e688c005ed28e4fe4.nq.gz
│   ├── d9c2bf5a50ff48658dda1513c0b16e5da21daf69.nq.gz
│   ├── da8e797d8b98899c9bd4e5e77544fd926a93b232.nq.gz
│   ├── ddeb84984128679e2a20b0256f27f6d53ff204b8.nq.gz
│   ├── e370b6abbdcde7d2281f9b73e7bb6924adce107f.nq.gz
│   ├── e60058490df8913c9b689820502f1f7d9d8dc50b.nq.gz
│   ├── e9c7421935f98a12e30617e60dd448f24ba0c93a.nq.gz
│   ├── ea3d5571aa6c10633d88f909985ea711783256e0.nq.gz
│   ├── eb1ce14235120a238d8a3567331d337eacf122a2.nq.gz
│   ├── ec3cbcf9cbac886ecaf3fe1cb76c8c61a2432fdf.nq.gz
│   ├── f0b885018deaa856fcf7a393bc91a507a106701c.nq.gz
│   ├── f4adc8d7cbf8eb84c03f1e46b5ddc21c50278390.nq.gz
│   ├── f7f7bae1c58be3616eea87d6cb7ec08c06f3d540.nq.gz
│   ├── f814f17b793086504cff1d4bc761fb89a81cfc6f.nq.gz
│   └── ff3f9007c93579266a529844d4c4671f47cd43ce.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 0ce3fc8b55b193ce220253bfbc0c3e09bd171375.nq.gz
├── filetree
│   └── 0ce3fc8b55b193ce220253bfbc0c3e09bd171375.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 102 files
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

[RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
