# Repolex Knowledge Graph of fabric/fabric

RDF knowledge graph data for [fabric/fabric](https://github.com/fabric/fabric), parsed by [repolex](https://repolex.ai).

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
rlex download fabric/fabric
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ded51893f02c33d2bc7c157624c44a039a952037
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ded51893f02c33d2bc7c157624c44a039a952037
│           └── chunk-001.nq.gz
├── blob
│   ├── 034fb5a71eb7f526a847059ab6dd0a07613a01cc.nq.gz
│   ├── 03fac453a82fe0132a3aeb23e88964e2730e6966.nq.gz
│   ├── 04dab0c0b68210605400cd6c52a5771cd975c2ab.nq.gz
│   ├── 06c46ad18ef0a585d144247cdd818a7906311710.nq.gz
│   ├── 10e0dcedd556981a2ea6c21acbf7763731992e07.nq.gz
│   ├── 12cc58860b4bb0fae297696d643f763de15ce4d1.nq.gz
│   ├── 1515e0eed56a363110fdd2a86a645abe18b88b03.nq.gz
│   ├── 15cb72c0b7791bf0617d1edc72b9092cf55889f2.nq.gz
│   ├── 162fbaded2facd368405cece3a8c4190765dfc5d.nq.gz
│   ├── 16f07d4ad77e473f7682ef8236f630188194a950.nq.gz
│   ├── 17044d85943e959bca4e36babee39bb6c861f712.nq.gz
│   ├── 1ea86ee2b77b74c34e8f82457ad059e36a4cfe20.nq.gz
│   ├── 1fa15a8c4b86aebd420b3dd1a20cbf85a0c014a1.nq.gz
│   ├── 22e1618711140fab0a23fea60cd946950cf79f6c.nq.gz
│   ├── 27154a577bf4f1f8edab720b589bcc614e76ee12.nq.gz
│   ├── 2856e32317db12b4013eafa0ff54729beedb0b8e.nq.gz
│   ├── 288239c96f0d42480cfa8a7ffe19e40b2eaf5a0b.nq.gz
│   ├── 294f1a0084c7d0cb893f4a905a7dbaa228103caf.nq.gz
│   ├── 29c1b2435f401406fcc48b8d30843782e015a768.nq.gz
│   ├── 2d13f12eb50fc41eb6776798a0913937dde4eac1.nq.gz
│   ├── 3096417e07b11f012ecb843a1e25a30a14d42a8e.nq.gz
│   ├── 3212c930799dabb49ffbe2f1b0096947c94334a1.nq.gz
│   ├── 322ae72d95e12c5461a28e07d7ec50065500d911.nq.gz
│   ├── 337513e9f132ff8ea922f206ecd8f417d236e5bc.nq.gz
│   ├── 348f0ac946733393c3929fc6d76bd492c384e758.nq.gz
│   ├── 37039bc6f766aace89df312b26db74697636c21b.nq.gz
│   ├── 3778a2f2f23ebbaa7dcc0aea5f98bb3901ba94f6.nq.gz
│   ├── 3be92177f7594fe75cf9c8763a8c34a84757d909.nq.gz
│   ├── 3d4f0e2af7a1c899f0c48a357e25e5e56698244e.nq.gz
│   ├── 3e83b238142e190eb96a747ba0fa559b078b122d.nq.gz
│   ├── 3fa8bcd788b252635b6643077e3c5704af391b08.nq.gz
│   ├── 415b53db73371275f5d4a78c2fab332ebf5af50f.nq.gz
│   ├── 41ab9cc4aa97c2e45cc2230edc2b8cf1d5d0bf3e.nq.gz
│   ├── 439129fe968ef2ea24694d99f51e3e0137fc663d.nq.gz
│   ├── 4e5ce7262715257aae2c85b896c239b3b70719ef.nq.gz
│   ├── 4ef06f684738a17d487b511daf27b9bd33c93c39.nq.gz
│   ├── 4f4b35338d14d865b959992fcf96f47e8f63b4b9.nq.gz
│   ├── 4f7d397e0676f2023ded409fcd312e05e6fbc582.nq.gz
│   ├── 506f2353afa3cffb605e9ce15a3e013889c142c6.nq.gz
│   ├── 51ba5895864bee632a99e810fa7f77c4e87eff00.nq.gz
│   ├── 5233cf676801c5487ca18b7944d0bf09ae89f855.nq.gz
│   ├── 587a15b35336f71bde3e9da7b815b8a3f80e41ef.nq.gz
│   ├── 587e5f79fa15402c392e89ca2a9b89dea5f5287b.nq.gz
│   ├── 597e698c9dec95dd2f687983287f1b8b112d0754.nq.gz
│   ├── 5e8b6b81fc1d163ab8a8fc9f45179362ea64720d.nq.gz
│   ├── 61b763d8482f86415d8be6ec7235bdae9ebdfef7.nq.gz
│   ├── 64a62b3cc2232ef643e6cf6ac96876a4b59b81ec.nq.gz
│   ├── 64deac5cf3b0a85e91e9a48e2981a767216cc295.nq.gz
│   ├── 650ced7d88202e3327ebef6e50bb9d22322a718a.nq.gz
│   ├── 66021c9d7cde5035931626a4427c5211e3942bf2.nq.gz
│   ├── 6757a9a885b545be7ac3a2fb2394374ed5276c53.nq.gz
│   ├── 68120d770bf73640a20f2e876547ec5652dab91a.nq.gz
│   ├── 6ef30c341cf338b19ef6fcbbd8777cb57df3e7df.nq.gz
│   ├── 6f4925d577b7f7aef47fa75f8b689f9008a54295.nq.gz
│   ├── 6f69a439f5e50d302ad36ce675c12ae49dc57640.nq.gz
│   ├── 70f5a16b3feef1137f5822d2006171b3ada26727.nq.gz
│   ├── 71b78d1d35dc2c6ab6a1de719184f309145b1693.nq.gz
│   ├── 7f37e47a83278aa51db215128655ce0f7b6d9638.nq.gz
│   ├── 8675442ae9166db5c9b7eb4d25343c2b63ec343b.nq.gz
│   ├── 891e7a38076754b195b92b9f9c879c37a18dc2b1.nq.gz
│   ├── 8981e9ff22bdf214584935b309f259f3bb5793d8.nq.gz
│   ├── 89bd0dd20816e7a55314209578cc44c90d9a409e.nq.gz
│   ├── 8d13d5a211d961c47406e95c8c09f2b708a05e00.nq.gz
│   ├── 8efa7e3742b5567c14b181df4abf2282facb3f9d.nq.gz
│   ├── 914f76b31a59918b0dd5fd08da57e05063556b4d.nq.gz
│   ├── 9232413bb105f2f5706703b154a3acbc53746574.nq.gz
│   ├── 93c651c0964456632ef4939f8c4271305c527053.nq.gz
│   ├── 97a4b44178aecd0f0bddd5af80dc34e0ea1ed3ca.nq.gz
│   ├── 97d7f23534c723ab945591eba75c29adb26dae1b.nq.gz
│   ├── 993ca679089a0ab919258edd638261b1d1d3937c.nq.gz
│   ├── 9ad7f6421fa629915eb6eb34e050ede5212618dc.nq.gz
│   ├── 9b91e56cf638cae24e8b645429624fc9b50b65d7.nq.gz
│   ├── a0a3d72860720adfe3c038d0dd7d0805cd880142.nq.gz
│   ├── abbbb44a61038feb683d0c5ad6b9c0c4acff3268.nq.gz
│   ├── accb0ddd0b870a48d7b80395d8536b8180d2dbae.nq.gz
│   ├── b09529addc255a9933c8c88acd3f171a76048e7a.nq.gz
│   ├── b642200a5316280d5e667d52ef94af20b9b31732.nq.gz
│   ├── bc76697e6ac461a259dcbf0bb04edea99b161341.nq.gz
│   ├── bec69b51f9a356b0999f0d93487286334da9f750.nq.gz
│   ├── bf1c74491098f46161ce393ce230dab0a90229ea.nq.gz
│   ├── c00f089d2053ce23f1131cbc07522de3fc0aa482.nq.gz
│   ├── c42d464db3aa08807e7a802084d9c0f78cac472e.nq.gz
│   ├── c47c422b39ab87007b32753d317ecb05338ee7a9.nq.gz
│   ├── c56f3434e32d5c1175472edef05aa22198a737f0.nq.gz
│   ├── c58801b7217bbc054cc51935716f868529c8a43f.nq.gz
│   ├── c64e0304593d86b16054c5ca94ef324fc6500eab.nq.gz
│   ├── c7706d372903fbc0a45f6212469cce561accdc6d.nq.gz
│   ├── c84226657521aad0cfff6d1d6314227b2a167c23.nq.gz
│   ├── c8af29c9f890624c81895f2b489e44db0af3e330.nq.gz
│   ├── c928a33357693322283aec8cee172c8f39d5cb8e.nq.gz
│   ├── c94b86443b9bab48770a8c9ea468a34cc630344c.nq.gz
│   ├── ce0f66e46229a0c80e7bcbda71b0659002332f30.nq.gz
│   ├── ce2acc926a838b4f32dcf72be10dc8be9866241e.nq.gz
│   ├── cfaaa2519270716e4ee61070f34f392975b9212c.nq.gz
│   ├── d10d7dc512c2c6bb0d32613c116496a5b5caa85e.nq.gz
│   ├── d8b938b7a2afa0c873e0d8b0ed30da6b4073a2fa.nq.gz
│   ├── da929053f753591ccec0b64ccd14f3d7b6fba4cf.nq.gz
│   ├── dcf2b7c9102a8a007416589836923041d6a3902a.nq.gz
│   ├── e5d463a7e675609a328eb4995492193352edcbd4.nq.gz
│   ├── e669591357de73e0b8b2692b370a7dce2e6ac3cd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea621cba8da0f687802ef3f5c9d491610c07ee66.nq.gz
│   ├── eaa68852227f722b33b912de9c090c1efc1abb7e.nq.gz
│   ├── ebcff35d0176aec9e6e13a295a7625d452fbb630.nq.gz
│   ├── eda64ff02f5ba6de49a47e0d2ff593a107ef2e2c.nq.gz
│   ├── f2acaab1bb0c89ddd2d9303d4dd78b5300f61436.nq.gz
│   ├── f51e190a1f80179a16cf70af1071077cc4806b97.nq.gz
│   ├── f55db14c0c3e257faa94937b16c4fb902cee2493.nq.gz
│   ├── f8a74565b63219baa9554fbc3539088411d4ac7a.nq.gz
│   ├── f965219e1732426b3ffaf361a702aa875bb29121.nq.gz
│   ├── f9dc270129b0da4bdb352f8b63b0435a11a66f60.nq.gz
│   └── fa6617dda5ef72a4cf8639cc152547148185de9f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ded51893f02c33d2bc7c157624c44a039a952037.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 120 files
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

[fabric/fabric](https://github.com/fabric/fabric)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
