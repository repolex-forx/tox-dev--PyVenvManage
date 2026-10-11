# Repolex Knowledge Graph of tox-dev/PyVenvManage

RDF knowledge graph data for [tox-dev/PyVenvManage](https://github.com/tox-dev/PyVenvManage), parsed by [repolex](https://repolex.ai).

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
rlex download tox-dev/PyVenvManage
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 754fc1a3b7afedd0776e81777efc2d7b7241fea9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 754fc1a3b7afedd0776e81777efc2d7b7241fea9
│           └── chunk-001.nq.gz
├── blob
│   ├── 03754c4c3d9206f5c9ef69e41990dfe26a05251e.nq.gz
│   ├── 07803cc2acb8e39e8fe02997268b0df593c0f099.nq.gz
│   ├── 091eea75d9779a88c52ff64f80d8d728631b6295.nq.gz
│   ├── 0b9bdb19725a3bf4148aa0cc3c66b380f363604b.nq.gz
│   ├── 0e395d4a389dd09bf6eb8555c872ad923e2c3270.nq.gz
│   ├── 15a3ed76bd38b0cedeeff455a216d6ac9a9a592b.nq.gz
│   ├── 15d4a0d7cdc2f210cc5922af93752cac3842c580.nq.gz
│   ├── 1684b548592a51945d42a118645c06530e516bc4.nq.gz
│   ├── 1b55c27901bf38fc908cc49adbb20d36e8f57dbb.nq.gz
│   ├── 1c2cc18b52695fba56a29a155f619ade9ddd7dd2.nq.gz
│   ├── 20a70af6e97bd8fe36c3db7fbedf588497ba4425.nq.gz
│   ├── 21ba4827edbf7c9a5d1331538f4be9a46459f63e.nq.gz
│   ├── 220f93d375a19bb70914391ab389759183167d01.nq.gz
│   ├── 249efbb032ce46a80c687c0723eb172e85f6a136.nq.gz
│   ├── 2a0451e6e74d7843c1d0dd4823d0d8155a01ee7b.nq.gz
│   ├── 35d93fc81ec46c9efcdcf3511ffa9c97f059f1c5.nq.gz
│   ├── 46c9bfea2e257a268159ed774999ae8fd4cb6da9.nq.gz
│   ├── 4882dc52c73ca4e396560916a5d10a86a9f07fc0.nq.gz
│   ├── 49903602eed9d1a1aa5c3f7a1664df279e24a877.nq.gz
│   ├── 4b91f6b2491321d1553477214813a1861dcd0a63.nq.gz
│   ├── 4c3b303555e5c185743f4b86860e5c91b9ddd559.nq.gz
│   ├── 5097068a8d375f5bf0d15693fb5b3615c972a801.nq.gz
│   ├── 52673c9a08ab9afc1a2210f2379eb47af8281474.nq.gz
│   ├── 55f0c728613f099cd30b5bf739190ad296c1fa8a.nq.gz
│   ├── 572f16048ecdcf3b2c35d668a148c8fa3a52d903.nq.gz
│   ├── 5c73cb2740d2be11ec0e25694032b048d8eff842.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 61575b28a7bd4d81cf006fbd07ec0d9e4ff118cd.nq.gz
│   ├── 618fd31b0e3e18f9b1a3563fccd289ac7a01b37a.nq.gz
│   ├── 61abeb445c0fd896397bc74bd6a62c975bcc46e5.nq.gz
│   ├── 685df8bbb8ec68cd416baef53905a72f863df269.nq.gz
│   ├── 6a86b023361ef8eb09dedae2a87855c087649dce.nq.gz
│   ├── 6b70747af4fc3da36ef979ecb3a8e4efa37f332a.nq.gz
│   ├── 6bebcb3d14e76c9ed4bf34c24236d60ec7fd7eff.nq.gz
│   ├── 6c38e29863330dfa1f79f74f36e20e45beb93059.nq.gz
│   ├── 6d90a414e6ef48b0c04134d9150c12ee09f0fd1f.nq.gz
│   ├── 70b85cb28d279ab537b0a71cab359dd6e09c728d.nq.gz
│   ├── 735dc0e6132184a16788e9f38ee0aaff31f7f501.nq.gz
│   ├── 74eabcba19fb31b6006dd57f3c4111464a7e3dbb.nq.gz
│   ├── 7b01259fa4324697c76f1ffe219aa47eaf8cab4c.nq.gz
│   ├── 7ba58bffd0c84f91daa53c2d055361bcef23074e.nq.gz
│   ├── 7db2d2ca0b279e6cfca78b7111381f6c4ee73066.nq.gz
│   ├── 876536a4301320f9f6e83c2c04eb83b5e2507f81.nq.gz
│   ├── 898fd90ecb72f537d565146bc435dea66edfef07.nq.gz
│   ├── 8e31fe0a70bd4f72e239e1d3bcdd9d81c28ade49.nq.gz
│   ├── 917cc8dcbc7ef92905745ce86dd1368ec708aa07.nq.gz
│   ├── 9a9de35102cf1780d5835543747ff6b597401065.nq.gz
│   ├── a2780ab2f29c78df57082b1e8cbced01b2c22c72.nq.gz
│   ├── a6662fc720b801fccf9d06de992c4d8b83495ca5.nq.gz
│   ├── a7d8f28a68b55b8252aaa37c2ff61677f131f16e.nq.gz
│   ├── a89277eaf43e9c3e4c3137458526fb7f192b501d.nq.gz
│   ├── b43a34723f94813b108b9588b6d866308c2ef0ea.nq.gz
│   ├── b4e8e127a76f8ddc879c11a3ca12684e3d889cfa.nq.gz
│   ├── b51e78cdbe2a3d439e7ddcf98b64e93e118ecb41.nq.gz
│   ├── b7286f53b753fce73086bc166a6b262bd49d2ab2.nq.gz
│   ├── be0cf8eb7ad09c05d771e8f43592cb0579bfd87c.nq.gz
│   ├── c8f57fb97ffec32590160d0940aea6bd5c9f737d.nq.gz
│   ├── d02c093c8061b0f113d82da45f4d5ea6ca5bcfc7.nq.gz
│   ├── e407dd26a90924dd4c2e3e377c02eb8b447432f8.nq.gz
│   ├── ecc95542a8aabf15fa0b2737872a78e41ed7a040.nq.gz
│   ├── f281bdc83e4c6e9d6b1d0c5857fb1c9cfcfc1745.nq.gz
│   ├── f7ffaad0d21e2648385c3d6fa99bf65ac3c3b55d.nq.gz
│   └── f88a59314a47167923280ff702dbfa034136a7e9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 754fc1a3b7afedd0776e81777efc2d7b7241fea9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 71 files
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

[tox-dev/PyVenvManage](https://github.com/tox-dev/PyVenvManage)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
