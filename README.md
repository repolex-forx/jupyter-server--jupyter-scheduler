# Repolex Knowledge Graph of jupyter-server/jupyter-scheduler

RDF knowledge graph data for [jupyter-server/jupyter-scheduler](https://github.com/jupyter-server/jupyter-scheduler), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter-server/jupyter-scheduler
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 955883c1b33a7c366df0e3e7d9a9523dff48c9b4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 955883c1b33a7c366df0e3e7d9a9523dff48c9b4
│           └── chunk-001.nq.gz
├── blob
│   ├── 016c73776168e070d4e2f2981d3ffe74e57061df.nq.gz
│   ├── 01f16b9eab34b711ff92f6da966c8a831c7de8ca.nq.gz
│   ├── 02cf57cd688d8726c345b7e523faabf578bd945d.nq.gz
│   ├── 04479b2e36a4bcab6e317f00137f35de57d32bce.nq.gz
│   ├── 045b252966f5a48c8e85140ec744a3c73b4fb75a.nq.gz
│   ├── 05043aae4f0dabf2045edadc2b12a76603351ade.nq.gz
│   ├── 06df0b6d5a548c24521e6924387651085c9a3817.nq.gz
│   ├── 08ada09765bffd737f3bc27551e91e8a04af8625.nq.gz
│   ├── 08c3433bf430c0a075bd52ab0aebf8849487b938.nq.gz
│   ├── 0900520ff67ee2464ba062326042b437906d26f7.nq.gz
│   ├── 0bc8e0b9f4bf498bf2ae98523443861f78f7e88d.nq.gz
│   ├── 0c1da493136c422d402ccab01b37a2a8decd0fd5.nq.gz
│   ├── 0e28a9b4f965e0e75c06cbbd6bb9d2b83bbfb441.nq.gz
│   ├── 0ea9c763a913a0a89408e3ed4384a4087a5593e2.nq.gz
│   ├── 1038acc17fc01c9c431d5f858eb5e199b9a7ac58.nq.gz
│   ├── 1039da84f5df22f77e296c0da5365fb7371e1d94.nq.gz
│   ├── 139342bc7ebaa5e7d1c7e7863e5d214acaa10c69.nq.gz
│   ├── 17039b27edf10f9ef32e82ee2125b3d8ada227cc.nq.gz
│   ├── 17f717b55540505a8bb97881b675206b6e06ccd5.nq.gz
│   ├── 18c3acbea8934be7f565e70d0010eb786e6579b9.nq.gz
│   ├── 19774842c80c495a254e7d764ac72424efb96080.nq.gz
│   ├── 19d15e60cf5e3dbf53e3dc9914d5002d2bb0c666.nq.gz
│   ├── 1a10e2042d64147717858f54f70187894b150b41.nq.gz
│   ├── 1c66acf6d8105cde5cff45b003c2bf453577c026.nq.gz
│   ├── 1cc5137ce7f0c453c5d8e6ed36d5c8fba0548570.nq.gz
│   ├── 1cea1a855624c14898e94ea69831bbf463f2fa36.nq.gz
│   ├── 1d6da27071c48d1fb6663c378668322e5b4419f9.nq.gz
│   ├── 1dd2028d843955f1be06059b6e2bd9176e43771d.nq.gz
│   ├── 21a6e82f746ecce40c7b32839aadd84cec6397e2.nq.gz
│   ├── 2586e3562a66b4d5795c0e1c52a6531de3fd95a4.nq.gz
│   ├── 27a30e8796d7418987d3ca57e8492b977c160919.nq.gz
│   ├── 28156f45f86c0d8a13f97f28894205d160d20da0.nq.gz
│   ├── 2a72b65f12bb7f62f2700bcaab20e6a466378869.nq.gz
│   ├── 2b23bf583949a250095015d82e3f11ae73a29297.nq.gz
│   ├── 2bd9bbb3954bd1021073d2ab8fd19ac1da35bc2c.nq.gz
│   ├── 2d3d4c0766ee2e7d9f8a0406b529ae819cfafd8c.nq.gz
│   ├── 31eefef90e4bc576d37860548124847311909f4b.nq.gz
│   ├── 3287ee7f3a901ca9cd12a682bae62a63d9fe75e8.nq.gz
│   ├── 32bb24529f92346af26219baed295b7488b77534.nq.gz
│   ├── 344268a91bf077cb297821eefd4c016c5811b294.nq.gz
│   ├── 3461280d684ef0f2245f9830bb40d9d8fb6c2fac.nq.gz
│   ├── 34d84d9621c2d09b1c2d75718603833c159716b4.nq.gz
│   ├── 3544aec4e880cf9c434c699f718018e5d8f161d9.nq.gz
│   ├── 35bd56b581910f5a765113104af6d33144ed0cd6.nq.gz
│   ├── 3716627c5819cbd700c145f38443a07e0824562d.nq.gz
│   ├── 3868ca80d2a7edaeae47ebd8d112e050f975caad.nq.gz
│   ├── 396330bb9729d2ec595617aef79fb28600d86bd7.nq.gz
│   ├── 3b29b10774736ac023162c82e085104822f5eabf.nq.gz
│   ├── 3c01e9236fc8012bf0761366103e3651f8a6c243.nq.gz
│   ├── 3cd982567103740d09c076531df9f153c6214021.nq.gz
│   ├── 3eb46ddec5744adb7ee52bbb69217a5b9a6d4764.nq.gz
│   ├── 413a297375c00402b69bf5d7e96bfca0b8d7f20d.nq.gz
│   ├── 4572fb6051da68ec0bdf37d0c468b51405e9774c.nq.gz
│   ├── 47f666770a1d81d30964f712bcc56b38d2ab3d0f.nq.gz
│   ├── 4a798af211bca40c527a53e65c4226e44276a0a0.nq.gz
│   ├── 4ae5ff5efe87c5827283226c3cf987fa93d54249.nq.gz
│   ├── 4b3f4dbe7ea18681061e7f3ec925677be347e209.nq.gz
│   ├── 4c918283de365c71faa3a83a923cef9121e90eae.nq.gz
│   ├── 4d278b3725ba5860b7716abe3a95a5657f8220d0.nq.gz
│   ├── 4e0c6efb44ddd250cb0f23e700b75ac7eaaec79b.nq.gz
│   ├── 4eca8d36d2541a727eb3feec67e78e3014c487fd.nq.gz
│   ├── 54d865946c726c84cd86f803ec7c2a2e8d551762.nq.gz
│   ├── 553f4a07586d183423a28d99e5d7f93435bd6cea.nq.gz
│   ├── 554eb6909dff499cb40120288dfb859118a494ee.nq.gz
│   ├── 5a7fe25905b530e7b72517d67c8dac7a585ae15f.nq.gz
│   ├── 5aa1782d5700d487705770eeac26fdc7a7e2ba78.nq.gz
│   ├── 5bad4c8ace882fdef6d0d9bc3d769509fde2099b.nq.gz
│   ├── 5c49c5d4dc84cf0dce87bdd00f0b5f9a4e4e4cc0.nq.gz
│   ├── 5caea336273a5ceb07b2267959a5058d399e9c94.nq.gz
│   ├── 5cf1c71c13911972df16bdeb7b5a725f6b9a2e32.nq.gz
│   ├── 5d44a30c7cc2ed790c07cbdc89ca8d880433bca8.nq.gz
│   ├── 5e5f849bf20e5e8cd9fcece8e6600b4e4ad259db.nq.gz
│   ├── 6071a4a5bdf7ca2eafb08fcfee4bca246f2dcbd7.nq.gz
│   ├── 60af4c5f16741c7c2fe17cdd9718ae5f6d56d8a4.nq.gz
│   ├── 612338104fe3d7afe025184c9e1dfa8dda97d660.nq.gz
│   ├── 62a30644a8a1bc4064aa73588b443b119ecc5fcb.nq.gz
│   ├── 65e98b7f64ab642372e2fea759225e134453fa93.nq.gz
│   ├── 663052829c93300d886a8d1e6f59a8830a8165fc.nq.gz
│   ├── 66546be38287d6f85a1cf4133c41638145a22a29.nq.gz
│   ├── 671d15a2b99a6f9235b703b4ada85e4dc0556df8.nq.gz
│   ├── 68ced84f753f60d7105a711581e8ee97ac80b4bf.nq.gz
│   ├── 6b22ce044ab283c89f4f61d26403404f12b76f1a.nq.gz
│   ├── 6bb0c95a05a78023250405ccf33c3d38c549d1b6.nq.gz
│   ├── 6dcaa1311004dc172defa1e32d02dd836f8e7641.nq.gz
│   ├── 701675fbb52d47297eaa1137e3d2914f8f6a2b6b.nq.gz
│   ├── 702727e01394c18a209d6ea134f4e54d99f28f1f.nq.gz
│   ├── 702e56cc1a3eec420160f0c2fa00b46b3a8eb830.nq.gz
│   ├── 70554d8119eb230e75de73856e5901a3098b3b1a.nq.gz
│   ├── 725feab5ce652dc39f3f2c77b9fd3c90bf049c65.nq.gz
│   ├── 7359ca8ccc65a05f9b48987536b6a2cf200b72fa.nq.gz
│   ├── 736fbdac956914f1b842822060541e78153449c1.nq.gz
│   ├── 7442e8319dbe901157399f762d35c04bd46fbe37.nq.gz
│   ├── 764111f5b0b54c56fed6363c6117ef8ecea1c9ee.nq.gz
│   ├── 7741263b9855341285afd64046ce8b55fd6d86ba.nq.gz
│   ├── 7a5469cb13d9ab41ce40ffb068e2c74463f5be38.nq.gz
│   ├── 7affaa3acbba75c737498555e26b9397904c6992.nq.gz
│   ├── 7f677e646a894f570e6d3315c01f46c2a8d5e9ed.nq.gz
│   ├── 80e5c39143844b120c415709daf3e096b1f19dd7.nq.gz
│   ├── 80f422f7b23d5e0b61561fc0eea984abd1bad35e.nq.gz
│   ├── 82d364236af0d610df11e923e3a97f31af96b7a4.nq.gz
│   ├── 8562898a8c3865ddf1103511d3afe099df431210.nq.gz
│   ├── 863a0c9452a4e922edd3f4a73fdc040a4c31ddb7.nq.gz
│   ├── 8a7ea29e69487a93c256fee6e15adfd533a53280.nq.gz
│   ├── 8b5c76420c6070a63b2beaaa99d96ed45aa3d30e.nq.gz
│   ├── 8b60960a017fcc503552d74ea1e5c20b8b34aa60.nq.gz
│   ├── 8bb5930f6ee3a6b7755ee4b2843e7f369418af73.nq.gz
│   ├── 90c5925a83c1ba737c6cdd6d79dc7683ee0fef06.nq.gz
│   ├── 91830cea31e689b345b9abe5707d339ee4c35d72.nq.gz
│   ├── 920e7d04931e064638ddeeec8578d0992d6963c0.nq.gz
│   ├── 949a6bf81558170bb88dca9249da9f5a4898119b.nq.gz
│   ├── 97025f1e421e164699c56b9f92c0c9f43800fb9e.nq.gz
│   ├── 98c58cd4d7635ef4e33eb495f5f6fceefd4f0dba.nq.gz
│   ├── 99c025ac2d2a2e7a671c4743e4a0289f06c648d2.nq.gz
│   ├── 9a005a9f2355e91f035516ae67ca1cae3269bdd4.nq.gz
│   ├── 9a088dafaf671fd7af9b585c92a2d2f7d22dc637.nq.gz
│   ├── 9ab69cfe0ac585092896ced92625d5d3eddcc492.nq.gz
│   ├── 9d94938f1bc356e29e0d424d7e5e8906c8453646.nq.gz
│   ├── 9ee25d1ddace3fc740beeab4881bc4720f6ae943.nq.gz
│   ├── 9fcb252842481b916383d9d5923f9d470def5837.nq.gz
│   ├── a028a76408bf46181259249b2e15e14a9bbdf7f1.nq.gz
│   ├── a086afa3c0aa48ed46e381679279fea05d061daa.nq.gz
│   ├── a196657a088a0bfceabd1cf2c0bb446225cb28ae.nq.gz
│   ├── a1c400ac213156728a82be15a6f124a13e1d01ab.nq.gz
│   ├── a3fd63f5d809fa5af009c1d56ecae3b58e5edd6c.nq.gz
│   ├── a49f360e7ee632b3352585083822a143ddf0985a.nq.gz
│   ├── a5ebeea4f2afa244b9aca96d484961e2e3b6804e.nq.gz
│   ├── a6ac00c1001aff98b12da564dbdefd29b0a507a5.nq.gz
│   ├── a845d0fdd382d3a8fe5c2bf695d40521a107c35a.nq.gz
│   ├── ac7f515aa9a7a51babadcb09e6bc7d8036daf7de.nq.gz
│   ├── ae3cb40b3c55d27c55d545bb14fa7b2baaa24196.nq.gz
│   ├── aefdf20dbcd4c5c7b8bc90a83f19e845d6da6b64.nq.gz
│   ├── b0471e662a8c77ec0f592ef40a26aab87d4f80e9.nq.gz
│   ├── b0cd995814985a28508654ce631e0bc3de69b770.nq.gz
│   ├── b0ec1c346ba20d2356acd120758edbb8b276d7fe.nq.gz
│   ├── b236ca65fff88ac3330c84ce36c2067a40761304.nq.gz
│   ├── b49fb9798574eac4f4c4c27ec948887d9f2a1e5c.nq.gz
│   ├── b52274ba90bdac6e0cfff56821b7fead4529726c.nq.gz
│   ├── b58757a53f7a86680e6801a88a45375298a521d3.nq.gz
│   ├── b5b4a2267a914e815da71b71085984bacf12a618.nq.gz
│   ├── b5bf9e2de0d7b914eee1b023f2dbfb9afdae357e.nq.gz
│   ├── b7b3c3e6e3d3b62bc229fd13102e5df86c684c3d.nq.gz
│   ├── b9c17d5a99c115efc8b66f522c19d0d994d26710.nq.gz
│   ├── ba3577d9452dcd126932b90d0b2eedba642d2091.nq.gz
│   ├── bb2f2bff1c4e663c5695b76eda5e88c15f8274fa.nq.gz
│   ├── bbd4a01da18736e81565e065dd0cb541a1eb43ed.nq.gz
│   ├── bc651f6fb293d2e9fc6c50377e7b711e90b99d83.nq.gz
│   ├── bcc49ca67f14f1b6bb1fbb5f2697b171ae9fb57f.nq.gz
│   ├── be5418a7978feb81d6303111165bf2ff2a38020b.nq.gz
│   ├── bfa723e7094fa02dec30ddba643f7541c3281089.nq.gz
│   ├── c0bc1deb82317ff75b1e072bf4cbc55944fc8d63.nq.gz
│   ├── c12852e1d7903e9d69c4d39a09bab424906585ae.nq.gz
│   ├── c12fb9206101d922cfe8c3cd6e97bb175bd5a2b9.nq.gz
│   ├── c1881060de286b6e65824cf42d336f09ad37ce7e.nq.gz
│   ├── c2ae97d15ac5977fe15f2931c24735c271379a16.nq.gz
│   ├── c4aed731c4d8683d9b75c39eb63ae500dcc7b2a1.nq.gz
│   ├── c504416c8ac46d0c0cb74dd8444ac1d81613e580.nq.gz
│   ├── c54d78140b27f9e6d85546a38f7f38f7789f52f1.nq.gz
│   ├── c5e7db2702653424590486c2b5acd48567b3d69e.nq.gz
│   ├── c9de389a2c33cc931e6f5aa1b0f796127e9c5b0c.nq.gz
│   ├── cca45852bcca1b0da74b32b0a329b77d5621df48.nq.gz
│   ├── ccec377ae53c31b08a3337256b797a1dcd540753.nq.gz
│   ├── cd0875583aabe89ee197ea133980a9085d08e497.nq.gz
│   ├── cda0f7b39c8ceb6256ad3cb42432f428e0438cf6.nq.gz
│   ├── ceebe535f4cf3e351d3d916eeca5b5b783d618f9.nq.gz
│   ├── d042b1c09b375663ef44e8d9d1cc08b7d68ddb4d.nq.gz
│   ├── d0824a69c143d80f2a5ef9fb11a7cb2e9611eb61.nq.gz
│   ├── d1b84587ce53cc5aa5fc70a254b82e27de6571ee.nq.gz
│   ├── d2d0313ffed9f318f566992236727fcca3e374f9.nq.gz
│   ├── d305fdea410e3866133d28dd6314ffcbae54161a.nq.gz
│   ├── d34b7e90e5553340ab67294b2a2369318fb30191.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d69a9ea3dd9e727cfe6f9febbb96435b0447686d.nq.gz
│   ├── d6d81f5066e9ebae4d0238b6ad98e9af109c293b.nq.gz
│   ├── d74433fbc4e8c73aaa8dd77c6748996b88aea1ce.nq.gz
│   ├── d9c61f6f88311867592c6e9068e8e6a4a00808db.nq.gz
│   ├── df458de8b870f38e15459511995ed8745b189a2f.nq.gz
│   ├── e1521dbab8c7384b496c209f2f2a48d056e19a20.nq.gz
│   ├── e17a87075229f6ff7f15fe26fdeadd4a7934e8cc.nq.gz
│   ├── e1d3fc918c4855446e1fa5fadf114c16aa670e8a.nq.gz
│   ├── e2aab07e69e149fcaf2556397d5757290b110626.nq.gz
│   ├── e4d4851342863986ca0cdf8b75910231fca0cc50.nq.gz
│   ├── e5fa375b36bb9901b416b609c57bc3af0b812179.nq.gz
│   ├── e62cd04e44e5856e46c190bd8f6adb6f1cee89d4.nq.gz
│   ├── e66ae6b9e5f94787864822e6cc8a69d3916ba536.nq.gz
│   ├── e8d3a3f490c3b4804ae722bc553db4ebd5c78c70.nq.gz
│   ├── e956f56a71b1bd6da0f240a26753a39591b249f4.nq.gz
│   ├── eb98a0bef277c4556b6b382433bc2193fff6e35a.nq.gz
│   ├── edb06c7a439683987c5f56c33ddb9fe76abf57ee.nq.gz
│   ├── ee4d5f00943a60300252aad6cd8f0ce78a046f5b.nq.gz
│   ├── f3763bb1412fc4021fd00a21c0301a61b6f32697.nq.gz
│   ├── fbb63372c1ea8e739e04bfd6381ee7b899ea149f.nq.gz
│   ├── fd18dc44fb4493028f50e545f353d68cdba8ae9c.nq.gz
│   ├── fdf0ac5ffe9a1fdce536a35b9676461ab2a1ac10.nq.gz
│   ├── fe5ff17726b02bdae61f588716898375d459c63e.nq.gz
│   └── fffa32fdf63cb1dcbf487758701753be78c08407.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
└── filetree
    └── 955883c1b33a7c366df0e3e7d9a9523dff48c9b4.nq.gz

10 directories, 200 files
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

[jupyter-server/jupyter-scheduler](https://github.com/jupyter-server/jupyter-scheduler)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
