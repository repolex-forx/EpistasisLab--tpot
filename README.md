# Repolex Knowledge Graph of EpistasisLab/tpot

RDF knowledge graph data for [EpistasisLab/tpot](https://github.com/EpistasisLab/tpot), parsed by [repolex](https://repolex.ai).

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
rlex download EpistasisLab/tpot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1bca6c6a51a79dc7370fbd2a8864a561fc5d7529
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1bca6c6a51a79dc7370fbd2a8864a561fc5d7529
│           └── chunk-001.nq.gz
├── blob
│   ├── 007aa4aabb9f7ff8d60d98735325e9bbbf114301.nq.gz
│   ├── 00b4e874c3f0ef75ea01261e3ec83d214f2711d5.nq.gz
│   ├── 01a2c6f93ec788b1b38aea44d26a89b782448973.nq.gz
│   ├── 0961d4711fc0ee4eaa0abaa27ab84baf93143207.nq.gz
│   ├── 096f76c924f0d74cad20afd0bc33a9313c85b18d.nq.gz
│   ├── 0b1efe754f0730df4d8faf5b0f53772d89c226f5.nq.gz
│   ├── 0bcd301b175b754fbd8023be7306b0859eff56a3.nq.gz
│   ├── 0d35aaf49bbd0f3ea325a034318c4a2de8e9da15.nq.gz
│   ├── 12a3faa929d05c0d5cde20f1dd0233af4488afb3.nq.gz
│   ├── 13776fc68768dd97d5408c87fc5afd5947cbec90.nq.gz
│   ├── 13967eaf79bd882455d61adac67d3d84a9cd8d08.nq.gz
│   ├── 158d135abbe92024e1b011f09d3a838e61b08d6c.nq.gz
│   ├── 169daaa2bdc3da883cef62b22273af851167e935.nq.gz
│   ├── 18e742172c07820ec5b25d2524ae574befb440b2.nq.gz
│   ├── 197681a45644c188469ca4250b48c9f207aa28ba.nq.gz
│   ├── 19d3e2ce2497a1ace51438a25af57215f095135b.nq.gz
│   ├── 1c47a9708452bd8b727f0689964a9312f2701d69.nq.gz
│   ├── 1dd8efa8dda84d057f46b0ecc002d51c022b252f.nq.gz
│   ├── 1f5f27e157785ccdea8f3c2faad6b9b467059566.nq.gz
│   ├── 1f8983d382de04c5ea779689f5b4207a83c5f0fe.nq.gz
│   ├── 2609cd6700ee7481d9cc2af000ef8cb18298a201.nq.gz
│   ├── 275662bc3a9ff684f429d8a19fc5b98f05c60fe1.nq.gz
│   ├── 27bf2f8caf9a056238388ded0550d217ce809692.nq.gz
│   ├── 284924ef3c774e3b112a7621ed977a35357bcb9d.nq.gz
│   ├── 2b9560685ea8a6561c316984072a2976280972d1.nq.gz
│   ├── 2c17a950770482af22718ef1cae616800015601d.nq.gz
│   ├── 2ec7ea98694b3c70d09994b4e743dc5f57f165d8.nq.gz
│   ├── 305850a37fb026f9a919328dc3fbb7f6cff30725.nq.gz
│   ├── 306db6c2552697f9729cf81b02bae5afed14b24f.nq.gz
│   ├── 365ff3e519b4052d181f68dbb6b78cdcd250eece.nq.gz
│   ├── 42d46de00b4b24d06d8a82d8839f4915ff948d88.nq.gz
│   ├── 447da63b12e36fa9eaee829a76cc89e33ea52956.nq.gz
│   ├── 4d022860ffdb8950e13a1962b5999f5d5a6c8e37.nq.gz
│   ├── 5280dd6130465c9f6bf359f0a188e6e0ce6676dd.nq.gz
│   ├── 5683a0ac052d3b38478caa6e6d13241f22ee549f.nq.gz
│   ├── 58fd0f597d2115cf25186680fdf4b97f022d2130.nq.gz
│   ├── 5ac42291d5185b6649661a97ee4d5b0f96cf1bcb.nq.gz
│   ├── 5d40c875b496beaabe9d7c62b695615074c0b4d3.nq.gz
│   ├── 5e6e0f51d259deb86af307f392238800807d57a9.nq.gz
│   ├── 5efabc0db7795ed8b7b460334b4a51e5044b72f8.nq.gz
│   ├── 5fd2037b3a732f8d0131e3e6e295f3760efd6d33.nq.gz
│   ├── 6194a7dc652ca119af319fa2db7aa906046f2a9c.nq.gz
│   ├── 61afcb3804f77dce18950ae892a713343d152431.nq.gz
│   ├── 62e0a7cc54d0b797abe13c3baf4f6ddfcdbda16b.nq.gz
│   ├── 6442dc456d969574b05b54703ec8ee219b77b65f.nq.gz
│   ├── 65c5ca88a67c30becee01c5a8816d964b03862f9.nq.gz
│   ├── 66d36f576cdc4b3d01f4ba8820b93011098bdc21.nq.gz
│   ├── 68942f5e7a6366aaeeb8a6321d48fb65eb9e9d15.nq.gz
│   ├── 68cb90bc592e5a14bbcfc2cf3ec1495ab04c1bcf.nq.gz
│   ├── 6a4af6fd0b17473567939d026652f689b1cd62a2.nq.gz
│   ├── 6d687e2134810c2064b5428e77b00da6b39858ef.nq.gz
│   ├── 735237c98d25a45f375dd22f71054e78705919db.nq.gz
│   ├── 738a0a54d6ec18f9bf43d220cb85b87e289d684c.nq.gz
│   ├── 7a98a723d4913c79d820dfdeaa1ca7adfd5440d4.nq.gz
│   ├── 7b5e82607ffef5809380a98778bd2867305ef8d2.nq.gz
│   ├── 7b758f68098bc5bc4847cdc00feb052d3e7fa347.nq.gz
│   ├── 7c0b1be18dfc3eddf655517e0b873a6f2c16c1cd.nq.gz
│   ├── 7f2568b7975858d03ceeb9f3a25ac9f6f4afeed5.nq.gz
│   ├── 7f8e8d2b0125eceed3cce3522b4a5e728f6373f7.nq.gz
│   ├── 7fea6cc042bf2e82e2966e52d5b37d5a0fba7db8.nq.gz
│   ├── 845a6f0b976cf5be5cbb01ea7ff64211d4971072.nq.gz
│   ├── 8883c00a7a9b087d6a0075632658bbfec36bc027.nq.gz
│   ├── 8baf4090136a05e569568176a39ab42e33dbc792.nq.gz
│   ├── 8e86dc8c0b4acbddb3e565cc19aa66e2c346b4bc.nq.gz
│   ├── 92bfde17c030a09ba926580db7d71c4704ac7ba6.nq.gz
│   ├── 932422e73e4d58c96a70ed180d3606bed51f17ab.nq.gz
│   ├── 94022e8b20a532a8fee9b442d620e6e314a10bbc.nq.gz
│   ├── 948fb089232e1ce578bc125260366fc77ff631b2.nq.gz
│   ├── 9504200711fecffb939c580960c0b3e5fc8fd13f.nq.gz
│   ├── 98baa88656eb25a7955131ca1be9bc9242b980c5.nq.gz
│   ├── 98bf7d625cbd5d311137de887172e9cff7039369.nq.gz
│   ├── 9b0a2ea351cb8ea5a99e57f3c15743b45fd00509.nq.gz
│   ├── 9b652749012b506c1dad531b17baa5156883a604.nq.gz
│   ├── 9d2e12ddbe616a6542f576663a72a6999d082cb5.nq.gz
│   ├── 9e70e8983de3e357ff3047d23e4af1a20c4dcb69.nq.gz
│   ├── a11a92a37ed62abbc69da73c46398c66ed96e129.nq.gz
│   ├── a2f2f84f18bafcfd0e706d45a5080654a6d38918.nq.gz
│   ├── a5a83a55402fb406601c6e514dd574aa2076ae29.nq.gz
│   ├── a5e66b813c70dff0809e1e685d1889e27d9e01f3.nq.gz
│   ├── a5e95758d4b8571ca17323d9e86436963b065e11.nq.gz
│   ├── a7b6d985162afb070b5a7014ecd022c382215ba4.nq.gz
│   ├── aabb8cba4594fe66e0f37c932b7a83960fa1adf3.nq.gz
│   ├── aaccde8c52c16f458c92a2fb85b4392cefc7af22.nq.gz
│   ├── ab3764c34c816e1aa1a805b634bd0a628ba494fd.nq.gz
│   ├── abe05e8196b8def4eb4612570dc995846ee85a68.nq.gz
│   ├── acb729c26140b1b7ae679a52ffb7ebec98d1f3e9.nq.gz
│   ├── ad1e76d67078fae904a281b758de9fe096db3bc9.nq.gz
│   ├── ad2b30b934d731c9ac79c11cdf455b597d0536d0.nq.gz
│   ├── ad86a2df28c5414712ec5a0f7cc490851b022a89.nq.gz
│   ├── ade2a30aa99beb03947b776e1911ea67459ca5a4.nq.gz
│   ├── ae32ba3bfdfba556510540cd376777f3b87ca8df.nq.gz
│   ├── b0376cd656d3e3a8dd26c32fe708ad540e38d0d7.nq.gz
│   ├── b07cbea23010ab6f72cfc44f2b1a015346486aee.nq.gz
│   ├── b4b8bac9ceb150e9258a54498f6bb283ee969911.nq.gz
│   ├── b64beb211e82897f7fe9e9c20af168c5022022bd.nq.gz
│   ├── b6adf6b1a796608df314d25eb0bb38055363a7dd.nq.gz
│   ├── b6bbe4418dccb0771d7f7f15eb2aaf430a1cb093.nq.gz
│   ├── b7198f687c9c107ea6869e7d35588e5dd6745d3b.nq.gz
│   ├── bb3b6af9032e3ad470db6a3b1cb96168e1f05d6c.nq.gz
│   ├── bc1abe0e02e296cd69f4f9c0179e0f42022a50f7.nq.gz
│   ├── be4734028d9bc627acacfcf5c87bc455a8f25eb7.nq.gz
│   ├── c5eaa8c4f9a1f237e67a6b795eb9302e7ba18152.nq.gz
│   ├── ca1e8877cf92ea2a98795b61b6d62fa1fd41fae1.nq.gz
│   ├── cc46ae25bd326c8443133672033bf17a276e2490.nq.gz
│   ├── cf130f80882b042e6bd735cfa5dd9b4cd372f289.nq.gz
│   ├── cf8342e717d33efd0753f4a322e6d6247ad45cb5.nq.gz
│   ├── d13e186df8f794b6358e2cbec26a819464010de1.nq.gz
│   ├── d4b480d0c6ea8e6df8ce58631987dc00427af477.nq.gz
│   ├── d4d369a2b825aae64448ae46a3625b39d7266871.nq.gz
│   ├── d632ffe384127782cba9e458e65a48a95c9ef305.nq.gz
│   ├── d74839582ce0d358d27c7560978fbc21edce0005.nq.gz
│   ├── d79423b8d7bc4ce687e088f000d262252f212d60.nq.gz
│   ├── d83a7945cb8f5b68be52a20046e62058c37941c2.nq.gz
│   ├── db78fc0fbbf865f184e9cfe4e854ae6bcd011dd8.nq.gz
│   ├── dc2f3609fbb4a4fd32e8a7f738920aa4cced7670.nq.gz
│   ├── e0be361787769e2cb04bdeb98f497e58bde1b890.nq.gz
│   ├── e13d341613aba12151d6daef9eafa507ee459f39.nq.gz
│   ├── e1a3fcc7a66144b026f360a7daee195acb5e7701.nq.gz
│   ├── e24f2b6a64d08890fd6572407c4278712c04694d.nq.gz
│   ├── e610858a2109ffe9a53860d0464ed95e3d50b035.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9047a65a1ca7972edc1e83932fda05271ac7080.nq.gz
│   ├── ee445379f19f95cf3e8f9dcf30e649e25bc0a2a3.nq.gz
│   ├── ee8ad6980b59223d3e9b813b10c6e12010958420.nq.gz
│   ├── f025d58f73c0b4283149918458ca2d9e7f492d2e.nq.gz
│   ├── f0322ca97d15fc3b604fadbdc8788fc030008f1e.nq.gz
│   ├── f1c8a4b1f403562a6348de9873a8c1e59d349ab4.nq.gz
│   ├── f1df7fa248bddcc0f91ba15cdd20c0255c9551e6.nq.gz
│   ├── f205ef6e8bb2414c86d2efca17dc7cb79ba8d58b.nq.gz
│   ├── f2f29b04f214345e3b6727b7deedd25ce8518c47.nq.gz
│   ├── f4489c1d1b533225af7c53b91da5a1ca7fcf51de.nq.gz
│   ├── f580c18a8cd8423c10cc461654e00214b54e0aa9.nq.gz
│   ├── f72f76f28f651a77aa9d76fa2be7b4dd3bf02951.nq.gz
│   ├── f9393fa7e24ed898c7f92dbe8293a76156d21e4c.nq.gz
│   ├── f9f304d771a0cb940af7c4b4ef171d7f899cb267.nq.gz
│   ├── fc1c58022f340284ab29eafee8dfb48e750eb5c9.nq.gz
│   ├── fd4d56addb5aa0126ec51e386035ed5646398bfb.nq.gz
│   ├── fe37da9fff1b92303d72d8cbe92049afc14ec67a.nq.gz
│   └── ff8949081e8fb3271da1c55831232516f5d84bff.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1bca6c6a51a79dc7370fbd2a8864a561fc5d7529.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 147 files
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

[EpistasisLab/tpot](https://github.com/EpistasisLab/tpot)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
