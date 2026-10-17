# Repolex Knowledge Graph of colcon/colcon-core

RDF knowledge graph data for [colcon/colcon-core](https://github.com/colcon/colcon-core), parsed by [repolex](https://repolex.ai).

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
rlex download colcon/colcon-core
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6bfb100bd8a9979e2903210f7a97724d6b8cf2c6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6bfb100bd8a9979e2903210f7a97724d6b8cf2c6
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ec0d201ff54d020f6d867b34faa76721b82812.nq.gz
│   ├── 014cfb1025f5203deb08cf7ffd224f455f06148d.nq.gz
│   ├── 02d0441c57830c23f36a0a9bab8b3ef98a21bf45.nq.gz
│   ├── 0353f8b2d12d34d6bb4820d364d7bf4b497922fe.nq.gz
│   ├── 049eb7af5b65cb98a9c2bf2beb465436faf2387d.nq.gz
│   ├── 05f39b6fb1d96a9b2a8ba298bacc09e219f50589.nq.gz
│   ├── 072eb0a9db13a6aa6617d547596a2c8012cb9251.nq.gz
│   ├── 07f7d3d8f48ab340978c6343236b8db3a6b271b9.nq.gz
│   ├── 0a52ca27fde9675751a97b2484431fe900c155af.nq.gz
│   ├── 0b11c8aa435ff32f0955c77160d5528de92d14f5.nq.gz
│   ├── 0b9cb3cd61f620049908b974283772dc1653e5f0.nq.gz
│   ├── 0c682ca59036a445adc97d62e6b043895bbbd31b.nq.gz
│   ├── 0cf9f943a4e68dcc8538ef01528970cb1eb8abc2.nq.gz
│   ├── 0d4e18cd9c6c001098c54fcb65dba2a86b1579a0.nq.gz
│   ├── 0ee080cb45bbfe70055f78f7c79c6b8a65d2db43.nq.gz
│   ├── 11f4c25cc9a6ab80aefbb3ef176aa5e2d20d5b81.nq.gz
│   ├── 122615d840ba7f052569ff3db728998de81a6a8a.nq.gz
│   ├── 131c4dacae7a20085baec1863971b13df7540027.nq.gz
│   ├── 13f2df9ba3a64c610a3ae7fd74a4a0ddd4e187c2.nq.gz
│   ├── 15eda1a743adb48cc55129442216cb7e61962417.nq.gz
│   ├── 15ff2d4848de5c4183f2d8a540553e2e68f29034.nq.gz
│   ├── 16749d27b67db7028bce51c56e352294a8f92f0c.nq.gz
│   ├── 17500dcfdbf0c3d8a2bdcb0c25a25bb6ba234bd1.nq.gz
│   ├── 187e6209460c9f7f8ca6bb68d264c4b99dac20bc.nq.gz
│   ├── 1923073fbf1455ecaf5b0812e35623de48b09d9c.nq.gz
│   ├── 199af400b9972b56bf8c21c495d9026408118dfd.nq.gz
│   ├── 1b717fc445566c0946951d12dee849c786329991.nq.gz
│   ├── 1c8a7ceeaf3a1054ddc07419be339ffd84978c87.nq.gz
│   ├── 1df8f561a86cf2cd3a409ab45569eb2f261392ff.nq.gz
│   ├── 1e138e881d95d56a09cad1a0ae7f756e1f5b684d.nq.gz
│   ├── 1ec284dc351809870e05e9a599ead67c9016089f.nq.gz
│   ├── 1ee08bfa2823a2d9adccd20997503858ff427b6d.nq.gz
│   ├── 1ee7342a2edca73578c138705dfc23e96c087adc.nq.gz
│   ├── 2118d545e8dc9d05e94fa62cb5d91c0660200e4f.nq.gz
│   ├── 224efc1870deb28bd91321e3743c4d322958098c.nq.gz
│   ├── 22780757c9498c47cd014a804cb396dffdeb5a5e.nq.gz
│   ├── 23338bc241c9a2648a8a34d484532271c20fdb65.nq.gz
│   ├── 239484b5f3f5a22198dd1cf1e50f439340316035.nq.gz
│   ├── 2656517bdf8f9272562ed5c0457b32b08a3b61fb.nq.gz
│   ├── 29f4dd78ca59289e188d14a1b12a1e12a062cd52.nq.gz
│   ├── 2ae4bc76b30ee41777c07ffd5c9908c0580d9715.nq.gz
│   ├── 2b22c5f75ac680bc12c3d481eb5e9cda9a4fc3ef.nq.gz
│   ├── 3226da1a16ca523498665d3e609a47a2fcfd0dda.nq.gz
│   ├── 326bb66d4c74f0cf8cf0dfc4e79909001f37da84.nq.gz
│   ├── 335f34b383303063bc3462e03b7e5fffc144d882.nq.gz
│   ├── 37013904aff72360ee2106ad941fcdae3adf38ee.nq.gz
│   ├── 377f8e35c7aa338b8ba592a01e476ea684d8edb8.nq.gz
│   ├── 379f44542a4217b794921c4b67ca9df55f0f88e3.nq.gz
│   ├── 3b2a5c298844ebc1cc685d787eb84005bbec738d.nq.gz
│   ├── 3bdefdb7cfc143665826261d84b9d43e9d066e90.nq.gz
│   ├── 3d65110bcbcf0a1a7a5b805c81e958758da672f1.nq.gz
│   ├── 3f4a363beb5e4dd3f0a6f269322e2d8103fd8e8c.nq.gz
│   ├── 3f587380ba45a5fe7c00645cb4b97fe5544980b5.nq.gz
│   ├── 40c39113413556bba01606d436b9fa3117fe3852.nq.gz
│   ├── 416bcfcada2cefb5c0b67742ac3b7ed3eb21caaa.nq.gz
│   ├── 43706e9774bb01a885168a2182d6182c5a41541e.nq.gz
│   ├── 438d62fb32617d12c255bf7bc194cb9db5afefb7.nq.gz
│   ├── 46558d8ad851167ec924f4ae502bec891bd4ec57.nq.gz
│   ├── 46616c44f7852667d7493b48e72effe1783dfc58.nq.gz
│   ├── 495a0c113b21f9865cd1da3066c6a02533b263d5.nq.gz
│   ├── 49913ba169ba6c4e19e008253f859c42f5130ec8.nq.gz
│   ├── 49976380e9368e20700625cb973108d26bbc432e.nq.gz
│   ├── 49ef954180f19412b2eab655284219aefd0b0072.nq.gz
│   ├── 4a3a7f5f7a3c56731bd4903a449ac0fc7ce83495.nq.gz
│   ├── 4c89bed619c725e6d5dd6f6ba616665ff5a47fa0.nq.gz
│   ├── 4d394aeb2fa8413ebb182b999110f7aeddcbac48.nq.gz
│   ├── 4e99116e00fd0ba6f6a1b4cb5000a864d48ee149.nq.gz
│   ├── 4f0ea804fd2b94847bc55fd7e6b9c7f081a2547f.nq.gz
│   ├── 4fa34eb88e0fef876088e8a61ad15f65fd04bb44.nq.gz
│   ├── 5007d101ca5a7c2345acbac540ad385daa22c633.nq.gz
│   ├── 5099f5964e5d4c9f3e55c4fd8154b155e9dcf026.nq.gz
│   ├── 523edcc4e41026195a51faf84dad1e519052f492.nq.gz
│   ├── 53110116033b0f8f6c586eba90cce078345e8c97.nq.gz
│   ├── 56bb5bec4d364b75cfb97fa02ecca830e3d43338.nq.gz
│   ├── 597f3eec306ced20c037fc8c4250ab93b74aa695.nq.gz
│   ├── 5bfd0ce533fd23c77f6dc05c5734be886ed03fc1.nq.gz
│   ├── 5d61fcb1c8c9e44e07845778756811f38fb645a6.nq.gz
│   ├── 5e3e5da7ef82b711c949af3b1f595f8bc7a3d333.nq.gz
│   ├── 60e7be547a7b3442ffb55d1f422681f72113c036.nq.gz
│   ├── 61e7eff780d305c1586c9d2df85429b0bdc7fa65.nq.gz
│   ├── 627f9c3acb84620d92ba85e26e633c1956063fd7.nq.gz
│   ├── 6301a36677e9c45bda6426cc067b4e45a1d811f5.nq.gz
│   ├── 640c870d04867246d610c9b080d2c8bb664a0ed3.nq.gz
│   ├── 64661c675497b803e300348041faafbe3e2d22d2.nq.gz
│   ├── 647b669b2908501f8ecaa5806fe5213c3841cbe4.nq.gz
│   ├── 66740d7c6f804028ef1df2db4fa31af158a0b395.nq.gz
│   ├── 6751566f05e979669db4c39da812d9058cca24d2.nq.gz
│   ├── 686e185e10abb3af06b050a49abe20a459c72257.nq.gz
│   ├── 698119c8effb515f923f1d8cf9d3db1e80a8e305.nq.gz
│   ├── 69b0d9536342ffa365b3769133a7834fc2017bf4.nq.gz
│   ├── 6a7fe518a7f5558a1e2bd48bdd318e0483144801.nq.gz
│   ├── 6a8a577ced63bdf19cc23005a92f940d54c3d334.nq.gz
│   ├── 6f0306adbd6ce6fce2d884e7938e5886b3019224.nq.gz
│   ├── 6f77212159fd32366255508958051a50b015ff65.nq.gz
│   ├── 6f8eecf1becb2f98d8e6ef27a9d256cd2d3e2aa8.nq.gz
│   ├── 74c47d6c273e839e75d2890c1a61709813db0dbf.nq.gz
│   ├── 79b972d279196c43542d6cb4fb4f1c4331f95c13.nq.gz
│   ├── 7b275b79735ce0b802f80cdc37bc3a84e82fc530.nq.gz
│   ├── 7cbd6ac19347042c8c91c6819fc5c38de59b8586.nq.gz
│   ├── 7d34f028a714dae292a36bdb558bb9270efcab7f.nq.gz
│   ├── 8427a8771c071627948857f40cbdb9941ec58edd.nq.gz
│   ├── 857f1177437dd3c7130a7ee7f1157e68ee7ff793.nq.gz
│   ├── 87b5dcbc1b5c22372efd6a296ec5ecfc9bb4e30f.nq.gz
│   ├── 883b5b7d93d253f918d9e5ca00ad040182b438c8.nq.gz
│   ├── 88707822e5f66fe6f0406a6175f985961f353cf3.nq.gz
│   ├── 893b7fd1365bf6cccefbc529d3fb3d137dcd06d3.nq.gz
│   ├── 8a8d32887aff254ba165fa463b68951d1f145281.nq.gz
│   ├── 8b8b31fd76292dbc3555c325e0420df510f80a89.nq.gz
│   ├── 8eb9cd607749885c59f348180797a1fbdcf2df4b.nq.gz
│   ├── 9205e35bfc585a95704903abe71d7e1b1aeb6989.nq.gz
│   ├── 9362f30e84482e7cf8aa73e52f56813322fda8ed.nq.gz
│   ├── 938ecfa1ac3161bd28e77093e1821fc220704f39.nq.gz
│   ├── 95553d835a7f5252fbc7a7fecd42abd2243b8bbd.nq.gz
│   ├── 9795108b4ee0efaf3350a3b0a443a529dab08fc5.nq.gz
│   ├── 97a4c85d3c8ed63811c36d4595db8b2617493e7f.nq.gz
│   ├── 993a687633ca38d9413349a90d32e21d50a74e1c.nq.gz
│   ├── 9973690c14b648a179d3629983d1958777f619b3.nq.gz
│   ├── 99d20e64564e64c81c8bd597d0f8c72f44bbd601.nq.gz
│   ├── a00694e9560ad998e1dc130750d9735389558ccc.nq.gz
│   ├── a3ef44cc99d92f89526e7e11ffbd8add6daf09aa.nq.gz
│   ├── a5dc0aec1d41fab5030a997e0278819bad2b628f.nq.gz
│   ├── a645106f075f8e0e054770091a28afc39360ab6b.nq.gz
│   ├── a6e38c1f872f3b90917523c9f710b7747edad672.nq.gz
│   ├── a8d43869b8c3953e3e404f3526d8f1e44c79ff24.nq.gz
│   ├── aafc127c98389cf480180b76cc444a48df4531c3.nq.gz
│   ├── acaa81cb5088f683be5c0200720e2ee2317527b4.nq.gz
│   ├── ad1a85b098922bef1622c1b766677d39f4e4a07f.nq.gz
│   ├── adab5a09259f2add58a4fc1715aabb1cdf1febfa.nq.gz
│   ├── aeea1d5e0c77a5918308f0d55700f5ea62586f88.nq.gz
│   ├── af28fdf944741f95ef3aa3b0524ee9825f33d9c6.nq.gz
│   ├── b0e35f860a975b1e77ea3d43c36c6de4b4583260.nq.gz
│   ├── b100a93766c172962335977012754772db553cbb.nq.gz
│   ├── b3074c20ac495ce6d0bf46927ae5f9fdcd3b3888.nq.gz
│   ├── b428f4d3479a0c90b8e5f4b1519c3ce46f5593dc.nq.gz
│   ├── b5d2d73f64801369cf50f129303321f4d8d7d6f6.nq.gz
│   ├── b6bbe2f0386ccf6e4146035eed6df0f7a135e454.nq.gz
│   ├── b730f1baebb3c7928da3324671efe3eccda4018f.nq.gz
│   ├── b7745614eac47ea349fdfc5adcf8a1054ecc3f70.nq.gz
│   ├── b7c7bcc6c4b9f93c8774dcce1db7eaab24900ac5.nq.gz
│   ├── b7ce72d7a4a05423d139bda29dcffb5b71198027.nq.gz
│   ├── b9ad4d09bd218c46c9d3960b37af65edd7b5b526.nq.gz
│   ├── bc24356880a8cbd6a4f64ff7b1f578956c0a282a.nq.gz
│   ├── bdb083dc5d886bbfaac9cab955b64a455a1cf490.nq.gz
│   ├── c04fce3dc2cb204350ab3040e907eca0cdd1d5a2.nq.gz
│   ├── c0fa83eca730b04c93e0617530f0dc3213666b87.nq.gz
│   ├── c18dd8d83ceed1806b50b0aaa46beb7e335fff13.nq.gz
│   ├── c315fcfbb2bd5609922517912d428bb40a49942c.nq.gz
│   ├── c5551e862575040c23a2dfde2ba451d0d665e7e6.nq.gz
│   ├── c658e4d83ec3625d1658e3e97d5adcc5d89e9967.nq.gz
│   ├── c91b5839d69b6bd1ad2bc511d6d26087de9eb797.nq.gz
│   ├── c97b22f57839b7e647539247a4479abf65e2c7be.nq.gz
│   ├── c9877e0c9c47853dc0b23e79765e55a340a6787d.nq.gz
│   ├── ca5e1faacd0682d47fbd020b3ad291bb0c0ff793.nq.gz
│   ├── ca94d6dcafb0e57170a4d8551a2f203b2fde16a8.nq.gz
│   ├── cade4c2729135b02827e8ea02e18f53fb600a21f.nq.gz
│   ├── cb18ebc225c708c76251c8b01914898ac6c8baff.nq.gz
│   ├── cbe6ef804734189999cea811e36b0dc3784c3037.nq.gz
│   ├── ccadec779eae40e702e754b67af549e3540c65bf.nq.gz
│   ├── ccde707101e85d335debe7c44255835d67eb288a.nq.gz
│   ├── cce1d0426a31952c0b86dd84cbf179c2bdc9d01f.nq.gz
│   ├── cfbd146437e87b11988638e01aa30ce39d73f02b.nq.gz
│   ├── d43b8992ee97b33dbfe9133e2b89ac28d7ab0177.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d82e251aba90be6a523969a59c9ce706786b5e06.nq.gz
│   ├── d8e4fdc4716f8a8cccf6d949401a13851ab93519.nq.gz
│   ├── da645609b8542bd71e1c7268358a70a530b27e69.nq.gz
│   ├── dc3b59735e917016439be3740beb057d1779ec64.nq.gz
│   ├── df452d881483e2b5fb6eac4859e68dfaeff4889a.nq.gz
│   ├── e075c2071e6af9a856734353c03ed8acf25cc227.nq.gz
│   ├── e18035fa0582fee420d3194ce77f1da98c91d839.nq.gz
│   ├── e23c6a4ffb172d88f42b0b37f65b7844f98e9c00.nq.gz
│   ├── e30cf6d2a50742686c247d3988fdd4de2c055e39.nq.gz
│   ├── e32ac506f3d88a36d3dc4a95643a3295f20e3c0e.nq.gz
│   ├── e457b3ba9461fb112886f64c14e0adc43a7d6a22.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bc4453e6bd81066aaf2501a0d43c559fea8f69.nq.gz
│   ├── e7f475391ab4e723a98fb3451ff07ab0d353add3.nq.gz
│   ├── e85730fca5831e7037a2c76855140c68d9a999b5.nq.gz
│   ├── e916cae0edc54df383b9270f2621344727211cd1.nq.gz
│   ├── e9afe66bc19976af25185cb97266f872931398ed.nq.gz
│   ├── ec5406743723da64362ebf78e7bd285c00d9474d.nq.gz
│   ├── eeea8e1e37082ff2e3dd8d3563682f9e647532f9.nq.gz
│   ├── f2d4c24ebae5f8006870e812dd96bfed374a0f12.nq.gz
│   ├── f3af15c33628770277a2d8e189d460fa593887fd.nq.gz
│   ├── f433d87ec97d961cc2f64e8feb1eafd10da19901.nq.gz
│   ├── f579768cb757d150b672cf3c66fe65618ab05a9b.nq.gz
│   ├── f7b2adebcd77d33dc0d8f47ac87992a96be86b38.nq.gz
│   ├── f7e2590fa18989b7a7186a8c5e028b861b09cc88.nq.gz
│   ├── f7f6885e7e8e6b42973282ac8022cf893bad5ad5.nq.gz
│   ├── fa76cb9c045a12015b47b3c4c40e91c292b8da97.nq.gz
│   ├── fbadf15c3d75fdef39205d46129ca7183b537346.nq.gz
│   ├── fc55ee1b594b022f814a4b014a08717550975b27.nq.gz
│   ├── fc6b48688434188083cc106b7c26dabbc85ed8e1.nq.gz
│   └── fced66d040f0321da9dbe54e3415bd21bbaff84a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6bfb100bd8a9979e2903210f7a97724d6b8cf2c6.nq.gz
└── issue
    └── issue.nq.gz

11 directories, 200 files
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

[colcon/colcon-core](https://github.com/colcon/colcon-core)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
