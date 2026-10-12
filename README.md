# Repolex Knowledge Graph of strawberry-graphql/strawberry-django

RDF knowledge graph data for [strawberry-graphql/strawberry-django](https://github.com/strawberry-graphql/strawberry-django), parsed by [repolex](https://repolex.ai).

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
rlex download strawberry-graphql/strawberry-django
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd3f6502fce162effca1eafc0749c52ca0bae508
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fd3f6502fce162effca1eafc0749c52ca0bae508
│           └── chunk-001.nq.gz
└── blob
    ├── 00a8de699a4b482618cd18a5b1d898af628e666c.nq.gz
    ├── 0129044c56c4cb61da0f211b88f9b52bff1625dd.nq.gz
    ├── 0301d089835c3595477d6923ed06805236fc1ce8.nq.gz
    ├── 052cdd70d0a71d008b5fc8d7586cec3046f67d72.nq.gz
    ├── 078c29c495bcdd169a9bcc4d9ef0ede7e7f47d60.nq.gz
    ├── 0943c9879ad35664f1d5e109c176f56272706bfd.nq.gz
    ├── 09d4839aa0f6905be02546ad4b4d6dd2161601b5.nq.gz
    ├── 0c11965639a73ff56219d10d61627784f2ea2dc0.nq.gz
    ├── 0d34fa6710f04a116576c8b685bc2718d0fe679a.nq.gz
    ├── 0e1648f282d964e2cd93c1590f3e3b31e6d6889e.nq.gz
    ├── 0f0af37780fc4304ab6df6f157adcfe8c43656fc.nq.gz
    ├── 1074dcb72d48573d49676075cb850f511f9f8766.nq.gz
    ├── 1181e3a334de50d70939cbb1f1af5415f3446365.nq.gz
    ├── 12ed0f42e70d9be35f910e4f857ec66c364b81f4.nq.gz
    ├── 136eec249f82a7714217952081b26f6af3bfaa9b.nq.gz
    ├── 14bc706e381f6a125cfb3f4474af57a634704f45.nq.gz
    ├── 1536934161c87954073152c12a6441dc41388214.nq.gz
    ├── 15482a68b1d9868bea6f4fa630ca827ba5f7da4c.nq.gz
    ├── 1629aedb839a533495e7b69ba812f2a400b9758d.nq.gz
    ├── 16bb1869c01a10ef964f2fd45be7a084baae0a14.nq.gz
    ├── 16c1eec966fc883aa1d6020f7c2debc8421718c4.nq.gz
    ├── 1706b9a07a231053d796e0881d64e5265e24e4e2.nq.gz
    ├── 17da0378f81ef2ee679857e25205ab54451ef8d6.nq.gz
    ├── 19393470c5d5fccb0e803a47897c02aa8996d4d3.nq.gz
    ├── 1a16e7fe15c853d5785983425d63e44703ef7f2a.nq.gz
    ├── 1b6abd2df8b4bd5bc547a15aa566c03c64c9bc56.nq.gz
    ├── 1beffcca559da041307e07d6ca342a521705e610.nq.gz
    ├── 1cb3f5e8a04c963a0fb24c74a817ed6e9fe463d8.nq.gz
    ├── 1df604d8dda5f96df7840eeeb7e9f3b8f9fd3b6e.nq.gz
    ├── 1e6848b50c9d722d6b5754a72bdfb34074d5dfc3.nq.gz
    ├── 220ac954ae0bb0a3ae0c991e25545064cd578922.nq.gz
    ├── 22abb1426dbd1c727a39ad83cf576f91ce7a68e4.nq.gz
    ├── 22fc76e14d5968b59f282962fc6b99e79d1e5941.nq.gz
    ├── 230a3132a629e7cd7f3865bc24ed1e7968bdecd7.nq.gz
    ├── 2316c464a53a0c56e71036c37c791832a643bd4e.nq.gz
    ├── 234a21ad0dc5b4322f1377b6b517706846364798.nq.gz
    ├── 259968dd582eec8ff9771a9cd163969227895900.nq.gz
    ├── 25c1e94783a1ac447a41a15fc820aa658d755344.nq.gz
    ├── 26aba93dab9bb410fe7b0cfc8caaf78af2ab3a21.nq.gz
    ├── 270cd8f04cbbaf8f98accd12221bcda802d1fb5c.nq.gz
    ├── 27c666a0fed361e04dfbff59eff6954dff4f5b90.nq.gz
    ├── 2aa123ab7d2e79e472ea20ee8d83ff0ff66c266f.nq.gz
    ├── 2ae6ad1d0d3ac87efb167020df35966579512bee.nq.gz
    ├── 2e50091b2be278d38ac0f35cc4074f3792ec3a67.nq.gz
    ├── 2f7428d3755c81265ffd01f62ee96079f1973b80.nq.gz
    ├── 2fe0879f42ac42579654fc7a08665598b5d637e7.nq.gz
    ├── 3021fac24a2474c601c8a2e8c5a7ef97fbf12372.nq.gz
    ├── 328cb6fdf2d2623217965e25f6d83730543f2b63.nq.gz
    ├── 349bda0295cdc9d09f4f32627108ad6c36010953.nq.gz
    ├── 351bdd920f516eb44d40ea19f1e646072a0ef206.nq.gz
    ├── 355a7758ecd17f32cdde3c805d58909a944e64f6.nq.gz
    ├── 385b345a2be565f2b8a652d131d10645cb869930.nq.gz
    ├── 398596511b0bf7da364c951c2aed8e933ad7452c.nq.gz
    ├── 3995407fd52a93b0963652a9e8a6c7a40f668436.nq.gz
    ├── 3a3a409c614adcd562f720a7739aff42dd59d02e.nq.gz
    ├── 3a7c06128d2e3663801be0b0608d4e38fcb17474.nq.gz
    ├── 3ae6eeb7fce08fa7a2f1be2290b11894ceecefb5.nq.gz
    ├── 3b6c4f4e729d9b4cefcf815577bd55d0313e36db.nq.gz
    ├── 3d9ac15194271e39d74430daac73d25aba43bfa9.nq.gz
    ├── 3eae80e489cfda92173305e9da8979b0b7122140.nq.gz
    ├── 3f99cb9d6aea6caa6f00edfe45cc433825015a55.nq.gz
    ├── 3fd50bc200528ef923dfc044314320ff28f79ea2.nq.gz
    ├── 4051dfc355e68115ce8c7735f2f09cf8fbdc8314.nq.gz
    ├── 409cb68193cc4da095354c2f99bc880a8526ac5b.nq.gz
    ├── 40dd6755698b4316cb7f71bec15ec0e374bbda50.nq.gz
    ├── 428312674c3c8e025a72c72c9891cf4b805fff82.nq.gz
    ├── 437127776b33804c6396f68d799dcd2291e6ad6e.nq.gz
    ├── 4476c14fa6727c94da5a3e5c803aba93cefc9c59.nq.gz
    ├── 48157c5f0527cf8eeac4432eab9b9659f730be74.nq.gz
    ├── 48615a81c852adae2408366fbaa89be2a26defa0.nq.gz
    ├── 49f638b5d186b0afed2bdd15d7220eff98fea053.nq.gz
    ├── 4cd1b126ce37609f5c7ded45586dd24a17dd3682.nq.gz
    ├── 4d223324bcc0d97b411acb1d60c683d52c52dc24.nq.gz
    ├── 4da4713b13253b50d09e4afb5a84c75f5ffb5fa6.nq.gz
    ├── 4db124accbfcf823fa49ceff5923882c94bd4e82.nq.gz
    ├── 4e93f458c8c850ea0f9d710e2be77d10f252b53b.nq.gz
    ├── 4ee7456cff9cb26062a4306c44fed9305cd77386.nq.gz
    ├── 4fc4473850a5d6ad97d337dfd7bee7ef0dcee185.nq.gz
    ├── 4fdaf780221239cf420f622b07d0500616a10afa.nq.gz
    ├── 4ff998b4b61ce7c701feb956c9631ee83a30d77c.nq.gz
    ├── 50736d950cf669d7f36b135f5e471616ca946276.nq.gz
    ├── 51c21c4f039b49adc78ba8315f2b8cf313fd949d.nq.gz
    ├── 51d491cf6ca87d1af35d3e0c0bf6ae14e4569160.nq.gz
    ├── 5261af00caf64ac33c070cea6dc02bc72e46cc42.nq.gz
    ├── 53369367b848b4b0101afa976c671c96c89cf8f7.nq.gz
    ├── 550eb611773c0e20fdac754e9b6f68dc00bb5761.nq.gz
    ├── 55988b02a7a2dcd25eb58be0a2de30daa26d9ff8.nq.gz
    ├── 5758dddfce297d417c1f6fa64c1e972d431f0fae.nq.gz
    ├── 578463dc43c316d9cb919214fb6a44a00503ec3c.nq.gz
    ├── 58579611bc33b0aa2c505d072a136e22f235a0ce.nq.gz
    ├── 58a6716eb9a61db39e7acb6b9a218038627813e5.nq.gz
    ├── 59719bc18261d11a76dbeb75ee8d5950a763616b.nq.gz
    ├── 59feb5da9cb872edd81b5f637ffed52aba615c2c.nq.gz
    ├── 5bc34cc2bdac4f7559ceecc01a30ad5161272393.nq.gz
    ├── 5d36262e181370a78f73d3c8c64570f437dbdde9.nq.gz
    ├── 5e2ab7661602c8f6f06eb3a8ec324523b41e236c.nq.gz
    ├── 5e7e72449a16c6e57dc494b48fd89d3a4ba61474.nq.gz
    ├── 5f5fb4ad5ad4a17df0cd75a306f2a862a6acf0d6.nq.gz
    ├── 5ff4d875c8e27185f1acad32ad1da6eab72ffd60.nq.gz
    ├── 600e071a78a8fa28872eea8220a37c6f940e4e2b.nq.gz
    ├── 6147210a66da113ba020dae998dc6ac0560dccd6.nq.gz
    ├── 6206be1e965bb5f8d120ba0c376859c3e8667da4.nq.gz
    ├── 62dec41340d8dcb81a49ae7e152799c0b389e596.nq.gz
    ├── 636c1df4f603f25521bfa309d84e9a383440aae8.nq.gz
    ├── 67e71dbf31eed9d739b976d730fd1cf2266e0694.nq.gz
    ├── 68878335f2f28d2adf4a36a9d62d924cad9f1529.nq.gz
    ├── 68cffabe97debba94d72306386edf5fa0819f98a.nq.gz
    ├── 68d63e288c32be62d60e0645c867528094bff8e6.nq.gz
    ├── 69c153976c155c2b9784a510d3ec69d520a4ca3e.nq.gz
    ├── 69cbf345bd43d996f2a652a8bc081f17b495b33f.nq.gz
    ├── 6cd8fa2bc4e6687eeceef9d30ef79a5b1e73869e.nq.gz
    ├── 6d655264436d9e9d66cde376cccd1e8ef07437b9.nq.gz
    ├── 6d6b13786250750ed7c1b704db7cb61414725bc7.nq.gz
    ├── 702b2ee71e1acd12e1a094908560b3e71fb8a2e8.nq.gz
    ├── 731d27c51ba995fb1a2b34c6cabf58e6745c22dd.nq.gz
    ├── 745ba8969c9e000c1046b7aa1d211033078a054b.nq.gz
    ├── 74aec116e61aab20f235f7d6ebdf07d38c460994.nq.gz
    ├── 756cdc2d438ebc28b0d9e6e20a9ac7c58927309a.nq.gz
    ├── 761d0fa4256958572a2ae0721b324683491e567b.nq.gz
    ├── 781a767c182162d7e71b85d7f8b23c5967dda373.nq.gz
    ├── 7a92a1290d2bde7b1683da9f1e69025bd8a98781.nq.gz
    ├── 7d30a9b8ea1ecc36f7f55c0a6e1cc3fac705e3ca.nq.gz
    ├── 7db8c300cd91690949550e63e9213d20c9bc998a.nq.gz
    ├── 7efca968c39d2d10e21979abe7123c80fcb883ce.nq.gz
    ├── 8043742e08d762e43485d645b6bd076ee935595c.nq.gz
    ├── 82e2c702a42e3c016cbd6103454c163dda2c9844.nq.gz
    ├── 82ffe7d6fec7fcd4b2d518ec753ce6879c021129.nq.gz
    ├── 847c45c3b9f79d2bfb940cb323c469ca06a408de.nq.gz
    ├── 84f1c0c39f07b027c56a5c68be6a810496ef38e0.nq.gz
    ├── 855bfdd91c00959ddb2653e7850c5326415f4985.nq.gz
    ├── 86036bb24fdede15fd5f1f7114efdd5c446325b7.nq.gz
    ├── 86b3ceee98e491640a0f74ca27d467ffca4ff5f8.nq.gz
    ├── 885543f5b3f1f29d9324f63bd80ad9214381dc1d.nq.gz
    ├── 89a303661f3de70dd12a1ccd20a91295d3727c38.nq.gz
    ├── 89b2856ba26f620ee0e867f53b19e538452baf7d.nq.gz
    ├── 8a2f0dfcfccc3d817bdce9a1cebbe2b20171d418.nq.gz
    ├── 8c24edb56b8c27e36e59bad9b9d8cdf397396e09.nq.gz
    ├── 8c657c27b501faf79051ddc80ebcf1770c98f287.nq.gz
    ├── 8d602f13f0b4470e0e0a0a7731445157a52a7b94.nq.gz
    ├── 8f2a7d66c7263dd60eb79ea8f67ca872dd613084.nq.gz
    ├── 8fbc3e90033087c2304a331759221d4527fb77ee.nq.gz
    ├── 8fe234a05c2170a1f2cceea133242fbf61d29f94.nq.gz
    ├── 91db7133d776ec968201356a3094f3acaf9d1f3a.nq.gz
    ├── 9245110fd4bbe46aaab7e72be93695e5b3ab24e0.nq.gz
    ├── 92773407709bf8f2d216e6b170e54eb31de0f873.nq.gz
    ├── 92b4cbce9891cf423ad5b5c85464ea76cd743811.nq.gz
    ├── 952d95bf9663a9595c5f91d8b26e4d33503cc88d.nq.gz
    ├── 95773d1371a8a391584347bd9dc377da60ad2c37.nq.gz
    ├── 95f56a50d6ecaa8757b17ea9d6807d2f492e4f3a.nq.gz
    ├── 96aa90c528719a4057df01a8044a830bcedf0613.nq.gz
    ├── 972e5c4835ced81dfc451a010374e1605b0a39d2.nq.gz
    ├── 974d64f71d6faf47802bf3a797050229713ddde3.nq.gz
    ├── 979017173ac26ca3b6f38c39f161750bc447af60.nq.gz
    ├── 9acfee188a89a522d2185bc4cde95472b150dafa.nq.gz
    ├── 9af7e228f2a337887cc234dbc577134c0cadba09.nq.gz
    ├── 9b6a77f8fef38c98a75370fb67939a7b7b1c3952.nq.gz
    ├── 9bb3062c1b0d2bf4365ed041587db0f99892044b.nq.gz
    ├── 9f5ab08e353ff08cb1b0248c6b0d9f3c84813ab6.nq.gz
    ├── 9fb355f9704fd1a05b00faeb3745b5f2906e0b4f.nq.gz
    ├── a0a8c0264cc0d0e00b7d50568ececac05ae0360d.nq.gz
    ├── a27add14922fe611f197d56cf94f602dd9f8075c.nq.gz
    ├── a32dd3f04bb8b8989870eb426cd36c747c51b5e8.nq.gz
    ├── a5c41c80ef9270d7e603c64253749f219056af90.nq.gz
    ├── a679566a912bcde7d20bd8f43b7af6b699b0000a.nq.gz
    ├── a7fded1c98076fd068b0d08ab0cbd4ca15955771.nq.gz
    ├── aa31b34958c8918331a57de19153f0bf53b281c5.nq.gz
    ├── acc44ec1c8363cad6110167b6374bc98f6cde0f3.nq.gz
    ├── adf780308b2b3f73ad329e3a9fd714d59af60b41.nq.gz
    ├── af3d1ceb3d515df6152159fe7d5f47df4b0a8d16.nq.gz
    ├── b1f53c83a881ddb8c41230ce6224cd9c5f27016d.nq.gz
    ├── b2a14acdbc81f79cb070b670c633ce10926d522a.nq.gz
    ├── b424f754e32520cd79eb81a7b790d30941570838.nq.gz
    ├── b685687b1be2b24b09222ad3f4cdf0e1b08f0f24.nq.gz
    ├── b6a61cc146d04b49b530b8dc80f9aced979959a0.nq.gz
    ├── b76561b1b1de6e3ecee1ae4e4f69a96cc0f434a5.nq.gz
    ├── b84b5762909dc44de7f5da5255c986a5defa3784.nq.gz
    ├── b89c9794be34d89ae635a6a691e2e6b6a4f49d9e.nq.gz
    ├── b957235e141e6f57520ff1192bc5b46dc85e2d5d.nq.gz
    ├── ba1e19d95496e96288dc89111814c0b5a7714719.nq.gz
    ├── ba20fca09db5f6304d3ac3fa04559b8170e9d6c9.nq.gz
    ├── baeebfeb7352535dac1599db56ae11b10cbbb59d.nq.gz
    ├── bb03a603110da5a3487666aa03762baa0b318c89.nq.gz
    ├── bb84e9fb74b3675196a434c62779c05e974909bc.nq.gz
    ├── bc2557e0bf804ce2b4fb2379a81363ec6f62c95e.nq.gz
    ├── bcdf4a0b544cf6fce1ab7639645e452ccc47243b.nq.gz
    ├── be10848a31f9774783fb4708136c95990a493983.nq.gz
    ├── be8a6b1c2125a129c1c93836fa7ab68eaea17a17.nq.gz
    ├── bf45313c2916a2856c96c881082d58f45cca520b.nq.gz
    ├── bf699b97447ac07e8e4cd8f737751df73681b1a4.nq.gz
    ├── c162acbf98371d8d4c0868dd920b4d25aaa42c92.nq.gz
    ├── c1a03d1dcb1605fed1e818267e5207fb4731e96f.nq.gz
    ├── c1c7459b24efc28d23de2ec0aa1a5e44c2184ee5.nq.gz
    ├── c2170b7399678ed7129a8539a98285b2b6972ad5.nq.gz
    ├── c568fb972fabc0a3cd7a498d6331744730d64c64.nq.gz
    ├── c6938226932f0977d49550ffc4eb1d61d63039f6.nq.gz
    ├── c6afd27444d0f59e97ab858db5543743f8553cca.nq.gz
    ├── c80dbf0cfaa54967fa7f84e7f6b86d98cc0cf375.nq.gz
    └── c937e0e2699e6b687ef2759144545058e8ca7149.nq.gz

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

[strawberry-graphql/strawberry-django](https://github.com/strawberry-graphql/strawberry-django)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
