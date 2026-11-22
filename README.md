# Repolex Knowledge Graph of eliben/pycparser

RDF knowledge graph data for [eliben/pycparser](https://github.com/eliben/pycparser), parsed by [repolex](https://repolex.ai).

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
rlex download eliben/pycparser
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 168af9695d179eee29f6e6ab9db676c248157950
│   │   │   └── chunk-001.nq.gz
│   │   └── 3ec766b7cd94724cba714296509604597ea4ce4e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 168af9695d179eee29f6e6ab9db676c248157950.nq.gz
│   └── repolex
│       ├── 168af9695d179eee29f6e6ab9db676c248157950
│       │   └── chunk-001.nq.gz
│       └── 3ec766b7cd94724cba714296509604597ea4ce4e
│           └── chunk-001.nq.gz
├── blob
│   ├── 04524e02d4e138581a29b1a50819573de25aebc6.nq.gz
│   ├── 04636f082a59ccc92409b22e6db94ef73bacb783.nq.gz
│   ├── 0c96cbd49c086ab9f3af6a7130ab3297ebae4d96.nq.gz
│   ├── 0c9e0fc1447e98b7f63ae8c9eb552c2af7b83f45.nq.gz
│   ├── 0d3e2b51c35355451f0df72806227dc2aab90152.nq.gz
│   ├── 0ed455c8b1ac2b6259a771c2af9d46e220addb7c.nq.gz
│   ├── 17b2ac4d933d0fdad9760748cf73f1503560df9e.nq.gz
│   ├── 1c80f445fede4bcffb15bc46928f954d892e359f.nq.gz
│   ├── 1cfaf18bba4777b475b0d20ac3dd718108b66785.nq.gz
│   ├── 21732a40e5033c49675c960625895c829a9a7949.nq.gz
│   ├── 23148f8364ac432f3791133465fa63c223af7901.nq.gz
│   ├── 24577fc9b72034c7a1c8457f17d042c7c72d6b43.nq.gz
│   ├── 2485d95dd2a25ca48021063cd48e6240f9c97065.nq.gz
│   ├── 248d1a160c142b94b4247ab5e54fe81187b05af9.nq.gz
│   ├── 24ed4f2f65dbba5af444e5ff1aa04b00e31d6f60.nq.gz
│   ├── 252375f893ea1c4fbaf1a98d32e8ccb6f0e85317.nq.gz
│   ├── 25bcca3b42c4a012082ef77e22e755f0502f1989.nq.gz
│   ├── 2b5ac1a9a228e88588776ecaae2e19ce5a2ec414.nq.gz
│   ├── 2bef0fb0ccef79be75b38fe2154a535c4eaa043c.nq.gz
│   ├── 2f1007fb76a02e011d1b18a3bfdbd993c195da0c.nq.gz
│   ├── 2fe14bf7ef63bf7f5658b1a5e8029347e059f55d.nq.gz
│   ├── 344cbc6db07eee751f5677b2cbbdde6c21a53042.nq.gz
│   ├── 35da01da9217750e24819abacb9e5c54bbf312e2.nq.gz
│   ├── 3893cecdb8ca5b2d423dde7d3a5788d0cff2bd51.nq.gz
│   ├── 38c80b38a78207839471490e118feb2e75dfbe8a.nq.gz
│   ├── 3901142180e5c21e3854cb451692917093102d5b.nq.gz
│   ├── 43f5018af4acd686ff910d7f98afe0078ca23ac7.nq.gz
│   ├── 44564acdb2a978ac7a515f651cb95bc17a4e2ef6.nq.gz
│   ├── 481737fba32317a6884f6f8ab8d80ba54cd58417.nq.gz
│   ├── 4918499c95859b4cf14fdee2254fd8dfef1af0a9.nq.gz
│   ├── 49a1820a57405825e151a151ee52a70ae503461c.nq.gz
│   ├── 4a307927d20732ae53e4e9490c140a34a0b843f9.nq.gz
│   ├── 4bc3bd57854501b60f5d74d656f4acd0a13dc5ab.nq.gz
│   ├── 4c1c047d28a94756ecec0e8b93f7f1fe9e98fb30.nq.gz
│   ├── 52ac2739a465f27187c4718129fdba79e13a6365.nq.gz
│   ├── 532fa8eb9c3045c36eba10194a1991567df5415b.nq.gz
│   ├── 5330745159eb877fe558b1eeb98c7a2dc7b9b698.nq.gz
│   ├── 55ded7c91a0f3d8a5ae43a4e72dfb9631a264786.nq.gz
│   ├── 590824dfea102d18ce3da059c472f82bc5006c93.nq.gz
│   ├── 5bc4ae4434752e90492e4a0a2edfc35ca8770838.nq.gz
│   ├── 5f3f83ee83d54b2aa071a271d41964702502f0a3.nq.gz
│   ├── 6036ec67290a468a5e969ef4c574cf6e31b12b94.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 60c7787fb9ed6aec7911ccda19a94cf921ab9c69.nq.gz
│   ├── 6251a9fb398c725d2c761dc094fd3011d8fece82.nq.gz
│   ├── 635750a1d054b7e8ebfa233fdd60d5796a625093.nq.gz
│   ├── 659368b19f12ec7a16b608a7a83310b631a2814b.nq.gz
│   ├── 66dfbb7f71ef9fa8826827115611862cd20ab6a1.nq.gz
│   ├── 68f57b3c4068926599b0f0c2ec7a34dca072eec8.nq.gz
│   ├── 69eff24d6b86ee58ade861f437c5a43903e53616.nq.gz
│   ├── 6d97ff956a41aee8d9cb17c2b4e6adbdbc6bb69d.nq.gz
│   ├── 6f15a305c223583fb46375cc219f055c4bed1a5b.nq.gz
│   ├── 7ac00e11006b95717b20a282e16b9222234f70ef.nq.gz
│   ├── 7b78808963ffc3976c0b69e574266f94da005109.nq.gz
│   ├── 7e60370cb89a9c259058bf3d231ea2a4809755d9.nq.gz
│   ├── 7e7647ae47e621f22c28d461ae70b08d53de155c.nq.gz
│   ├── 7ec500e87f8b5c3044e4abeb586e9e58da3ed7d6.nq.gz
│   ├── 805d46fd93b90457758613be2d73e4aafde4c1a9.nq.gz
│   ├── 832614f56b4c73506128e93312fb4fdbc8bdb0aa.nq.gz
│   ├── 834a8c1befcd0a2eb349f88639eb642086a50a47.nq.gz
│   ├── 8489d449c9695b68bbb905ea6363fc8ea1cb50b5.nq.gz
│   ├── 882a1ed32dc38eaf83ba8a24dd2c8f735994ed18.nq.gz
│   ├── 883520658a7f27cedb1bd249ea2f78d8f3b32093.nq.gz
│   ├── 894783c8fd27dbb4beccd4dcded418e184012284.nq.gz
│   ├── 8cbb28ed60a4b78328c7a598b2a3efc9d7afa0c8.nq.gz
│   ├── 8ea6ff6dd88a8a4adaf65e8bb275e79a17e14543.nq.gz
│   ├── 8eee907fc0564013e4e217d5eabded7724dc5931.nq.gz
│   ├── 9069b94c24c857925ea2971ca1b9d4e48af276a2.nq.gz
│   ├── 91b453322881f9c842e5c2864dd6a50f34f6bdda.nq.gz
│   ├── 91c326cb05be2e52bac371e3f2dd389ea86b50b0.nq.gz
│   ├── 935e1be8dcc0e69eeec84a6919264a7ec77376c1.nq.gz
│   ├── 958bb670186d596a1c7e89b363ba7959c3be6a5f.nq.gz
│   ├── 95d6cc49b271c99d9ad4be57170fb7c8917ef2e7.nq.gz
│   ├── 96a6a0237cf51efd15066fb650376bd8beeb684e.nq.gz
│   ├── 9ff621da9ee4a000e8a6a91700941950ec56cd50.nq.gz
│   ├── a0df6106d923d76486dbdcf3559437c602541cf2.nq.gz
│   ├── a155cbb4a45b7680bc5ff9ba65aee7cde105909c.nq.gz
│   ├── a51239b324f89a96bef3a7e9e4c48ae3bdcc5642.nq.gz
│   ├── a666b982b2f1e84e2cd88e633c0058a7f98198bf.nq.gz
│   ├── ab1426a7b32ced21f8a8995b315f46503ec313b1.nq.gz
│   ├── ab5f16c5e86bc1d01a79c6dfc2802bd6a40e9b4e.nq.gz
│   ├── ab7ebb362b1507a426dcc8795f64f8a6ad1b5aec.nq.gz
│   ├── abbe5d83e8f14092c2db1eca8bf3632e5530104e.nq.gz
│   ├── ae7372c337cae242a916ef381fc5d71bfec33d72.nq.gz
│   ├── ae8212dceb2aaa2a0dd0be9467b6d6bb38b7f75a.nq.gz
│   ├── af32600819c5da071964fa6ed66814db2f06f190.nq.gz
│   ├── af69f5f06e34f8f90b59798cc885627f5ca228c2.nq.gz
│   ├── b007f1903b0d32319b26ef08e4e1c30eae08679d.nq.gz
│   ├── b1fa222b389305d516e63ef4f924855bf08634ee.nq.gz
│   ├── b27b8eb6a17c5b3bf5831005b181da7f868221e9.nq.gz
│   ├── b55f767b8e0d8cf2563a4035a0b7651c3679b318.nq.gz
│   ├── b811ccdaca77642a40e58d5aa2537cc98dc9276c.nq.gz
│   ├── b8209cd2ad8e8ea44e184ee9fe1de41f9d582ca9.nq.gz
│   ├── bca67eee44d3937017e81623bc36fdb1cbdecd8b.nq.gz
│   ├── bd53c3bf0e58608d3a1cd4324e9ed81d22c27a45.nq.gz
│   ├── be6997b853ad0502254a4e92869a4d31d7a6fe7b.nq.gz
│   ├── bfe4aabee72adf129ca0340b88b01855b530689b.nq.gz
│   ├── c0f583d5b8ccfb214428cf1fe43ac95703d52be6.nq.gz
│   ├── c3520775385f74c221beb4d5302299c2c9e31fea.nq.gz
│   ├── c88774bb48d3b406a72e681ccb70f228a2543605.nq.gz
│   ├── c9ad45ef27afa392bd4ca26d52fa9bb40909536b.nq.gz
│   ├── d2627af4eec00b9d65a17276b560240b8fd6e4d8.nq.gz
│   ├── d60d655ad67ac0a51604e8432d7cc1725bbe99de.nq.gz
│   ├── d9bc290a98a5d84351d358ac18aa394a226a9e8a.nq.gz
│   ├── da67a2ce7d0e73f1a542f3b47a371ae220316357.nq.gz
│   ├── deddf49341ed9ac010dc62f8d967e5bf47eaeca5.nq.gz
│   ├── e24aaad808aa1081e9690770f744c4e15444bff4.nq.gz
│   ├── e2c50cb1f39ab0a33054dc1876fad70be30cb195.nq.gz
│   ├── e4a348d96014b74e36f2e68b9a1dffcb5eae9f57.nq.gz
│   ├── e4fba2183587225f216eeada4c78dfab6b2e65f5.nq.gz
│   ├── e5b03360cc7f0c484416c958941a81093ab8b96b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73a0fab0a3e1ebc5c46a4c2c9969557143174d1.nq.gz
│   ├── e7602456d0445d9e3058156cc939a7c257a752c3.nq.gz
│   ├── e7c5daabf37e33bf1fecdb1433addc050ded72de.nq.gz
│   ├── eaa3a6762efd36fe7150c65590b09f250e2f521d.nq.gz
│   ├── eb33c1f66203b856bf32fc63345088762e6fb19d.nq.gz
│   ├── ef517eea61d10638710ef60966f9086b2daabf15.nq.gz
│   ├── eff94bdd2e146d439fb82e7cbd2991339a44e9eb.nq.gz
│   ├── f0da87138a9aeff92d4a4883ea23d9c85c9dac06.nq.gz
│   ├── f2992f32c61e3797a8992a6857d5139a1b14fb38.nq.gz
│   ├── f7c09209e2ff80482fb209cbf0ee386f193c2586.nq.gz
│   ├── f845c0fb110133f42c1479db5b28d88504d9ed5a.nq.gz
│   ├── f952c1d67e09fd1314cc87e5c25c07a253e8e0af.nq.gz
│   ├── fa15b38f9924a715f94b54a4f16145c0e88e7a04.nq.gz
│   ├── fa4f23d3ed7f81ac434d6e6955a495dd566e1703.nq.gz
│   ├── fafb54ecda1e3095b4d6bf3df211689367fb90b8.nq.gz
│   └── fb16db570fe8eff4467abd8980a61b8fcdc31ab0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 168af9695d179eee29f6e6ab9db676c248157950.nq.gz
├── filetree
│   ├── 168af9695d179eee29f6e6ab9db676c248157950.nq.gz
│   └── 3ec766b7cd94724cba714296509604597ea4ce4e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 141 files
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

[eliben/pycparser](https://github.com/eliben/pycparser)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
