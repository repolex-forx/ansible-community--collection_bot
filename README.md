# Repolex Knowledge Graph of ansible-community/collection_bot

RDF knowledge graph data for [ansible-community/collection_bot](https://github.com/ansible-community/collection_bot), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/collection_bot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eed09ff73ec1d5828bbdc89e900494004e09794f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eed09ff73ec1d5828bbdc89e900494004e09794f
│           └── chunk-001.nq.gz
└── blob
    ├── 0230fde7b8224bbc7157133bb2beb19a8407b5c4.nq.gz
    ├── 06a7b4292614ca2ff2074c10b4e100b3b126cf3a.nq.gz
    ├── 07453dd8e8668c09c0c8994a69cb5bc3ec07549f.nq.gz
    ├── 07eef0b2f0a0c3f81123652c8c858584df65687f.nq.gz
    ├── 0bb335c01150f8d01154b2f27544f7a4262e31fa.nq.gz
    ├── 0bbd525657522ee8bd08d0d8eebe5fe7cc97fe7a.nq.gz
    ├── 0e7a06f0cd2c52d688f523640c64d4e7a2c54e5a.nq.gz
    ├── 0f64f883030e107e78f845b84d3fe2855034da07.nq.gz
    ├── 0f7ebe44ff96c4c9a7491bdac1d82067715277b5.nq.gz
    ├── 0fbef69eb6396bb60b4d9af67bedefc8db69fe62.nq.gz
    ├── 10ceceb00e2f87862b05998a51506af9990e64e4.nq.gz
    ├── 116df8299af11fc58065a6b4a7191a0ed5755812.nq.gz
    ├── 125b45759344aaabd9816935a9127c6d4af941f6.nq.gz
    ├── 1321c1d8b556355ad857b2419a7dc7b96c449d3f.nq.gz
    ├── 138ef2c387de40b8fbc65c22e821c35e1d63c5b7.nq.gz
    ├── 13cce9dbc4d9a377dca767b7c66e8a113f0859eb.nq.gz
    ├── 14b10bbe864dcea501ef61b1cb9d737ebb98fc35.nq.gz
    ├── 167dd5daef19e0b7209d33cc682724c4aab76853.nq.gz
    ├── 167e73ff7cf84343cf23f85f32055811d10b50b5.nq.gz
    ├── 18288b7b48f3a6456ce51ca98a86ee333c83aecd.nq.gz
    ├── 18b5008273ae293cbd04a934d78c6cc70dba7220.nq.gz
    ├── 18d67399ebe51af44f2426301b94496f3822a6d4.nq.gz
    ├── 1961ef36ac45483e94f6046967de99606217f4d7.nq.gz
    ├── 1a07408e07415a94a3836ba3c15d14441b5213d9.nq.gz
    ├── 1b05f253eb11e20888b1cec11b8c183eb5c5d35c.nq.gz
    ├── 1c35dd7c53ecfbc09b783b93e90d97ad955e2b30.nq.gz
    ├── 1c43d11f7bb61f50f315733e387f508c93d6f992.nq.gz
    ├── 1def0e8c3215f066b44bda94e1064350cc5f9fee.nq.gz
    ├── 1e0be148e5ae60af1c9ca32d77d31005aafec65f.nq.gz
    ├── 1e1f92ae368dd4cf1373616272920ce1824d201a.nq.gz
    ├── 1fc1c6bf368b7d695cafcafd1eb2d7edeabf61e7.nq.gz
    ├── 20ec074ced8fa44862d6706adcf50a618311e03b.nq.gz
    ├── 212e2cc6fe71e5c5e2b93efbb7cbcf4203478168.nq.gz
    ├── 219d66508bbe86c7e377e1de036c7e22b09217b9.nq.gz
    ├── 22dd561e3ae5797efd4ccc383d4ad57341abec7e.nq.gz
    ├── 24eeeb13cb8918a965884cf774d6f683bfd4fb18.nq.gz
    ├── 25ba8791ad587ccfd83f6eb576cfbce75cc561d4.nq.gz
    ├── 2608751e86c75b283f290f4e187a58afba6aa0e6.nq.gz
    ├── 26bc95a73fb809783ff79e055438a2c77e757444.nq.gz
    ├── 276ae551fa1966a6d187cf3209155570ba1059e5.nq.gz
    ├── 279732acb90ff4380baca4800783388fb7334aae.nq.gz
    ├── 27a94f4bc7ec6263da6752626aff674f1696788e.nq.gz
    ├── 28a002b9ad58ea424f76d2f23ffd87fbc9281da0.nq.gz
    ├── 2c4ab17677bc06cd48cc5f531cde2da0b06e4e54.nq.gz
    ├── 2cd57cea76507d00193db7475b46aa38be3fb980.nq.gz
    ├── 2d82dfe5eecdd0bf0ababe0bd1cca7af5a89600b.nq.gz
    ├── 2e24fb94daeb03fd841e8d76f5811e704e46a53c.nq.gz
    ├── 2ef09474eb2d385b938291fbc8eef2bd20816a1a.nq.gz
    ├── 2f1ec98f32b852d8e5381cca7900a6234e04842a.nq.gz
    ├── 30063d8f7412239c6cf4783001b4e30cbabffa22.nq.gz
    ├── 300975953dd6bc3f3860a1564fee7543bfd97eb1.nq.gz
    ├── 30ad94a2c3397e08dd5991fe5d9b188a0a64359c.nq.gz
    ├── 34dc052c5945c8e62cc393c9fc12283a79c8d539.nq.gz
    ├── 353b8ae2c6826160381cf2e02f931dbea2814fa0.nq.gz
    ├── 357d541090f58131d40078ea1967ef88babc2041.nq.gz
    ├── 3706f2510d406c87cfa20c1695c9e631fb3fa0dc.nq.gz
    ├── 378e9b9ad9300848627fc888e8fdee00f60a12c5.nq.gz
    ├── 3791dbcfb55da7af72025de56ebeb4604ca11bb6.nq.gz
    ├── 38e985569481853ee6ef56d56676ec1d2279be61.nq.gz
    ├── 3916c5bc310692baf88e41339dca30b7824f3728.nq.gz
    ├── 3b66c49f26dca919af1f8f694cdbb38ad54fd405.nq.gz
    ├── 3b6aaa774c97ffc39e0083930968e6676a2143f3.nq.gz
    ├── 3bd62b995e3c0b7b747b2026fe225f1d726c1e06.nq.gz
    ├── 3cbb1d3e19956e831701dfbe2b0c904c9e9de78a.nq.gz
    ├── 3cc842b1eb58aa5ce6801a664fdab6012047fffb.nq.gz
    ├── 3e8245dadca1eb0657a9ac5bcee1a5297597c97f.nq.gz
    ├── 3e9214b905218876f20c509a61225de57cae4a1d.nq.gz
    ├── 427a0c22c38df2a38c8c9ca15004859b30f60f37.nq.gz
    ├── 44e50871cdf899ac1fe6b6004f973c6bc20b0fcf.nq.gz
    ├── 45ec8218ee98bc5b2ecb89843cb022e1fbf0674e.nq.gz
    ├── 47667a649c32a9d1dec87c79496b87f67a0c8631.nq.gz
    ├── 47980ec592f7fc12cdee192992223c7e895cbb11.nq.gz
    ├── 483aaa34d2ca114f6f13032feef8c5f4eb646465.nq.gz
    ├── 4874e52132f207880f3ee9d7672f73db253b7f7b.nq.gz
    ├── 4bb41c0d139c5c40a051e86e5d3f13d1b793ab12.nq.gz
    ├── 5004ab287b54e1d17e7482697fa7fb77992852a7.nq.gz
    ├── 507497b2393667140da8e9d7ee7d642cd3ca0245.nq.gz
    ├── 509ae72c1317b225c2f5e14ee23675fec9b86c13.nq.gz
    ├── 51c522060f8c9000b10d401e7bc8e1063889a4ef.nq.gz
    ├── 540144879383cb65cebdc0d840da68a1587cb8de.nq.gz
    ├── 54cb67947698e61b05aa3870796e44dfa11d22ce.nq.gz
    ├── 550f635b76f2c4de836376462feea1bde171b846.nq.gz
    ├── 55777d0997aae982a6d0040256f531551522eff3.nq.gz
    ├── 56ef02cca64a830aa6e2b78789f6a8f84d80c8c2.nq.gz
    ├── 57307d9ec009e80fd5807d27cf3c44f05e17407a.nq.gz
    ├── 5767efb84e2d34785442af6533ef5fef76d201e6.nq.gz
    ├── 57c5d4b90dc6d8d0c54410a7105364c02cbe2f8b.nq.gz
    ├── 58577e74155a1dd4b0f3b0d16f5c38c6f91ef824.nq.gz
    ├── 5af2aee3bd0b2df53c00cb212ed958555ddd4372.nq.gz
    ├── 5c23624d9e911c8a2baf515fd37e6f720de26031.nq.gz
    ├── 5c9e9649b0566531da62ab5220fe218829576e60.nq.gz
    ├── 5dc57c3c5be24689b6565ee6065e5c4f710be70b.nq.gz
    ├── 5e0cb79dd26de710a88de7f310e39d4fadcc7819.nq.gz
    ├── 5e95a58dccd44494dbee07c43b92923b4f3000fa.nq.gz
    ├── 5e9f8ec48a3014af9e5a1d8590bf5385c5e3159b.nq.gz
    ├── 5fe712460cc784f9ba16072e6e9815da74791052.nq.gz
    ├── 5fec6947c8215a3ca94f21c2f1e50cb10e021aae.nq.gz
    ├── 6073a74ef78e4f8ad92b4331fec6f156688a0eef.nq.gz
    ├── 6111c58a8d5a53a93c1663b6902d1395c11183a9.nq.gz
    ├── 6122e414da387f9b1e87b6ceac819e40967c40b9.nq.gz
    ├── 6325045d12c1d60d1761e1dacca4872f913c5062.nq.gz
    ├── 6358930b909632209160121917520ca743c12abb.nq.gz
    ├── 6657bd542186f4c81e1c4c50c314c92592be3005.nq.gz
    ├── 6780d91e1cdbac01016dc95ce210247a17ea9318.nq.gz
    ├── 67f04d1c6b13b811f017921b53ed9b92403ffe0a.nq.gz
    ├── 69c031d12e67b1bd90c0826c8a686d93507c7218.nq.gz
    ├── 6a976ac25ed95256318e779cf69258a646b5b9ec.nq.gz
    ├── 6b0b8f1511a778b10d71dd1fe6b98e18d9b07dc4.nq.gz
    ├── 6c25b19180d9fc5c2a3afd27924062c92b11d311.nq.gz
    ├── 6c4eb1bcde1bb556693ada0f058fc167c4d1fa30.nq.gz
    ├── 6f9c598fca71b438e0437d8979609d253beec0b7.nq.gz
    ├── 6fa429661399811866b45434903ecbb16dc29eab.nq.gz
    ├── 714c2dba79e10d91128e429159b79b4c6519e396.nq.gz
    ├── 732475539a5400785c7b36fa69b601ac3eba2539.nq.gz
    ├── 73f6d393f197b84d1bcf43674719596e6ac2111b.nq.gz
    ├── 74a8b83c6f0bab17b06e2b16714d5ce76521a94f.nq.gz
    ├── 74ae8d91fe9c3f106d7968dccfb11b58e40b8bb1.nq.gz
    ├── 75cbc95d29a2dc39e73055a638ca1ad63fc13931.nq.gz
    ├── 764c7ecb293b4142e6941883a33e7e2494eff835.nq.gz
    ├── 771dc610a7af6a0b193474367e5d73454cbcb28a.nq.gz
    ├── 79a782637ebc61aa78bc9af0f103f56158887151.nq.gz
    ├── 79abf05f5b2d00d1e44f71bf8304ffcf7dc4e7b8.nq.gz
    ├── 79d008f52c96c4b176feefbd21fe250e3714c84c.nq.gz
    ├── 7a2ae066e135ca09b351e5bb5e1fbfb15a6f6ca7.nq.gz
    ├── 7a336ef03cbf56515598b6e69e6a636aad2f70d1.nq.gz
    ├── 7cf2bd68da3c38586c6dbab46cafc06cd4d1d03d.nq.gz
    ├── 7e569ae141ca5ba3f22c782304b05f08b4a01130.nq.gz
    ├── 7e907587a161ff26bf0c0dc0c243c3a3f1c4df90.nq.gz
    ├── 7ffe71935db86a6d6ee3483116621b99775f1a89.nq.gz
    ├── 802bbc5e5b8b0962db6fbb7e8dbadd738b217c19.nq.gz
    ├── 8044211b251338e7143254e79b15057e5d19005e.nq.gz
    ├── 809f767781b69f3f3897933c5671fdf10ef2338e.nq.gz
    ├── 866c2bb83e3599a22a2b15290ba5565e678800bc.nq.gz
    ├── 887a80efdd77460e7130b0a38a7806363e239b89.nq.gz
    ├── 88daff50eeb373cc64c52de03a98b8e9433e8108.nq.gz
    ├── 8b8731f79fdaed060cd87112186468fad5e6ee63.nq.gz
    ├── 8daf5bf809b5bee86e306e814dc2a2dd90b03554.nq.gz
    ├── 901492e81bb6a87e4de1d24ff71c7467d437bc8e.nq.gz
    ├── 90c8ab19a5f30908d596756bdf26ff203a751c86.nq.gz
    ├── 928963097120af709dff181e37280558f5a00ef7.nq.gz
    ├── 98d95a365055a7dbbcefc02a79946f07b596f46e.nq.gz
    ├── 99710987f605f7216b09dc37a8dd6c6115f559a7.nq.gz
    ├── 998c1dc87f37be9ccec66c82eb747e2b4633958e.nq.gz
    ├── 998c591eed98415bebafb48fc768a8a891ab3194.nq.gz
    ├── 99a09232383301d20730e1d1ceec6cbcee456ddf.nq.gz
    ├── 9c0f0d6972abb2993cba46c77fad8bfea8c018d4.nq.gz
    ├── 9c52760b6d60f443741d7180e320c4847311f45f.nq.gz
    ├── 9e97efdbb09d74cf6a03ec225e42bf4dfc56c802.nq.gz
    ├── a0d2ac33e67d5e969d7271f1b7d0eb0438e0c321.nq.gz
    ├── a2de341e9464fb27125e52ae225b2953035200ad.nq.gz
    ├── a3b6215b9e1f9971f37a4805bdd8c5b169d5708c.nq.gz
    ├── a4915977c60ba04e34073b662915e5ca018bc04e.nq.gz
    ├── a4e2cfa9aad81581d2f53f087dd771b7f3c46ce5.nq.gz
    ├── a6146659483ec5cf1a671865c8cc42a58c6c245a.nq.gz
    ├── a865ddaae416f6a14c47427bde48b01162d3a0ee.nq.gz
    ├── a99fe73e3b9716cff540214c1efbcdd49b7087ba.nq.gz
    ├── aaaab2aeebe205c9676ed0c2ceda595c5a1b7954.nq.gz
    ├── aae2e1ca388f2d6074f0b542de9b3ec51db06222.nq.gz
    ├── abad37df4c0f27fcc0e9126ef8a318421748cf6f.nq.gz
    ├── ac9fbabe061c7f3f03e2550daca228b2b426a30d.nq.gz
    ├── ada78d727ce14a27485b790792149c26bed6560c.nq.gz
    ├── af32f18366a3f7c2a7fbec1a6960e84916cc3588.nq.gz
    ├── b09dd491450c48e4cc4d27d01b544d2bb4471acb.nq.gz
    ├── b37cacc78681db9de561860267eae7dcdd79529a.nq.gz
    ├── b4e13b152135c1fbc01cbb9741f1b1e66d83c2f4.nq.gz
    ├── b5bdcbd0b08086150ae47005359b82cee4735c94.nq.gz
    ├── b5fc98fe8f154546a5c2cd4433e62c8cb34c3645.nq.gz
    ├── b602b74e606cc2d3b880ec12dc0f083265c6e48d.nq.gz
    ├── b78313e50188acb1c9c596add8a759e6a716f118.nq.gz
    ├── b8051666ac72f8ebc1f3af0034e9164f8202ebe5.nq.gz
    ├── b9417260fec088d0418cb32b7e92e392ce051b15.nq.gz
    ├── bab5e8304135416a4bfb12f8adc9edb645749629.nq.gz
    ├── bb32eb680951edf19da67ecb5f27f58711d0497a.nq.gz
    ├── bb3597635240fa1a4b89445b85d6fb58cb481522.nq.gz
    ├── bbe2b4c81ceab7bd36b47af58dc676f8840269a4.nq.gz
    ├── bcef7da59bef61db8000c54c7bb64135caa32bf3.nq.gz
    ├── bde0f7ed205bf7f5e2f3c8e99b0d6f3715740d5a.nq.gz
    ├── bdfc458612d63c0739fc12dbfd8b95f1199bf9f5.nq.gz
    ├── bf51b3233061d022bc513aaf653b9a175b79525d.nq.gz
    ├── c04135d7549b0a9d3da21f797a56bc1a5fcf0dbe.nq.gz
    ├── c133087427d17f9b7e6d31326da4b998b6a10b15.nq.gz
    ├── c20be6a90932ededa875921f3529f227ee81613e.nq.gz
    ├── c3818d4f5d52600b1a7b7c73d2eabcfb978b92db.nq.gz
    ├── c3ce4e8c7282a665bcbe0c65427087007e9c7df8.nq.gz
    ├── c512d6056016c2ffa5793f4acc15e27a7e3857e3.nq.gz
    ├── c5e563ce0e54ad991f0452789c220764b4cb42ea.nq.gz
    ├── c70b016cfc04eebffc6e811fa3684274089f0ff1.nq.gz
    ├── c712d2595247bf32129c8609dcf822e238412a20.nq.gz
    ├── c726b75a60f09508ac9aa6ac6268c020f4069e74.nq.gz
    ├── c981e6f32f852f6d0da5b27565d54ad9436f864a.nq.gz
    ├── c9dcf205c7599baad84a79c0f7137bf3865783c5.nq.gz
    ├── c9ddfe93baa365d0ff484835449c99bef7e96e48.nq.gz
    ├── caf4c2ecdcac4db4e03edebbc39fe5f8aeff7035.nq.gz
    ├── cdf52756c0377bb4487f4f1c31eff0748626c546.nq.gz
    ├── d07adf5443b1c6ad08c78d8b2d46db7d0db7989f.nq.gz
    ├── d0be216896ffe5a1f4fbda5f3c3785b137b3c54b.nq.gz
    ├── d26962ef60a6f8f1387029fe7e5a10910bacb912.nq.gz
    └── d304831327dbacad51e3acc811783032c6d1b816.nq.gz

7 directories, 200 files
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

[ansible-community/collection_bot](https://github.com/ansible-community/collection_bot)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
