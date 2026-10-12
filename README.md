# Repolex Knowledge Graph of python-babel/babel

RDF knowledge graph data for [python-babel/babel](https://github.com/python-babel/babel), parsed by [repolex](https://repolex.ai).

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
rlex download python-babel/babel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e2a17919f0eb988bfea2883b00793ca4d5d37c4f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e2a17919f0eb988bfea2883b00793ca4d5d37c4f
│           └── chunk-001.nq.gz
├── blob
│   ├── 00afc78ae4329fe0264a44162ff634254316fbc2.nq.gz
│   ├── 02e01f1992ac31a1388a5d2ea764f44a255d8623.nq.gz
│   ├── 04b115822db773879be661cca27ec21f10c01c5d.nq.gz
│   ├── 052b96470a209b45b8421ae328f28fa91f18b4fa.nq.gz
│   ├── 05dbfaae881f56d1f2189fba66f86ca471429013.nq.gz
│   ├── 07b2ad0c711fadcaa63fc453c076ad409808ec24.nq.gz
│   ├── 082174133c226a383a34f0e9cf720e1e56afa7e8.nq.gz
│   ├── 082b2efec1754b789bf20ca8b060bfe0471395df.nq.gz
│   ├── 0a0745b4215c37669711893bb03e03d222e81fa5.nq.gz
│   ├── 0a5135f1461b38866a6d01ea96f58a8e53c2a5ac.nq.gz
│   ├── 0cd4666a288fb7ee790e45e8ff3570e84ac1bb07.nq.gz
│   ├── 0dbeea5b4f37559312a0e01683ce8c78728348db.nq.gz
│   ├── 0f1d5d1338f5dfa654c053fc253636cd94bd764b.nq.gz
│   ├── 0f32014aa8a7cdbf44689865c4ffaf0b2bca548c.nq.gz
│   ├── 0f4b483cf8ebfd5af935aad31847b5225fd14c12.nq.gz
│   ├── 0fb625ba906b8d9d19f5358e89a88e6882b50c01.nq.gz
│   ├── 109c8931e99b2959ed63962f06376bdb9dd77a58.nq.gz
│   ├── 10b53fbee087910b003dceaa5baebd06b503e96d.nq.gz
│   ├── 1103798ff46fe63e5ef05cf4a5ac0dbc6a3b98fe.nq.gz
│   ├── 14cadceff09dc5e0fa9ca1bd7b62aeec88178eaf.nq.gz
│   ├── 16eae65aa6a61847c7846094bb87bce7866917aa.nq.gz
│   ├── 18b4f1f59cec3ff8680bd7b17e80d44651fe0147.nq.gz
│   ├── 1967856f56e5e229dca91b2f6eb19771419d8fb3.nq.gz
│   ├── 19c3ece46e609b62935603184187bbd8303e09cd.nq.gz
│   ├── 1a4ef08f02154b5e762b63352491d957d2cb89b1.nq.gz
│   ├── 1a834d1b79531f20f92416643170e78c28c83687.nq.gz
│   ├── 1d93751c95ab40c4e2c80981e53ae2b2fb530a57.nq.gz
│   ├── 1dd37a7ac7db266eb87336f34f97ab7a2cce73d3.nq.gz
│   ├── 1e8eaa267e32cc5b70285a4cb7d5a70a3544ca73.nq.gz
│   ├── 209e755f12ccfab866089dd255b802ee7bb6ec8c.nq.gz
│   ├── 218813905b74c5aa6975455bdf4a73f053fb0c09.nq.gz
│   ├── 21b1727014d7301c78245ccf10b82e484b40c36b.nq.gz
│   ├── 2413f7139295b895e70aea50542e8b9109849ca5.nq.gz
│   ├── 27f113ddf22b35cecca3c07518703bf8d90eddb8.nq.gz
│   ├── 287f1e07c546633732172ede0cdeb8a105049981.nq.gz
│   ├── 28a0091e9c455c9813836aace1ce9356033274fb.nq.gz
│   ├── 290223cccc928edf427742eb1e640359c9240b8b.nq.gz
│   ├── 2cb97211236f6226ce531a4fe1d147d7e3268bb0.nq.gz
│   ├── 2cd26186beaf54302700ed78ba7585ddfa0ff4eb.nq.gz
│   ├── 2d9c2d069c9d8750192a1767411d7cc17af36147.nq.gz
│   ├── 2fd88befa4c5cfa830a863e46fa229ecf19e2cf3.nq.gz
│   ├── 319b545f0327962b145858e20a89ceb2b641fb67.nq.gz
│   ├── 31cf48ed4cde94224310cd45bff095502fe00f14.nq.gz
│   ├── 32128ff8621bf11aca1adbc97b7996224a3ab400.nq.gz
│   ├── 325afc954c7ca8c451a9daa377e0f8c69880c8be.nq.gz
│   ├── 32a690148c7dcffe3990a55ec552bee5bdbba20d.nq.gz
│   ├── 33a85d38abc8e8c418afb3301c9f75429ea36364.nq.gz
│   ├── 3d33270d048527b429096f366c4d9853b6989a14.nq.gz
│   ├── 3db413dac06edb441c6a7d3ff15e7fa9d87997d7.nq.gz
│   ├── 3fc0b1d225c488f83603ed6d01a6f1585d9c23ec.nq.gz
│   ├── 40006f59ab356c04d16b586d3f379a6baad1f7cc.nq.gz
│   ├── 4026ab1b3274deead5cf3fce2a31ea647991cf54.nq.gz
│   ├── 445ed67a8648952e59ea386ed6c9d2a57b44e8d9.nq.gz
│   ├── 448366076de2bbf81227a19935db1822e32c338f.nq.gz
│   ├── 460d94152071a1e957da50ed7c870fef5d998def.nq.gz
│   ├── 4864c69dde21341418ac9e245f47864114e0c27a.nq.gz
│   ├── 48c15132846b9a2ea4e07848c78b02529cce355f.nq.gz
│   ├── 48c1bb2489b0c1c3a0eaaf7aec4e5ec3998abf65.nq.gz
│   ├── 4a8b2dc60296e331bd8fba02211c6d861971499f.nq.gz
│   ├── 4da07429de82caf9164dfe4671193969d4d83926.nq.gz
│   ├── 4f8c73907c65b37abe1bfe35f358dc060be89baa.nq.gz
│   ├── 51081f71df939ac562720f21bd0ccaf97efc2bb0.nq.gz
│   ├── 51c1a068837cb6134df2f4fab0d99f544fc773ed.nq.gz
│   ├── 5385fd067c5f2433249ee2445e466a4ee2274746.nq.gz
│   ├── 54f8de1a9231acab5ccbebaa00449cff66daa047.nq.gz
│   ├── 5901c873b9591da65cefcbfe4954006ac1259650.nq.gz
│   ├── 598b722de4e4ec7579e7d5dfd167d4988a5cc695.nq.gz
│   ├── 59cab1f588cb0a7e80b8135577c4d867f7f27503.nq.gz
│   ├── 5c3d2b23b65c5e98a73f824a49c2167a46bea3c0.nq.gz
│   ├── 5ca62087905e63c4d60e9a7d8fcb3dd89eb9c169.nq.gz
│   ├── 5d07f01676c69b59ad93762664b9c21d11661261.nq.gz
│   ├── 5d5d63e6623fc2a2a524e1fe2d67c2082743d896.nq.gz
│   ├── 5d6fc09c371a13bc06d0aed9c2fd096efc38c966.nq.gz
│   ├── 5ddb3e876bd679f6600f95d748dc05d6d314ffd8.nq.gz
│   ├── 5dfc1aaa981a554426addd9bbb713a4eeac53e13.nq.gz
│   ├── 5e6c28255a7deffbbf4a3f2a13df3b9606e6f2e4.nq.gz
│   ├── 60af20fd8e475eebc9534dcffbe630f180bc9967.nq.gz
│   ├── 640576451506f7e465b4eb9c6aae48a568f8ea25.nq.gz
│   ├── 672bbfe708bd12d1c31f5f510dae8352ac23aa77.nq.gz
│   ├── 67b9f24e1fd97068341f568ac181ec9064ef24d6.nq.gz
│   ├── 69a2be2378a0395a3b0f36b6908b135dcb59f8c9.nq.gz
│   ├── 6d034cfd60162a3c06f64bbe1e6f128128dc4d54.nq.gz
│   ├── 6e6c2f45f032494e423963ba97e37a9c05b23de6.nq.gz
│   ├── 6f02b5b42eb6f920549794b3b7497628151c2039.nq.gz
│   ├── 6fad84304066521c225e26adc8a04a712ec63479.nq.gz
│   ├── 70dd2322cf3b12c14df15bfab5a72bd7d11b2720.nq.gz
│   ├── 710e68187bb62fcb8eb6c3ced889ea865624ec7e.nq.gz
│   ├── 72e8ffc0db8aad71a934dd11e5968bd5109e54b4.nq.gz
│   ├── 7403a95ec4f21b7f207c3c9ef37dd2d1c32f2675.nq.gz
│   ├── 7733f70b1356771ab909873784edfd21847328eb.nq.gz
│   ├── 79aeecf812b56c3d08134545326fc824e480e760.nq.gz
│   ├── 79e18d46d37b794bda83ba11d751e4c0fa86c1dc.nq.gz
│   ├── 7b626aa1155f8b5557454655bd6b4b24118cd397.nq.gz
│   ├── 7c730d32519a2e58c956a30d73bf37ca6c892ab9.nq.gz
│   ├── 7cf11c046c291d77a7b9961d24fadfb89450f6f2.nq.gz
│   ├── 805aaff6f35c1946ea96ed17f703a7d9d8773d2c.nq.gz
│   ├── 8060875c307123012418676deef8e0f8f3a2f327.nq.gz
│   ├── 81422ed48f74e5598c1d3179ebb87b5dad5c4c00.nq.gz
│   ├── 8183238ab1c7f1b7f360cd8536d5f4f75e3fe170.nq.gz
│   ├── 82cb37a221357b0cc457bc125dcd9a1c1ff632be.nq.gz
│   ├── 82faa85b5e203c0c6a74e41e8e3dd71e7ab8d0db.nq.gz
│   ├── 85a1507446fdf7bb3f8b26e6f78c8d9a1f656a26.nq.gz
│   ├── 861b74f3c812088755fd185d964e82a244503bbd.nq.gz
│   ├── 89826e834f7107a33b28d7b695c87e7f67c15bc3.nq.gz
│   ├── 8a6ac28b886750ea818fe6463a286246efb29afe.nq.gz
│   ├── 8bf614cb6e8f283bb361c618534b5b95bb7f8674.nq.gz
│   ├── 8c038ba52ffd40968befc743b3332146234188bd.nq.gz
│   ├── 8c071f8ca1d36016f331ce88daa439af6c6a0ee3.nq.gz
│   ├── 8ca49915764cda3060e0b929688d2fc42d77c991.nq.gz
│   ├── 8cb6375e350e71c7fe896925597d7afa8813717a.nq.gz
│   ├── 8cc2492e87123d73a1f4fbcad4ce2fa58d7b2c7f.nq.gz
│   ├── 8daab7ee6efe3b6f3c2a2594b711e7a9026eb5e2.nq.gz
│   ├── 8dde3f299b0f6a77bf6949c4820ccfdcb5560b90.nq.gz
│   ├── 8e429217e640e8055f5fb8471354bc714aa38645.nq.gz
│   ├── 8e4f7a608d0fe66a0e3c5afa4ef3a801b5cefcf6.nq.gz
│   ├── 8fbefdb87162a279d1f2ee144179decea3b1ad03.nq.gz
│   ├── 92d76782435f627dd893557f47f223dd8e806b73.nq.gz
│   ├── 96f467d27dc84909918ef70976c8f1207130ee12.nq.gz
│   ├── 98660a5ff985fa2c7b5b2e28ae6b074dcbe480c8.nq.gz
│   ├── 98c9cc05a5fcf22c41172c39a3b1c495a9f883f3.nq.gz
│   ├── 9992684d45a32781bdbf0951bf24a0cd7b87820d.nq.gz
│   ├── 9b0b4b77915c2bc10af265d7f7665da38173ffd0.nq.gz
│   ├── 9eb95ab2e98e50b596fe563770112a0b11e177dc.nq.gz
│   ├── 9f0c80b574e6a598dfb1facaec0274566ed940e0.nq.gz
│   ├── 9f297b2a19a25a6cb92730d59394f6c808eacbad.nq.gz
│   ├── a2bf728cca78ad65eb0c686ac732c3ea9050c110.nq.gz
│   ├── a2ea3b6ca86a217431e90aeca6de5966104f6a6e.nq.gz
│   ├── abb36fcf56b58a77d64e514267a45aedc2ed101c.nq.gz
│   ├── ae3f8bd58ccac0ef27560e7cc065ae12ab7606ee.nq.gz
│   ├── af6dfb144214e6a1e452ce6cc605c4988c0f3f2a.nq.gz
│   ├── af83510dbe05c8a7365c15b75683c8d0f28d3a58.nq.gz
│   ├── b09e184e8a8698a1615f7d1a22bb3ddc22804304.nq.gz
│   ├── b12a1434278fa07820dbebc007ce4f6025b617d3.nq.gz
│   ├── b3292bdff8ed5429eedd7f409839979d408beb6a.nq.gz
│   ├── b6214932e487241f6de9be86f87a17b83e062646.nq.gz
│   ├── b6c859800304d4aea57aba65b4c167ec504c7ec1.nq.gz
│   ├── b782521e5c2b31c692622da0dc3ee51738fa7f9c.nq.gz
│   ├── b9eddbdd9b831a21f0a0d733d3d4f31614d34439.nq.gz
│   ├── baafc5451b6d255c6b92ea39c23bbccc90f086fe.nq.gz
│   ├── be1cf970fb27b5162bcf9d2eaa646d35e1ca61be.nq.gz
│   ├── bf2eb2b98de66f21ec2c7478d3a1dff40f7a2a10.nq.gz
│   ├── c40f29f04cc47705da83f87d904f3e4db78f7a51.nq.gz
│   ├── c43bd56d2683cd4651c667e3d5bdd27e1d2bada8.nq.gz
│   ├── c4898facec9282eba672ec32ea16acd9902d614c.nq.gz
│   ├── c6ec2ab179446869af44fdf6a53fc89ac3aa5c0b.nq.gz
│   ├── c7387d7445d6f86055a0998c75f78a7dd7305677.nq.gz
│   ├── c835d60a7dd1971e901dc8abe2dc144e2ff0a029.nq.gz
│   ├── c8b8d17d5d412a414f5c49a1fcc4e90694202005.nq.gz
│   ├── c8c4f28a6bce97cc9e959d50ee141b9f97479de2.nq.gz
│   ├── c9046da0353623ffbf8d9ee321d159669d9942e4.nq.gz
│   ├── cbc1d8dd2fcbe2631dcd3a6cf28d91cf152519bf.nq.gz
│   ├── cc83f360b5eea5791b5c79fb059332e54582aeee.nq.gz
│   ├── cd9765b1e50f64ba9bab70541ea3422f36c4f178.nq.gz
│   ├── d17f5d4aff925115d2a080a6f5843d7b568a5924.nq.gz
│   ├── d20a1831591c5098716843fd122ddd87067dda3d.nq.gz
│   ├── d309255c00a2364034b7b9dcb507e0e65b1d1856.nq.gz
│   ├── d3245e747a8bc085800a555ac3ea9f4ccdafbe4b.nq.gz
│   ├── d526b6a73d5493bc43acfac67c209485b28a844f.nq.gz
│   ├── d6c1382a7236041011fa8643457626199b9b5fa3.nq.gz
│   ├── d74c8e7a740c58d67143463d77d7ac5e56331528.nq.gz
│   ├── d751b58f7d21f87c1a2fb67fd41ee4151269aa50.nq.gz
│   ├── d9addae678a112da83eae34cf0fc24b611de3bd6.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── db94b7055178ed56d62da2b240443091bf5b6a7b.nq.gz
│   ├── dcb938775752dad9de0e90b65947691042a03cb5.nq.gz
│   ├── debc00a806269b9b6f056cd92d57f392dff0aa9f.nq.gz
│   ├── e194d34c18046b9dc19962c8b072e227b6df2bde.nq.gz
│   ├── e1a1d707d0738b86621871ebe61b309b816df61a.nq.gz
│   ├── e572931c2f6cdbeb45b08a756436db2ce30f49de.nq.gz
│   ├── e660fd93d3196215552065b1e63bf6a2f393ed86.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7e67052c1fbdb7e88761fd6e8f08e97d54cb54e.nq.gz
│   ├── eb817579678d4cd72a8cb00b54512a93d43a32ff.nq.gz
│   ├── ecd8a2b2668c97ba7598f681878521b85100df72.nq.gz
│   ├── ee023abde7dae75dedd415a515d4002a5a7ba03d.nq.gz
│   ├── ee16dec0ae73b07a68d3dd5b14938cf16df199d3.nq.gz
│   ├── f054dfab89e84d5056e08db739e663a8c8b7d642.nq.gz
│   ├── f22367fa1d1553a4a7ffcf078778c55d2db4db92.nq.gz
│   ├── f308741793f81128780b2a18a78d5a24e47bd7cf.nq.gz
│   ├── f51626e2538f60940c4d72846be470438f99666b.nq.gz
│   ├── f77368087367365cfc0f27252f78db07187493db.nq.gz
│   ├── f9b13e4aea7562408ac1d327224d1164c9d42ff9.nq.gz
│   ├── fa638ba58df7452cb73c603fa4430c8e025571c5.nq.gz
│   ├── fb01a25f7af1117feb16509691dd4d1d79f19179.nq.gz
│   ├── fd7ee754df3d27d0b8c1f9987a6ef5fff4eb6a75.nq.gz
│   ├── fdfee9c2fb54f5dfa7cfdf496b85ff286921e315.nq.gz
│   ├── fe55a89fca7e6c3a733dc419cadcbbd066d143e4.nq.gz
│   └── ff04df1719e515d435647972b07e5cfbc2dc70d5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e2a17919f0eb988bfea2883b00793ca4d5d37c4f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 196 files
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

[python-babel/babel](https://github.com/python-babel/babel)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
