# Repolex Knowledge Graph of pydantic/monty

RDF knowledge graph data for [pydantic/monty](https://github.com/pydantic/monty), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/monty
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c6e072c41f492981dab3181cf215745c81b52df2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c6e072c41f492981dab3181cf215745c81b52df2
│           └── chunk-001.nq.gz
└── blob
    ├── 008cba579e99dd6ff11b03a36f05dae1188f7523.nq.gz
    ├── 00abe580d3253c0f5cd362f95db0943f9ead7bd9.nq.gz
    ├── 00daf7759d7e91c60c5669b85e2908a895f8aed8.nq.gz
    ├── 0154b8fb5f86bb8fbe4aa7a36018340bc874e9d4.nq.gz
    ├── 017674543b00574712c2c1d20fe17558118ac520.nq.gz
    ├── 01fdc9cb4c2d5bab2e0a84da98332bb602810ea5.nq.gz
    ├── 0266dd57b4b85c312ca276335c8144a952d3a0a5.nq.gz
    ├── 038b27c83ab29d8b060b65d4b9bf864fa8440dcb.nq.gz
    ├── 03d05ee15dbb2141a935ae6b47179f792f1cf6bb.nq.gz
    ├── 041d77d39e5a5f8318b9ebb1a7e44cc054dc321f.nq.gz
    ├── 0433fed2a3e21e0b91354266b9e26e435aa944c7.nq.gz
    ├── 04a119ca92731f419e21f54a66ac7fcb6172e719.nq.gz
    ├── 04b87bfe68aec5e14657aedca8561c9c7015ce3e.nq.gz
    ├── 04e3ad6dcdf81412fab2485e2b1278d5187370e0.nq.gz
    ├── 052ed8cd900cc11ba45585765db6c1223364c8ba.nq.gz
    ├── 0531e75d4c3095b19301cb35a071feddb3ba6575.nq.gz
    ├── 057635092efa7cd50a60ea1d8d46eb527b94447d.nq.gz
    ├── 060a379d95c8966b7c3286aec6a17e20989f9c30.nq.gz
    ├── 061e36fbfcb7015d5358fc31f4e55f356de2e834.nq.gz
    ├── 0661f4ba1ff71cc27cee05db9652210cd35ffff5.nq.gz
    ├── 06908cb34148cf6f3c3c4394e1aa0d1c3ab86858.nq.gz
    ├── 06f9bc0f787403f19e980826787afdacde443db2.nq.gz
    ├── 070064df6479e68e2c9de4820d03945dd4b31dc4.nq.gz
    ├── 08c622bb998f8df1df21a6bb7cbb10ca9e64c434.nq.gz
    ├── 090643e6c43d40f666d5b1b568352ca55c4d3814.nq.gz
    ├── 0975e2037bba6d59d79f0fe6f33c7e1a4f3d9cd9.nq.gz
    ├── 0985833b1e170ed5fb9bd016903c2cbafbef1325.nq.gz
    ├── 0991924b2637f72816b8dd376ebe7dc071afc8f9.nq.gz
    ├── 0adb6ff69e083b7737a913c365a27cc3c0278425.nq.gz
    ├── 0b25634820250cf90c5a85ff8df5aa5219acde8c.nq.gz
    ├── 0b77189ceee4b01a0562df7b63a2695feebd106f.nq.gz
    ├── 0b8ddd1641556551da32d0883bb8516df1620061.nq.gz
    ├── 0bebf08f0e57400d655ccd41ae87389bfbc1bacf.nq.gz
    ├── 0c0ab324d8350b5d9169ff0e72fb4c2b31be2bea.nq.gz
    ├── 0ca91f3f2d85d85136ab3b36e3c01226313f626b.nq.gz
    ├── 0cd6bf8ec3b68a93702b0bf439f06cf21d86731e.nq.gz
    ├── 0cdaf0af88f03697ef195ba7538c4b6a60c1d8ac.nq.gz
    ├── 0e914fddc1dc43472e33b18d33a7119e25949be0.nq.gz
    ├── 0eb34b6a0a71247da765bcde7692433b643bd41d.nq.gz
    ├── 0f3ce5b48909be4f2ac92fbf8dbe1aa165b0b2d9.nq.gz
    ├── 0f964caf2d0b1f100659f2b12f8f52af8c99f1ee.nq.gz
    ├── 0faad333d67a9f7e5d63cedecff679acf8d81006.nq.gz
    ├── 0fab5e60f038a68792ed0ab272f6c3794b124c92.nq.gz
    ├── 0fd8b718f44f107464cb1c59ef7bc82a34420f6d.nq.gz
    ├── 0fe0e28ee9bf5c40353378b7b3416340e085596e.nq.gz
    ├── 0ffcafdb38c69b9fe234e37cf0f606c62a22ff5b.nq.gz
    ├── 1138ae07ae0b38ef26b738f8af8f5d5853875a63.nq.gz
    ├── 11bf2d545f1425e9436d4521f54e3a6a737fbba6.nq.gz
    ├── 131887fa1bf35c25963f56c42ff0caf32e746ad6.nq.gz
    ├── 13290a64876f5dba157d2d934f9fc81b1bc759b4.nq.gz
    ├── 132dea742bfb7b0f6fb1449859b40b519970edf0.nq.gz
    ├── 13fe81cfa3dfd983847f7b9d36b5c56cb523511d.nq.gz
    ├── 14157bebe02c1ddc77ae7e4a78fa7148ce08d62f.nq.gz
    ├── 14e1367f9f5a168cf133af546769abe6f3bcb3dc.nq.gz
    ├── 1595b3637d3c268d5548e2c2f5e9628cd3ce2f2f.nq.gz
    ├── 15977ab265016b7cdae072e8b59327bb7d44ebfe.nq.gz
    ├── 15f2a4a61a09fbd7764eb73b49ef56a25f2c4bfa.nq.gz
    ├── 16387af0f6e8957907c3167568267d3198e296df.nq.gz
    ├── 1699e5c464576a4a9bb6eede835693c0c97f669d.nq.gz
    ├── 16da37d98f1d4db58f27a753b5d831ff346b6059.nq.gz
    ├── 17616bcaf9dbe650b5e8a78207953359dc5ead6c.nq.gz
    ├── 17d17c792015364382fe9305d97269a3b7adc5fd.nq.gz
    ├── 17f1b68ea07ad9f440383993db914b730157114a.nq.gz
    ├── 183d5675998e5116fe846c49483fc4908029a7c0.nq.gz
    ├── 185aac65e0309bd5e0b35d979975f15e42a8b732.nq.gz
    ├── 18d17fbd7ac94de05c1b7e1a368a1a27791a6518.nq.gz
    ├── 1931123a1abeb1bea9a2fa9497fec445df694be8.nq.gz
    ├── 19c4304f8b5d1ff34ff60a2733ac2daf605be763.nq.gz
    ├── 1a07a67d3c183883932f02f4746f641e305dfd77.nq.gz
    ├── 1af3586f9cf28ebb060871c037932617d7c53302.nq.gz
    ├── 1b51af38f3680392f42f0d72418c1b22b415e11b.nq.gz
    ├── 1c3aca436ac6185598cc2b8b2a00bd23f9cf7e60.nq.gz
    ├── 1d5395e815ea818af90bd2b84be3353aa420f98d.nq.gz
    ├── 1e10c02fd3a69763f27b3b298648abbef0a0532d.nq.gz
    ├── 1ec07d59f697624c2b179bb4035d7bc97505098a.nq.gz
    ├── 20346ca8c83ad74549251bbc3fbb19c28e2aed1d.nq.gz
    ├── 206de9d2bc9a5cc73625575c59a8956ace7ef7c0.nq.gz
    ├── 20b6ebe8ab907ccb7fd439fcfa17fb96125c986f.nq.gz
    ├── 214c19d8129055782c10b4e81ebe00604c4a761b.nq.gz
    ├── 21af4ce332c7e386fa5b0a1d181f90e7c7cd98a7.nq.gz
    ├── 2217106f0275896e35bfffd4c1e3fab3dd72dbca.nq.gz
    ├── 25e3442eaaf0378d148737236a200932fc348db0.nq.gz
    ├── 25fdb6fe52b8d5af53fb155f017f918a391c737f.nq.gz
    ├── 2612086716fb87e640703394b4db243f43d997ee.nq.gz
    ├── 265ae18aa78e2b1e3593cc89c740496bbb03bad3.nq.gz
    ├── 26622062d83b35cc050789cb455720d2d2cfaed7.nq.gz
    ├── 2733a7d0c4e08922e5b4cfdcc7049c38c4c2e27c.nq.gz
    ├── 29b852528764c27197f19e968eee0c16cf17ed2c.nq.gz
    ├── 2a30ffd8064ba3047659422ca7557f7201589512.nq.gz
    ├── 2a52284c790986fe6baa36a5accee472e5fd8b1c.nq.gz
    ├── 2a925134a53b969ac61f7272749b303058a8d21e.nq.gz
    ├── 2ada3e2bb56d2e3672fd5cc34d7f3fd1fe7068e2.nq.gz
    ├── 2b7a412b8fa0fb7e985b0793321bd4e698f2b6cd.nq.gz
    ├── 2b7f75886925696569e24c3021e31502d633e8da.nq.gz
    ├── 2bcadfb09b79cab91fc12941657b11fb94deb119.nq.gz
    ├── 2bd06381d0cdbf2ae1a760af83ae96f7670009f1.nq.gz
    ├── 2bdeae0af2c25ab376bb637da9bf6a99fb6f832f.nq.gz
    ├── 2bf2a7e76d3ce4e48af723a19287e50239c48cdc.nq.gz
    ├── 2c9294319861ae01bc6a85164ae1bce8b3c4973e.nq.gz
    ├── 2cf8aae01d417da81e169fcc36eb3109155188bf.nq.gz
    ├── 2d0696136634ee74b5b062c295634998a4498bd1.nq.gz
    ├── 2d21fd2f2c36a91f00e00e4557fa8ebd32db5161.nq.gz
    ├── 2f85295cb81f472940e27900ead5774b8850f24c.nq.gz
    ├── 311445c2375cf9901b19f5ff4bb860d504b8e9f6.nq.gz
    ├── 31b789d2ddab7257c88e4319db471726763dabcf.nq.gz
    ├── 31e1df2f42da0cbc570320a5d0905a58a9a4b948.nq.gz
    ├── 32480f2fb5e129caa706652a7088328829e43f8e.nq.gz
    ├── 33045c655a73bfce01231fdaa5124925d84bee86.nq.gz
    ├── 3311e82d82dbaf224decc2fc24ca91bd28589a66.nq.gz
    ├── 332da483360d3a1976475808a7dc67000f9598bc.nq.gz
    ├── 333189130e76995f13a227be3896a1a3076ae689.nq.gz
    ├── 335a777e1c7cab799715ac9b5e53ce34b8fb8640.nq.gz
    ├── 34766867eb5100cba0ccbe3bdb3a18757d24af3a.nq.gz
    ├── 347929daf0048c5f93bf7e8567808493e68ef0f0.nq.gz
    ├── 3540b5aaea1046d3e5982ae3cac9c919e3388d61.nq.gz
    ├── 35acd90dc46cdbd9dd7e8b72c2dc8d21132e3c8b.nq.gz
    ├── 36af289d89cab05bef36abcd726c9dbe054c471b.nq.gz
    ├── 37a23e9a6bda8aebee35b8855c66c14b50bae1e2.nq.gz
    ├── 381a7e4395ddc214dc6bb531887c4b2e52503a65.nq.gz
    ├── 3823de36cb4a07ab5233bdae5e6bfd8357d3fbda.nq.gz
    ├── 385f721d802575dee4497db9f45c504546abf3f6.nq.gz
    ├── 389429aee5957489162d4a638e9b1e809af310fe.nq.gz
    ├── 38a001fa12149b73e711d9806d3f503dff7398b0.nq.gz
    ├── 39814b91b4b7fce7383cdc120c220393d2dc4b38.nq.gz
    ├── 39e7a0d3c45ecebd1c5afbd83d5b7749937f274c.nq.gz
    ├── 39eae97d89fb3e9e1f691ef781bb0d6d4ed12d04.nq.gz
    ├── 3ae8abfbca7641a9fa5b427ae3fc838f12028b87.nq.gz
    ├── 3cf071e4b5a11fcdf6607b3e72fe8ec8398dae48.nq.gz
    ├── 3efdc4b2f1fd986b0de8458d50c7a966a91d8a4b.nq.gz
    ├── 3f783a0dce0416c02c8cbbbde3caf1351e068eaa.nq.gz
    ├── 3f9af4ba4051bc85883a8a8fe2aed9b9fb90e2a6.nq.gz
    ├── 3fb54069fe56c8a62ba92a61025dca01b07c3e69.nq.gz
    ├── 400c5355e660049d85cea3d72c59b6431d0ef454.nq.gz
    ├── 404dffa1d226dde1ddfae87e75619b23867191f9.nq.gz
    ├── 405fed2e21afeb6128ad977ea804a79bb930e128.nq.gz
    ├── 40c486b36c1a233f783600670984d92028d9de8f.nq.gz
    ├── 410bb9583a757e9bc45cfe377cf77f5d45e34a81.nq.gz
    ├── 416c46d736d8b4921d8dbe4ef29e2f237395f8a7.nq.gz
    ├── 41a4bf0a2d51704de89219c80df7ab6ed7f7edb6.nq.gz
    ├── 41ba6e703beef598c2647e55240130eedff2cfb7.nq.gz
    ├── 41d5137bc546502e60954c331a74a0a6e37b9c83.nq.gz
    ├── 431beb442f04859d4b7efa5464060a20268bfa13.nq.gz
    ├── 433cbd74ea93f12a441d959352b730f582020e56.nq.gz
    ├── 433d0558659dff3cc5a16085a7003ae446e01842.nq.gz
    ├── 434c1369ff5a63b73c83775bdd8a7667809cc215.nq.gz
    ├── 43c8330031bad959f7abc10356d46a88925e550a.nq.gz
    ├── 46ba1c04f0c4595e72b45314d19022cc1d85b4de.nq.gz
    ├── 47221f05aa084f0fc81db56e887d3230e85b956d.nq.gz
    ├── 472aa6409e367e948f8b8a6667e6e84bc05d8a08.nq.gz
    ├── 478b07365638116972ed34fa5a180055c7f4cf41.nq.gz
    ├── 479a62a1c84eb31af0a9c71f87c6a3d482afc423.nq.gz
    ├── 4873a967d0c41090d559ed4ba958de88501059b9.nq.gz
    ├── 4ae57bc3e1fe774a157548c01d3b6e2df8beff27.nq.gz
    ├── 4c1a68a35ca959711c4dc2e1626c1f0ee35d3a8b.nq.gz
    ├── 4e95a34f8487f61f1518e4b1f5520d6fa2c8370a.nq.gz
    ├── 4f20e8e3f7a8e18e7a7d8777dba16210170e1b44.nq.gz
    ├── 500f93addccd1099f70f88b2e938515949b69cca.nq.gz
    ├── 504afef81fbadc8c0a072e1ac93f1376bca7f4a9.nq.gz
    ├── 5105f0c5a5c55d6d8dffa4bc3143f6213aa5c347.nq.gz
    ├── 51f8c582c7650beaf75c28f3e62d70b7660397eb.nq.gz
    ├── 526a900c0568bd26ec97bfaf3e800ca14618497e.nq.gz
    ├── 53a810bea759571e2b1c79ec0cb011124a5e59a5.nq.gz
    ├── 53c3b0f768c4439b983ba18be2fb82903801aaa9.nq.gz
    ├── 542479a8e66e8f21ccb7056c67307d83b165abb7.nq.gz
    ├── 544268dbd68e0dc3334dde689ad01b46d2c1896a.nq.gz
    ├── 545b3672e87f18e797a6e34d32fd34188ed9a9e6.nq.gz
    ├── 54771d4bea03db1135bc40f06791204a6fb2ff2e.nq.gz
    ├── 55a72f3af79fe25006e65182120d82f30b1ec020.nq.gz
    ├── 55da81e148e2bdf6c3711f9d04e62a0821bdca38.nq.gz
    ├── 560d8026b6939c46f28a438aec4b0c3a3d72994f.nq.gz
    ├── 5689dff00225ddc754b613edd20c30f989f05cd6.nq.gz
    ├── 56937fb0e0be26c85c87f758ed19a31e83bd8389.nq.gz
    ├── 56b4bd26f0a7b79418d074cb8200785fa6c6b85e.nq.gz
    ├── 5703a72d3fcc0d6659196a09f182d67ff1cfb96b.nq.gz
    ├── 571ff6ac0a0cf88125e1ca8bf236ac0a13bdfd54.nq.gz
    ├── 576e7c6b7139f970fe51ce1fa400392bfdb34d41.nq.gz
    ├── 577357f3b493b0ac9f4ee356a988bcd3eec3fccb.nq.gz
    ├── 57dcfd8484a96909ba56ed06292703aa4166e417.nq.gz
    ├── 57fcc525bc9e6ad02c543b01c41eeaaea5bd96ef.nq.gz
    ├── 586e79a7c5c96baf213e49b31507cf814479bce4.nq.gz
    ├── 588f11f6465e6c61a2da411e6cd7bf7ac1ef5af2.nq.gz
    ├── 58d2df3a6b1ff9ed21c25744dece6ee64f5ed0e7.nq.gz
    ├── 59410261f01a226de2224b1f5a2383634341c4ae.nq.gz
    ├── 597a7bc57b3057ec39c916e18de0c8baa8e344b9.nq.gz
    ├── 5bca0e799e9278ad06962895bb1404aa104d5dfc.nq.gz
    ├── 5c32029bf60b3fc2124cca9365bff63d36cc1558.nq.gz
    ├── 5d15f859b9e9ee87e87d1f9274a79860c8040e3d.nq.gz
    ├── 5e1be15a51be9307abbde77f7781849ec14d83ad.nq.gz
    ├── 5e2c94883081830ffe28663cff08f3f58f3aefde.nq.gz
    ├── 5e4aeb2e972c5c8d9f2ed1b989485a0eeb2645af.nq.gz
    ├── 5e5c54954bec44bf7fa3efd1b222800e59fa3688.nq.gz
    ├── 5e96bae7016361086220780313ebce18927e107c.nq.gz
    ├── 5ef7cd58ae62608ae504dd7ca96d28e9f56bfbf4.nq.gz
    ├── 608293e2dde873f06f41dc9fab5138c7290872f0.nq.gz
    ├── 618a991fa874615a4cf245708c72999b7f60e38d.nq.gz
    ├── 620b416ac4b5117ce2155a51e23bf06cdf22c589.nq.gz
    ├── 62216286b699dd30a0341f497cc2a59465f605de.nq.gz
    └── 624e2f001bfb48270887864af5557f6174a33b43.nq.gz

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

[pydantic/monty](https://github.com/pydantic/monty)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
