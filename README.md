# Repolex Knowledge Graph of milvus-io/pymilvus

RDF knowledge graph data for [milvus-io/pymilvus](https://github.com/milvus-io/pymilvus), parsed by [repolex](https://repolex.ai).

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
rlex download milvus-io/pymilvus
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 58589c040969bee94d3569e720ad91243ea06e57
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 58589c040969bee94d3569e720ad91243ea06e57
│           └── chunk-001.nq.gz
└── blob
    ├── 000637edd079accac55bb49c2745ea936275b4ce.nq.gz
    ├── 000c13237a1c601696ad42eb74878c2c54d89a73.nq.gz
    ├── 00818cfe5bfa230154ca10301dc4862c9df2c963.nq.gz
    ├── 00997e845aa16e34f09d1a32a00b2ef56fc62280.nq.gz
    ├── 012f1553d9a6e07f170471e12e15c1e26c0514db.nq.gz
    ├── 0147d526007d4cd58b9de2c7d436ba022adafb3d.nq.gz
    ├── 0460f344d64f8b74b221d156120613e476ea54dd.nq.gz
    ├── 05e7856f238c92d3e4c5d3ff53ad29381dc149d1.nq.gz
    ├── 05f4165eac2e21aa098466836d8e2f235524ffee.nq.gz
    ├── 081e455007c2ffccebd87ba63ba04f3cabcb4c8c.nq.gz
    ├── 0873acda8162e3f5b6aa5e6c14960e41f52e05ae.nq.gz
    ├── 09a72a6a6b17ad4de8ee2ae07400033606f716e9.nq.gz
    ├── 0b7e4ecbd32dbeb57caf68238fed2a40b4fe0d34.nq.gz
    ├── 0bf6f50fa2bfb237d898cda352c2b9e4a610804f.nq.gz
    ├── 0d451322400d28494ffcb92e56bbd7d359a08120.nq.gz
    ├── 0d47f6d67001eee54c31024d2b50a8e3115dd6ec.nq.gz
    ├── 0d8758fed991b60ed776d1c4643670e7f982338c.nq.gz
    ├── 0dd651d81cd8075b057e10ed438f0d14dd47b6ba.nq.gz
    ├── 0e6755bfe4c993bbe15aa1b1a9ea4b417412df98.nq.gz
    ├── 0e9af72d271a88116dc78c063b6cd008e9282a17.nq.gz
    ├── 1074644fcc0f739af4f31e4f17a3a84e538ae6ab.nq.gz
    ├── 1169dca262cb3edc92c895952a76eb264b9e4775.nq.gz
    ├── 11df5f093dc442e4ab3265481bf4544eff788aca.nq.gz
    ├── 11e5eb65c1c0147c1362e086fa651ea8f1572de3.nq.gz
    ├── 1214a554e2f94824f265802826b0dafb38c3dc4e.nq.gz
    ├── 1243d0194502a3530285b6e13e5f0b6601328a0f.nq.gz
    ├── 14009a0fb043c2bb7984c47c8eaddca2b0b56370.nq.gz
    ├── 142833bef1f7fb95b20a87b6cb2ae64533049319.nq.gz
    ├── 15032f8fd0c19de5c00889081ad753b9f7194bdc.nq.gz
    ├── 151307373896ad89b1223362909e2e0b63f52990.nq.gz
    ├── 15e112e3b216c936df173f7e8af3c1e14d783fe4.nq.gz
    ├── 168971934a14c9927173b4040d69c3c71f853af3.nq.gz
    ├── 16b8bc708836bfd1fe834c0d6f889589f8ed0898.nq.gz
    ├── 16ef794dcfdcde67f6dd97aa873ec8687aecc953.nq.gz
    ├── 19f44bcb2c82a9610ffde77b13595a7586904244.nq.gz
    ├── 1a0cc1a8615d95ffccaa3a6e780289b4c20954bc.nq.gz
    ├── 1a167750eab4c7f19d1774b39853a7a8cd4c16d0.nq.gz
    ├── 1a29d51d6cc435ee1faeffff5f902d9751aaadaf.nq.gz
    ├── 1a83d1be397946b5a50e7180fce750d3733e3350.nq.gz
    ├── 1c3e9e26ce422dcf6ab2778eb20edce7a7db17de.nq.gz
    ├── 1c8a955ba8552da4b39aff37b1bfc22b6fed8231.nq.gz
    ├── 1d1a8f485aad69ff202ad7cd9dac5734b4c2a312.nq.gz
    ├── 1dd877e73e522b57638d1a623434b5fcbbdd3abd.nq.gz
    ├── 1e6933597afb1009f2fbf4f84c686a47f31738f1.nq.gz
    ├── 1fbb166339cc94fdad5628108f19315424aeb09a.nq.gz
    ├── 20b1080da7d58707ef37bf1cbeb92c642e65e592.nq.gz
    ├── 20c3ecd84b628ca284b3962115d7b768b414fce7.nq.gz
    ├── 20c404e4781f4f6e3c2c9881a4b576c9eb4fe32a.nq.gz
    ├── 20dc4601635197df22025dfa41053bd5e0d549a2.nq.gz
    ├── 217bd0a4cad1d496d355afe5819319cba7fe8e0a.nq.gz
    ├── 221062d7783584a2425d83dec1baf29b3e5fa070.nq.gz
    ├── 25a9c02c2d24e598e84deff5d2a7fbba4f65c42d.nq.gz
    ├── 25c1e0ad6409fc36a06a5a16d7ce9497e7b020dc.nq.gz
    ├── 25d6e526f4f4f1179615413a5491ae727092490d.nq.gz
    ├── 263e1e3c958ebb1d97fa84b99e195163ade2bf5a.nq.gz
    ├── 264b4653005e7e1c86381a2637a50625c08c82a9.nq.gz
    ├── 268bc835b671db5463c68f3abd8df1b0da7534ac.nq.gz
    ├── 2926ae962e426da1cb3b6d69dc280ff9cb5b77da.nq.gz
    ├── 292a59184b56a968f0ed13dd394774be1b5ccfab.nq.gz
    ├── 2a4e8eef5220d0c1ea3685d35e0925406dfaa0e2.nq.gz
    ├── 2ad5aefb68dd025a03f64a0f77d08be0d52a94f1.nq.gz
    ├── 2b899d2abd0097adae21335bb449d6fa151f7564.nq.gz
    ├── 2bb7b39859ef43db8f3b159b083c71b15b5218ea.nq.gz
    ├── 2c2287e1c6f5c4dab031e20acdb8779fdb49a894.nq.gz
    ├── 2ca1285d202dad658a6bb0d4c79d6fe4f734a686.nq.gz
    ├── 2cece614d4e3eaa884b8610e28872f62663ef7cd.nq.gz
    ├── 2d8d465ae903a71870c8b1cefc71604f2d5f7dab.nq.gz
    ├── 2f1f66b647838884a4578597b8068cd69af8d975.nq.gz
    ├── 3084518488eb45012b6fd3343db7adf6af3d6f61.nq.gz
    ├── 30b7ad04eb05fe238dae1a11767f40cbbdc8d382.nq.gz
    ├── 310e8207b09a1eff1d026afa77a403977db420c2.nq.gz
    ├── 315dc76331a4afe6a600223c8575992d15d91882.nq.gz
    ├── 326cb28f62ff9460ff8e661779bd8ebce25015ee.nq.gz
    ├── 328d4e1d80f6c154dd8c083498eca541ab20ae0f.nq.gz
    ├── 3291ad0d1fbfbbf968704f959743f6b19eab5eab.nq.gz
    ├── 32ca61f58acce84b194a6eb605c73fbb03490a1f.nq.gz
    ├── 33ae40f759912f9540575cdaa3d1eb168e30d131.nq.gz
    ├── 347df2abccaab7e825d68db1107beedf6c49e341.nq.gz
    ├── 34c5069e8bf9be7704f6ff63950b6c00939bb45a.nq.gz
    ├── 34ca17f4857c875d9667e992121db6668c7f4b28.nq.gz
    ├── 36ed328c048b0f99e8d863cdf867f0d7147ebc11.nq.gz
    ├── 380f20c124cc873799f63dd932dcdcb87a631f1f.nq.gz
    ├── 3832cc957d2249d122213c2185f966283a7b2442.nq.gz
    ├── 390764ecd11d9790566f76959b3b6c5ece9d3f46.nq.gz
    ├── 3aa056f6fd1593670032d60f1ec2ad3e0685b14f.nq.gz
    ├── 3c5e6b44db2e52093c9933d92278b653f2bb4229.nq.gz
    ├── 3c6bb30ce3597e0f7f54663c534f06cfaafeac00.nq.gz
    ├── 3d73d455c0d82c58d8687b492d839e88b6330b15.nq.gz
    ├── 3ef95bacfa007636269a43fd58c09870d4b757ee.nq.gz
    ├── 3f88cf611b55f41d62a659bf96882dff969b259e.nq.gz
    ├── 3fb8af49e7cb62044a4a0586fe004cfbd6e0fa31.nq.gz
    ├── 41818fb9fa734c6bc74419536cb00bfef601c3ab.nq.gz
    ├── 420ca9c2c34148399c136affccd108c97c989ecb.nq.gz
    ├── 43c461a1272c9689fbe8dcb9e3916a87f231f695.nq.gz
    ├── 44080b68d92c055edb02af4e9c1f78c35a1a279f.nq.gz
    ├── 444aeb43886e607b3f89fe0fa88f00bb724e48f4.nq.gz
    ├── 45ffc037691469fe0a107e9a9a7601e29ceadc18.nq.gz
    ├── 4612be913f589d2e070e8435a123ed3cc78a517a.nq.gz
    ├── 463aeff1708f241b8c4877eeed90c6c114cadd13.nq.gz
    ├── 46598c9f6730131a926182e79828b79ad6f2f335.nq.gz
    ├── 4667a29d504047e8dc2757781690b4d2844261ab.nq.gz
    ├── 46f9946127c1aa9e5a892d03fc889c2e508bc926.nq.gz
    ├── 474bc1fbf890f13a94d60b939d97b18fb00beac8.nq.gz
    ├── 47823af82c0f79775b97d8fb42fb780512641141.nq.gz
    ├── 4830b96b8d5de582b26ffd0c085be2306611cc1e.nq.gz
    ├── 485c88fa0659ad178398218b1d7741b4bf147e45.nq.gz
    ├── 48be0c7eced7409f2f2267e5927c1fd9d30ed531.nq.gz
    ├── 48c0d4d2f4707c3e35d25a82740b97801ac73dc3.nq.gz
    ├── 497eafe0307dcc723280de767c31ae9b61c942e6.nq.gz
    ├── 4a8f437499522623f80d4ed94b5d42710f0409ad.nq.gz
    ├── 4afba2d2b17aaf2b9ba38b9dc8172adc318338c5.nq.gz
    ├── 4b3c2c5dc4c0cef0177605a0cbb98c96f12474d1.nq.gz
    ├── 4f447fabbce7db44f2385b44dae1ae0ef915b1cc.nq.gz
    ├── 51011f3ffb68d8de04e0b1d774046bc9ce44184a.nq.gz
    ├── 5102db421fb55fe91c47a084cb70416db2316c18.nq.gz
    ├── 517e5fe3533fed56bbe09b6d2fe67cd331d15773.nq.gz
    ├── 52338d62093de7c961889f5bb6a4210a37ab5d77.nq.gz
    ├── 5268cd378020727f0579377001b8aa8552eb298b.nq.gz
    ├── 52d83b4e7291349be1df35576424757dbfe3a3c0.nq.gz
    ├── 54a8d89a80218811426b0cba341af8ef7597fe41.nq.gz
    ├── 56ed59087c8a8c4dff017566bd491564b4b8d6c6.nq.gz
    ├── 572bf561b1b02602e92d17dfe94cb301e646dac6.nq.gz
    ├── 57620897f15fd15a882f66836c95ffc3dc74b34d.nq.gz
    ├── 577bd450359ce1b818edd9cc16a227d740435ef2.nq.gz
    ├── 57a881795f40ef9e75e53d4437c0c6bb2a627863.nq.gz
    ├── 5861ca23c3e9b32d37093a33e75f3842b3575e67.nq.gz
    ├── 587f54454f6cbcf45a8d04244b87cf17ae4f4807.nq.gz
    ├── 59607c60f7e63d9dd859c42d4b6a3c1ab7b3d18f.nq.gz
    ├── 5a051c48bf9e22b70f194c7cb2da04508684059e.nq.gz
    ├── 5aaa73f2ddd16b54d81cf012d73df8c8c1d90bf0.nq.gz
    ├── 5aac2b392b54626a4acd3a1e34ce674be7083008.nq.gz
    ├── 5ad3c92e6b192afb7ff05e08ccf987a5575d3eed.nq.gz
    ├── 5ae01b7dd89c03a8a7fc764d88b31ed96076f21b.nq.gz
    ├── 5b0de3e46a9e86500f8c1c421797cb71e8143139.nq.gz
    ├── 5b1b2a40ad1ace6da62957821fc63abf7d475d9d.nq.gz
    ├── 5ba4b3a0afaa47cb404ac4e6f68211619245efb4.nq.gz
    ├── 5c63fcf7708b75c714d9e4290c92dca4c6c35897.nq.gz
    ├── 5c9c98a6e5cf50a97a65a3155d2e834c22b2bcd5.nq.gz
    ├── 5cd49ff1a46597f793a9054024b64ce940f6b819.nq.gz
    ├── 5db4fd7dbdf204d31e6c645c18ff511624257ca5.nq.gz
    ├── 5dd2965904a845b6e301f151924028cbb2fbb4d7.nq.gz
    ├── 5ea0c47b0006e5fb0846c29c8b3d3288f0ea3bbc.nq.gz
    ├── 60682f5eb28e9f912cb4e912ca405f0f3564e2a9.nq.gz
    ├── 61159de971e9846375978347597365d07eecb2df.nq.gz
    ├── 61241d900be8405886562e3859ec2b0f9bca7a89.nq.gz
    ├── 62056e2ee1ca1da275483675182113cd5e9a7082.nq.gz
    ├── 62dea8074091d8050b393e00b7b0b7f1f5904d1e.nq.gz
    ├── 6593fdc4c9daf7f4d945a8c2699dccf6df250c2c.nq.gz
    ├── 66694ca022f18c1407f61fa34991183dad24bfbe.nq.gz
    ├── 669a9cc5938f8d5ee6a4e34f67b975d666083bfb.nq.gz
    ├── 66f4fa848e8c83cd9698d77f4e150e8f99ef3422.nq.gz
    ├── 685ff29440548e02b53b31ea0a5f5cb562946723.nq.gz
    ├── 690e11c261a2d99c528ddda211dc5d2ed8e91a41.nq.gz
    ├── 6a5b7ab448df2cf1dd7dfcbcdaf6b2ce269b5791.nq.gz
    ├── 6aa83df619363f246f8b946662f7f7e49abdccd7.nq.gz
    ├── 6b2c4782d8e3ba739227e9f987bfb59a1705e876.nq.gz
    ├── 6b2e7ee4eaaf46d1160eebfca0504b5f1c71dcb0.nq.gz
    ├── 6c0930f2caab2cfd40222a1edb93d2f9dbe1201d.nq.gz
    ├── 6c5a14d537019ba380df6ae27c7a01a8a72737ce.nq.gz
    ├── 6ecfb5c186f4d0a7e67e0d4e227a71c757929700.nq.gz
    ├── 6f3bcecc20e54d7888f5d590f5bf8152faaf654e.nq.gz
    ├── 6f88456bed9de47ec0627081d1d210db79cfe8d7.nq.gz
    ├── 6f9d42c784c4cc15a6ba5aa17c2be1782156b1b2.nq.gz
    ├── 7060cac3fe4a0a3b72db0e47f5b4bb1c6d869bd0.nq.gz
    ├── 709106b3562c4aa316af388f1ca8a4da548ce527.nq.gz
    ├── 70d4a554554b772c94cf67928c80c09758b68cac.nq.gz
    ├── 733537b5978e4dd7ea68afe7dd687ccc995671ae.nq.gz
    ├── 733cdba25124d0c6a70ca20ca98405a599dc31d6.nq.gz
    ├── 743a7aa1b7a46ad4a6e3ba36d02748433fa664c2.nq.gz
    ├── 754361634243a89f306bf7b8358e41d4e63a5e16.nq.gz
    ├── 75479033e5eaae0e71b43e4f819090d07aed0a4c.nq.gz
    ├── 7723a30b47c9f5300e48f29e41da56bf88c907d6.nq.gz
    ├── 78699f7d879a81082dc8a84d082a3b74ec291e80.nq.gz
    ├── 78bd81d8a4125b483868f194e511ecd7d60c3eb3.nq.gz
    ├── 78f4635268ad9cfb4f08a539ae67706247c11968.nq.gz
    ├── 79171dd3ddf1c142bf5e60e18044d5e510bc868d.nq.gz
    ├── 796578c96a99adcb0c430aa830470a53dc6f7e49.nq.gz
    ├── 7ad4d9fcab768ddacd11f9214a1af7b3637acdc9.nq.gz
    ├── 7d51848b29b40dbaad28f1acdf7c731e6e5f8ef1.nq.gz
    ├── 80b45334ad2f7c7cf7bdddcae03fa2f87e83e623.nq.gz
    ├── 80e5da6276f7377c207cef0468c3f2f0c348e2b3.nq.gz
    ├── 80f9667987c3fe2663968ffc13f819c8307119ff.nq.gz
    ├── 80faa07984b851af016d05ca3c94297423ba7ffe.nq.gz
    ├── 81dfd5dcb85df323c4f77d9d5e062f9f8c44fa32.nq.gz
    ├── 8269cffaaef424072379182e8b9c0d52ddf1a869.nq.gz
    ├── 828a7357a8da2cef870076634bbea6b730616ce3.nq.gz
    ├── 84b48ddea54019997c1116f3a35176728d18ae32.nq.gz
    ├── 86db0eba4a2d3fccc66c27e754c80256a329389a.nq.gz
    ├── 896410b7d791abec79541ab78b98444991e11bae.nq.gz
    ├── 8a8e4f804584dfa526c32742bc92bf8b36109908.nq.gz
    ├── 8b07ba4fef6d33ca1fa56940d87622e81941ca3b.nq.gz
    ├── 8b36fb4f3a0c8fac83d160275db9b50ccfbf296e.nq.gz
    ├── 8b5b3deb8c4c8f24cba7b73b084411fb88ff1b3e.nq.gz
    ├── 8bcdc08e3359a051b0fac3788c7f0b333a7dd8e8.nq.gz
    ├── 8c47f9275f056187c681b3067743677a16b7c63f.nq.gz
    ├── 8c8bed8ef74c87fe2ca85168b5d00aa79690e12f.nq.gz
    └── 8d3dc25f0e66b0adee8fb85d92d619074b02a4d8.nq.gz

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

[milvus-io/pymilvus](https://github.com/milvus-io/pymilvus)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
