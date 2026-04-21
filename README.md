# Repolex Knowledge Graph of apple/swift-async-algorithms

RDF knowledge graph data for [apple/swift-async-algorithms](https://github.com/apple/swift-async-algorithms), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download apple/swift-async-algorithms
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9d349bcc328ac3c31ce40e746b5882742a0d1272
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 9d349bcc328ac3c31ce40e746b5882742a0d1272.nq.gz
│   └── repolex
│       └── 9d349bcc328ac3c31ce40e746b5882742a0d1272
│           └── chunk-001.nq.gz
├── blob
│   ├── 03513f643c79a6af4d6589735aaa1661d7ca421f.nq.gz
│   ├── 03650ec4a5f99d436eadb0e61f3305053c761a12.nq.gz
│   ├── 045bf832ebc13e5bb7f7090568493535426ea78a.nq.gz
│   ├── 04d59163d8f42148adac407a3ff653428fde8b87.nq.gz
│   ├── 051600974e69ae7d749c1c3bd38c11abcf45f4f4.nq.gz
│   ├── 060264b434e490b7cb683f291e4fe5c5ab84a3ba.nq.gz
│   ├── 062df1307b29aeb0ea1d7f995b8a3853473c899c.nq.gz
│   ├── 09256190e5ee780b148c29152489594a27ce4a38.nq.gz
│   ├── 0be1a7f9e967c4e1b49256d63ff16bcdd6272deb.nq.gz
│   ├── 0d21cd5a13eda24d62f4c76754c2742647b07569.nq.gz
│   ├── 0de4728a2cc0944f3e62258033286d6e62984813.nq.gz
│   ├── 0e1e99cf13903a98ef865b1f739aae5182d27c82.nq.gz
│   ├── 0fbbdb5a60f46b36ee0856cf8203c480cbf1c7fd.nq.gz
│   ├── 10cb40795fa6f3fd2e7c18976b48d3d5d628a1fd.nq.gz
│   ├── 131954364a0e176ed95694ce37bde8bfb3fe9b7c.nq.gz
│   ├── 13765e3be0f636c192f11b7fe20b4e64891a3d1f.nq.gz
│   ├── 1419d68bd63f861eab2ecd9991921c3c757fa6a6.nq.gz
│   ├── 14766ae7a5b52b226044ae1478526a0d6dcdd797.nq.gz
│   ├── 1484d14f62246176a9540fc6ed719455b225714f.nq.gz
│   ├── 16a250d5607b09542a07db52dad80134ac165750.nq.gz
│   ├── 1730f6364b40564025f431220c75b26445e0e413.nq.gz
│   ├── 1cf1519289f303f9eb5105a20023221562452b97.nq.gz
│   ├── 1d0f3356a9eec081638653def8f86ff807da43bf.nq.gz
│   ├── 1eaebcfeecb74274041f66b699db44bc150c26cc.nq.gz
│   ├── 20a0ddc6c2fc601882ceefc0bed004875f98a9d2.nq.gz
│   ├── 21c40d3206424d5552de1e7b16729fd00577ac0d.nq.gz
│   ├── 24fcb5e64b90f26ff1b15f66dd1e5a0984036498.nq.gz
│   ├── 253edf9ea1928bcab8d537fbe0f13441b2aec31a.nq.gz
│   ├── 25420da72b4a5decc1d27a41b4346235ec6c40aa.nq.gz
│   ├── 25dbd49f0bc5cfcc992a29f2081e282f91500487.nq.gz
│   ├── 27e5dbc126b8c4a7acbafbbd8528c2258084f92b.nq.gz
│   ├── 281471ca70d95acab68f2c65f60dc4fd4c49e7f7.nq.gz
│   ├── 2a779cf6e861c56b194cb76df6be477e38e33827.nq.gz
│   ├── 2c34b4ab5e1b85c67a8aa3a2983867a48f3df8db.nq.gz
│   ├── 2c6bc9fcaf3c3fbd1a803ac0bc6e0cadcaacd68e.nq.gz
│   ├── 2cfab1cca67b69a2b8711f9004d4a14c37fa662e.nq.gz
│   ├── 2d4c9fa6bf3a485ceb9742050700886e9856934c.nq.gz
│   ├── 2d7b92ffd227b7bbc925d568822dfd9de3bb8e0e.nq.gz
│   ├── 2db97f1df2104cf178b1a45a94b526e2b5d53783.nq.gz
│   ├── 2de5c72fe2e10cbeff764ffe609dc2fbf7f3f136.nq.gz
│   ├── 2e1885c5c3fccb75f7081c91f6f525fa86d45b5e.nq.gz
│   ├── 308fbc831f42b495d3be87957595be7d5df9b367.nq.gz
│   ├── 32892678ab68b8b2a6ba0ee2db101d1da45d496b.nq.gz
│   ├── 35dad3a18447a136be13c6c788c89cb5de2a925a.nq.gz
│   ├── 35ea3ef5934b59fdab577a70ae9eb2c4449e57df.nq.gz
│   ├── 3bd52186b8abc78aec97a162143c8931ea056087.nq.gz
│   ├── 3cb64a06ba4e952d0425cc622d4ab97ab290766d.nq.gz
│   ├── 3d965151c1a9a83b568b03e7c7fe9b1e2f163068.nq.gz
│   ├── 3df0a33c5017250d23d869d58849edcc9ff7f63d.nq.gz
│   ├── 400d01de8a8b2873d35dc47127eac5ef5ca81089.nq.gz
│   ├── 42dd2f1ab3821b8ca1f7d888692ba96fd3247940.nq.gz
│   ├── 47cc7e2190a45a027129c3e476b61a5094d744bb.nq.gz
│   ├── 482db1bf4afa82ee08994f1284fc6b6d626dceb0.nq.gz
│   ├── 48f8cfbf35857c8195bb45c9b0a53b7cbfb4200a.nq.gz
│   ├── 492e0bbc7cb80c2072eb312e0238c24f632447fd.nq.gz
│   ├── 4b22bcde417dcb40e1b6bd1bc211b78b35c38902.nq.gz
│   ├── 4c6b2382fbfed3655f2df5f8226e970540b23b4f.nq.gz
│   ├── 4d3e64a29c0c6495a9c1fb24eb6a9919ed1e068d.nq.gz
│   ├── 4ea06e06f41d85ccedf409888bdc647f4bf319ae.nq.gz
│   ├── 4f0bb7d963c2c9ff3d572378f2756ed5a1d87d51.nq.gz
│   ├── 50e2cf281a2812c56951accb296ea2fcab603533.nq.gz
│   ├── 51cb1cf46acd26c257b0cb128c2236411408826e.nq.gz
│   ├── 52a1770fd3772b9ed8ffa833ba0ce6989a058b96.nq.gz
│   ├── 537ab27ec5dfe8b93c2e5a92b36a9ede9c2cd4b2.nq.gz
│   ├── 54c9713a0bc7683671e54c1bb945284776d166b9.nq.gz
│   ├── 56ecbc7711aa4be3048a353fba762865c7ba34f3.nq.gz
│   ├── 57d818364f1a42d718710271d1eb7fdf427ee450.nq.gz
│   ├── 582317c1a2ec46372ecaac648ea4419b7de5ba26.nq.gz
│   ├── 5eddec6fdac1bfb8bfaa0bdd987eda18a9d91891.nq.gz
│   ├── 61b0c78195f2d00acaf658000eeca6ad406a3a29.nq.gz
│   ├── 622cdc4d8d613c1f42104063dbb62107934d003c.nq.gz
│   ├── 625302615f299c76672eb7112591f128efee88a0.nq.gz
│   ├── 627b6e3e607e52234a7ac50dfd94248f776cf591.nq.gz
│   ├── 64051fa9de80ead92be7e8c9bd8beb3c7bf229b4.nq.gz
│   ├── 67464ad6dc8c9fd071c6fcbd66cf0c67e94c8123.nq.gz
│   ├── 69cde581a5b1ad1aa0faced1dcd56a94639e2200.nq.gz
│   ├── 6d2b52bd55124cd7afd8803cbc009a78b34e8bb6.nq.gz
│   ├── 6e0550b9a513b5ce05b3c999ce09bc8b9f763c1c.nq.gz
│   ├── 6ed3a71ff441799184d2d4a42e8b97fb415bc401.nq.gz
│   ├── 6f69fa4c90dba6fa9ba722607413bb9b8b7e8f70.nq.gz
│   ├── 6fca343037205aba6164bbadb7f3e14c31137c9a.nq.gz
│   ├── 712030683f9791d42af8a31b297215c27bfe21e9.nq.gz
│   ├── 71b6c4c8e0ea7cceaa3d34bfaa16a54669f99a99.nq.gz
│   ├── 71ee36c471b4e6731a4931556a0597683aa46253.nq.gz
│   ├── 721c70bacb715123804d6be68f1f06134ca60776.nq.gz
│   ├── 731440e23cac08b356e36f736190dbc46b1b3afe.nq.gz
│   ├── 766106716e02100af8c34bb63c6b0afbb6458cae.nq.gz
│   ├── 7717dd1a3c6e2c661e86008aafe1e606a8202136.nq.gz
│   ├── 778b62de6256c13fe4cd37754534927ce5fe13cc.nq.gz
│   ├── 786a6844010dbac1efe1deb60f5703685e15c988.nq.gz
│   ├── 7c9a3b3cf33c879eecb3f4a74b95cccd169bd2e8.nq.gz
│   ├── 7d2e1980b7e4d20d1ea9f41f888e3681feab1006.nq.gz
│   ├── 7ddeafcb3a8058468be8b3eae83a4a9e9a1a0fc8.nq.gz
│   ├── 7eda70434c11b7e01967337fe8e0f133a45a3339.nq.gz
│   ├── 7f57d72f31b1f8adfc9813812a868432d4624147.nq.gz
│   ├── 80916098d602519acf2872c716d5f3e1fa277b91.nq.gz
│   ├── 80eb8c771e124eddbb1b33a84095a241287a73ad.nq.gz
│   ├── 8283f6e80324b62c30a9003fe58477417ade625e.nq.gz
│   ├── 82e737268637d42a748394fd5bbecc96df0d5712.nq.gz
│   ├── 8461d28ada1ec0223ce82adc107ddb99df644892.nq.gz
│   ├── 86e6fc24596cab482dedc522a99a32ae52ac5a17.nq.gz
│   ├── 888a0c9c9614ec9b4fb10400b91fc84ebf6dcd6b.nq.gz
│   ├── 8b4c83bbb715c09d6948b0e88054c059d490b832.nq.gz
│   ├── 90b5fc0ffc39632132c6a5c55e4859685d5fbafb.nq.gz
│   ├── 917184d6ed08b443bd47af2ea5b59a49a473bc44.nq.gz
│   ├── 93fe23c9f06fe7f07ea98a9b88d17d0167a90de1.nq.gz
│   ├── 94389220894bafb01b86f98e4809f15b1ed3fa4d.nq.gz
│   ├── 94dae2862fc0db8f12907eb2318ebbbfaed39ff2.nq.gz
│   ├── 95d10be8015b4c549d5d6f3e4505b04613860eff.nq.gz
│   ├── 96e49f6caede491480266bfe4d6d2f949f8eaa6b.nq.gz
│   ├── 97392954b13316fc0651afac09220b9e9299c5df.nq.gz
│   ├── 98ed168253e7c259ddf01e72d18cd53816f2d68e.nq.gz
│   ├── 9a3ab0fd136168ea7a4e22a94b373a8f3f68e02b.nq.gz
│   ├── 9b4328c51977e53823b08d923c7170f5b5c0f0c0.nq.gz
│   ├── 9b6fdf3c26abc5e9c4cbdbd24c20d25636b46a52.nq.gz
│   ├── a29984ab0be2cebe8a9073833541644c3edd828e.nq.gz
│   ├── a32c59c300fad5716d7955242977223223c921a9.nq.gz
│   ├── a37cbb079786befd49a79577c2317fa82e0537fb.nq.gz
│   ├── a3e7f1f4eba21f2a9be16074b5cabb90313d5453.nq.gz
│   ├── a3f5aac6259e109f448b33a3c97ddb8f2534dc22.nq.gz
│   ├── a497ce812eaf471d582fab1a68aa454de86c4cb0.nq.gz
│   ├── a7b6b30554837934ab6872a658c588a30a23d391.nq.gz
│   ├── a966405e6620fd043d9e15a517e4cc777f16e5b9.nq.gz
│   ├── a9c02fba51561d1b76eb25eae87febd79db88f2b.nq.gz
│   ├── ad180fac6b6251093a774ae1e2f1b7a4c75c3075.nq.gz
│   ├── b07fb835f00d8d0d2ddb95f2780c0dea65f65ee7.nq.gz
│   ├── b0aa29bb6c5f4716f0ea802a94f94e24c84e2212.nq.gz
│   ├── b0b12d1bb4098f5579fdff80406ba6e2b8aa6e9b.nq.gz
│   ├── b1a056d9015f9839f133374651085a5ede410049.nq.gz
│   ├── b3dacfc5cd52596d0eabc4b159fc3ea1cc1db83d.nq.gz
│   ├── b50a0d75471e8ea6973466c2bff3aa4cbb546899.nq.gz
│   ├── b5d28cd978297fc7f93c6befa8bfc907e03072c4.nq.gz
│   ├── b784cf08e2d8b2e2ddd969d499abf25946893437.nq.gz
│   ├── b7babcd35eda2bc97a53c7e77751dee75b529fea.nq.gz
│   ├── b870513adbbf06d2b5951a0439ebb437c9dc2605.nq.gz
│   ├── b9a5956b6965f5d46de0e69256965e318341a358.nq.gz
│   ├── ba4366ea7939137642677771530311ed294b1136.nq.gz
│   ├── bcdf6a84d031edde36a171331dc8a1227f59ebd9.nq.gz
│   ├── bfb08158140fb6ab153fb58944cf5b7b9355663d.nq.gz
│   ├── c49c9c6cca223ee79d208f3e0ec192b780fd8534.nq.gz
│   ├── c94ab57b3b706728c71af1b44718dff927bb9775.nq.gz
│   ├── c9baca3b311c28a8572f550b5907d4a04508bed3.nq.gz
│   ├── cb01a05cbda88d49fa1d353e8d259747a666ebe2.nq.gz
│   ├── cc772829e2369a31f818bdfe7898f3c607d6ab00.nq.gz
│   ├── cc8f71f61955bdc1c4e615b777fefef6afc72991.nq.gz
│   ├── d1dbecec565bc7066b6eaf702dc25e9da2bf41cd.nq.gz
│   ├── d492cdbf1487ed5bc6b21cba0dc6ff70bfa6f9fe.nq.gz
│   ├── d86484fe45d902e241d9997a48f97e9355d74a6c.nq.gz
│   ├── d9049cbc64c56e2c37eb9fbb5634840e90d0e17c.nq.gz
│   ├── d9948392f44957051f6e1fd53dcb2713622d6520.nq.gz
│   ├── d9ae62ad310df2d2722ea43b34f26ab336e8f406.nq.gz
│   ├── db794e3b0ff413adcd3e9d9fc8a408c711994953.nq.gz
│   ├── dc2c2e66ecd3abcc8584229427c74cf35b2ea50b.nq.gz
│   ├── dcaf2e0d4a32016d27ab6b0237297497672685b8.nq.gz
│   ├── dcd0edfee56c4f2d9cff02e251b6c718caf21614.nq.gz
│   ├── ddd4a03812971537404e1cc6e37bfc83896a4076.nq.gz
│   ├── df0ccecd940d8d4bc93a65169d775f3f3d4ef70e.nq.gz
│   ├── df2aa7c137374913ac641c88332cd7c76c7f1527.nq.gz
│   ├── dfe5aa576827985777fccab6b5f60868045a7797.nq.gz
│   ├── e03d45d5280bdd5eccf552d3f6624358dead7c8f.nq.gz
│   ├── e1a30faa07b57b6d09f1373c18ab0017e7493485.nq.gz
│   ├── e1c0d3f2285747a4233540ec2d5f404bd09f92e2.nq.gz
│   ├── e36bf969f0cb9a57caf42b70ec3d73de116a7023.nq.gz
│   ├── e77f6d8113288cfcade771cbb746725b37df5cb9.nq.gz
│   ├── ead13dee6f69d4e18de21e8bb9e3bf24ab45c35e.nq.gz
│   ├── ebf1b2462e99e78129a5e2ef3fcee32580f18fbb.nq.gz
│   ├── ec1960fb260abff8fd3a08ef01e30f605820aed6.nq.gz
│   ├── ee7c49eff8ab261aac6b132080b630f5f23a21c6.nq.gz
│   ├── ef3a0ddb6cec8d332f16a256522e468fca4400b5.nq.gz
│   ├── ef5d4cad8ce767d2a4f50e2d46382bb6a2f954c2.nq.gz
│   ├── f1e36550e360bf605c8ce81195a40e6dc84c5b17.nq.gz
│   ├── f27e55b8d3511dcef641b7a8a21e575f8dbdbc0a.nq.gz
│   ├── f64dd2c598cbd02fbc15232c16d87be23882f4fd.nq.gz
│   ├── fa15e792885cd71cfd1dd3d752a34fd0bec79ef8.nq.gz
│   └── ffc6035023b9c62625e4e2ec670d647659b9e3fe.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9d349bcc328ac3c31ce40e746b5882742a0d1272.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 184 files
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

## Source repository

[apple/swift-async-algorithms](https://github.com/apple/swift-async-algorithms)

---
*Parsed on 2026-04-21 by [repolex](https://repolex.ai)*
