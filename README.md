# Repolex Knowledge Graph of canonical/kafka-k8s-operator

RDF knowledge graph data for [canonical/kafka-k8s-operator](https://github.com/canonical/kafka-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/kafka-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a35dc7393b487a5794f347b4902da23192514412
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a35dc7393b487a5794f347b4902da23192514412
│           └── chunk-001.nq.gz
├── blob
│   ├── 02bcb31e6e165b9358265ca976288ebf056ad163.nq.gz
│   ├── 0432a40a0c8c1591168ae0e5f656e452d15e2763.nq.gz
│   ├── 07111ead065b0ee6dadac370ebcb5e3a924965c2.nq.gz
│   ├── 07147d636129b3048545ff09371cf03e718cebca.nq.gz
│   ├── 07e0b48cbd1569fbf0e610fa77b6a4e96330574f.nq.gz
│   ├── 096918629019ad243714dfecf2af3fcc483d7600.nq.gz
│   ├── 0ac9bfba1a33c4b41d128f2b5505cc8dd45fd20f.nq.gz
│   ├── 0b680d508757e960bfc1e7190cc29509514d1562.nq.gz
│   ├── 0c2958d2cd1a885f2590ac56995bb792eb0d753d.nq.gz
│   ├── 0cbe8499db5a36417d8c4cb38f18353ce2308d91.nq.gz
│   ├── 0d2d1d100c8dc49c232cc59fb26cf713f763a330.nq.gz
│   ├── 0e87bc6336df0b6d8f541c5e004120a085301313.nq.gz
│   ├── 0fcdac6c318974a1cabb1f243684abc5117a3984.nq.gz
│   ├── 127f379a07d5ffc7233afa836871a0b27d854dae.nq.gz
│   ├── 134ffb09dc9eb2114fb024c5c626e34b1de1fad2.nq.gz
│   ├── 14a506073146f47ff88f94dad00166e47276d02d.nq.gz
│   ├── 15dcb52ea42f84e3c8fa9a67a4b3259efa57bc8c.nq.gz
│   ├── 173cf0e171208f0cc4aa9b91186a4f4677e1330d.nq.gz
│   ├── 1d0df76c88cafe5fcfbbb4e6091339091653f9ab.nq.gz
│   ├── 1e806832cf9b166b829018addb975439474ff43a.nq.gz
│   ├── 2259c6ee6c3dfe2fa26ddbfb60306753572e0967.nq.gz
│   ├── 22a0182c079ddfe638c7921a1dfc48057195a2a2.nq.gz
│   ├── 233ffa0b572456f1016263e1d51a5b64230f0560.nq.gz
│   ├── 23770e2b5d4fd533842e4eb7664b955a1c640fca.nq.gz
│   ├── 251a19d061f694a4959b0d91a24c048088f89ff8.nq.gz
│   ├── 26127626aa98bb9da05c1e2bdec7435fa2f97d3a.nq.gz
│   ├── 269fd6494760d32e50690a4a81844f8883494e65.nq.gz
│   ├── 29ad4baaded12bd41da18f598494b9140c86d50d.nq.gz
│   ├── 2af691cbf507e661020cdaffdbb3390c9ba4259d.nq.gz
│   ├── 2b81986ce702e6b1d28c30bc9a7a3b5285cc3b69.nq.gz
│   ├── 2bb8941c91796075462b20545b71db59a2639400.nq.gz
│   ├── 2ed6ee8f27ce6f2b34bd6a44bb3277fb8493087d.nq.gz
│   ├── 307b5f2ec4afd37039c61500decced8f538bc94d.nq.gz
│   ├── 3282c22312925681c449bde6752dde32a75b2e65.nq.gz
│   ├── 33c166d753541679d86ca99dc1d5c3bb317e8c65.nq.gz
│   ├── 3413b294f3c957c762d0cdaaa563d5b8c0e1986c.nq.gz
│   ├── 34f8ffb3470a29a637be9d7508ae9d5eab2bf701.nq.gz
│   ├── 366db0ef3e1433ff54c992500ce9f69d436a5e3b.nq.gz
│   ├── 375c690dd606784ab7180208315a9044ba236597.nq.gz
│   ├── 3e8e1834e17ff7f7882510292f474fce3d2779a4.nq.gz
│   ├── 3f44d2d563c8fbc693e389816bd0d6e8ddbc3aee.nq.gz
│   ├── 40adbfc7c89ea407b6a72eabbd4dc28ee4d17d73.nq.gz
│   ├── 41c5f4622e7f0b2cd3cda8482fd1b6ea0c477e1b.nq.gz
│   ├── 41f6bf6dee657dce8c114abd42e6191b4304aaba.nq.gz
│   ├── 44c10d9bb58e27f74b4caa4032001bd2607ef966.nq.gz
│   ├── 46f57d894389a4b0c248e51db44f85a0fec1c5fd.nq.gz
│   ├── 479ebcbdc8e0efd5f5b4efa6accde870a2f38067.nq.gz
│   ├── 4968d2397ce05dbbc3d1c37b6088e2615a2795e1.nq.gz
│   ├── 4b05f5d47b9b656d9370779331a66d6d3c860466.nq.gz
│   ├── 4b92c42d469ce1705f338c07c535fde0c2e2f5bd.nq.gz
│   ├── 4bf31f03b0e0ad271052f498e8923f7a248bf623.nq.gz
│   ├── 506b9d8a4091d86814bc24316ab169e829980d4a.nq.gz
│   ├── 512b0cec8fb959d8092a57044109cd465272a0bd.nq.gz
│   ├── 519a87de0b719843c8aa56d433bfd40844b944b5.nq.gz
│   ├── 51e55e78ce79f99951c4aec1c4ba3a8c159f72e9.nq.gz
│   ├── 5248e0b5a12bd3b7a306f055eefee517de441f50.nq.gz
│   ├── 52b14668ddc18614cd491fd868f6a72aeeaaa3b3.nq.gz
│   ├── 532b877407bcd691f6505b9a28d5c513db376c8f.nq.gz
│   ├── 536277de82ed4cdc7306112348641427ab1c7c79.nq.gz
│   ├── 53dec7b2b80a53efe323dc52e0a364133318667a.nq.gz
│   ├── 54a060c6c13868be72c1cdb46601d8984a0bb792.nq.gz
│   ├── 5541c67e6bf5f6e81bcddc6cc6b0bcc42253777b.nq.gz
│   ├── 56d3948bec7a67cf917a364bcfc85d63def2e76d.nq.gz
│   ├── 57a263e88b6491d3c55d1e151b75f45a10a418ee.nq.gz
│   ├── 5a15145e4d56fcb861307fa205960a5e6f185908.nq.gz
│   ├── 5a7d4ce306013bc7742622b347b7da5cafe7351f.nq.gz
│   ├── 5cd4886d7b36524aabeca35830e6693d9657bda5.nq.gz
│   ├── 61cbb070fccabedcc52c8caeb6668060da2f53bd.nq.gz
│   ├── 63cb78ed02a92c66f3020cc37a83bf6df02eab5f.nq.gz
│   ├── 6703dea5b787599080212ad91f16c1fc821f8466.nq.gz
│   ├── 6b8ecd6e24281cdf0b9084274c6aa883c84ad434.nq.gz
│   ├── 717b831ce7f44b5aff7c3835ef117334997c6f62.nq.gz
│   ├── 71cdee39cb58230c14bacdb21bf6350afef65785.nq.gz
│   ├── 72b23a84959c38cbc6d30b92cbe16823baf91b68.nq.gz
│   ├── 74cf4c74bd2c59e4e7a279ff8f339c6dd3077b2a.nq.gz
│   ├── 75e9e7006eee8909a6080e94be41f8f6f82bea5f.nq.gz
│   ├── 7620f62e5708639ff069248a284f425c0384e2d4.nq.gz
│   ├── 7639c0068066a47c062131c37121b4f57d198e9c.nq.gz
│   ├── 77ec006202c6bb9f461c876affb111a61754de3e.nq.gz
│   ├── 78329b061b6fa78c51669d7d3cc04aa7435190cf.nq.gz
│   ├── 78f28e8aea21cca6df08de0eb87d4aab7a45e955.nq.gz
│   ├── 79b52ba06b12fc4efb61f3c59a1a48fbd7bccbbe.nq.gz
│   ├── 7a08d59802a4bdd428fa93993b5cc9ed7b9e66aa.nq.gz
│   ├── 7a3825a60b544a06e4eaa593cec3fbc0f580fe6c.nq.gz
│   ├── 7b5666dff529ced63411eeab4c56293824e7cf60.nq.gz
│   ├── 7cf959d3306f00cd35494711c924efdde1d6a8de.nq.gz
│   ├── 7d812794d315df0e1ed2ca0faf87fa6b5cc68722.nq.gz
│   ├── 80036c8e9f03901f18d6c3287fcf5d7f7dd285e8.nq.gz
│   ├── 8245835e87cf6cd45fb3ead6d9882bdb55231e9b.nq.gz
│   ├── 8285246a0ad87b3c3e2fb0dcda7fc436ac2bdf99.nq.gz
│   ├── 83f78b4194acbe0637cc981af7664515537c9dc4.nq.gz
│   ├── 8472fcd892864e2bc1646f11b253e7e99947337a.nq.gz
│   ├── 84ff42356a9cb1ac22933b4693c59b4e807c5d8c.nq.gz
│   ├── 859825096c72c09c55ddfe2d7fcec8df7c4a93e9.nq.gz
│   ├── 8599a729c35538f0745395ee6228c3cfd5a5efc2.nq.gz
│   ├── 8a1ff4a70959a6b5da128edd7c643b55f3aac5c5.nq.gz
│   ├── 8aac72bc05692d3aeb13be505883b6035369804d.nq.gz
│   ├── 8cab71336fee34dfee11cb67dcfc82dd34df6172.nq.gz
│   ├── 8d36ce072dfa15099a9e7090391c932276c59913.nq.gz
│   ├── 9084fa2f716a7117829f3f32a5f4cef400e02903.nq.gz
│   ├── 909809285d2d74fa0a52b4072090c6c352dea6bd.nq.gz
│   ├── 917a1e4cef3fc29911d871d8a1f424e72b7f52cd.nq.gz
│   ├── 92190aee06d151ebfb34c4e856d6ad70b7e0892e.nq.gz
│   ├── 9279520764d19c80dffe71b5ec6034c85985fd81.nq.gz
│   ├── 92fde7f40859746cdd630fa5076d2266ad4b3d9a.nq.gz
│   ├── 93ebb052cabbabadbd6c272be54994bd09306793.nq.gz
│   ├── 9437a794cf4d506a8fd200fb11549eb50810b9d0.nq.gz
│   ├── 9886fc2b40dfc111e4cc7eb94e14591d5ee21aab.nq.gz
│   ├── 9ad725d37dc86a466308b465a4b78a652113c594.nq.gz
│   ├── 9c9e41148093766f4290d81565eee7e9753763c3.nq.gz
│   ├── 9cf5809a93686825a8dc96d853a269d919aaada9.nq.gz
│   ├── 9e611695c0d9e34fbce72b144dc041d68b179fac.nq.gz
│   ├── 9ee9ae71302c0315f19ae6761c0f4b360890de18.nq.gz
│   ├── 9ef36aca6d2980f250f98016204ad1e4b0f11d84.nq.gz
│   ├── 9fc92db3c9b027a4cb29184463bffbedd1a39469.nq.gz
│   ├── 9ffb0a7fcbe296a4decd5de70efd1ea1eba0fcad.nq.gz
│   ├── a1dbb8299afdaf3fe254eba61ee68f42e2399ec6.nq.gz
│   ├── a3339b7e374617af9383694c5daa87dee3d9edfc.nq.gz
│   ├── a3e2751d2cba8bb2cce1a5c000a0b182366dd26b.nq.gz
│   ├── a6019c082297f848fd9b5654ee739e2544789d13.nq.gz
│   ├── a6553b8e194ebd8612ca370b26267b1b86b67377.nq.gz
│   ├── a688c12c0b2716cc3b2257d3ec483688dbad5bb3.nq.gz
│   ├── a69cb0ab068255720a605025484fdeb1f63b46a4.nq.gz
│   ├── a79017538a8f7f5cd66e8d9633fd3d0ca7ead7e4.nq.gz
│   ├── a7d6484e5fca5705578716f4d015d55a0a82a626.nq.gz
│   ├── a9ea4b2c1dbd61a71da51169a2abee13a969b228.nq.gz
│   ├── aacb759a4cb432b4762203e053b3045a9fbe158d.nq.gz
│   ├── aad78f1f7ce6363e24accc44c2022d8bcedc94c4.nq.gz
│   ├── ab42e550d5c87fa91feec1acb31b01376d880b2a.nq.gz
│   ├── af0083074cdfa861dbc7bea615114415ea77278c.nq.gz
│   ├── b09dda78c12244fe17dc25e4f3bfaf3b98b237cd.nq.gz
│   ├── b26ed145716069e6ef01c1438dd1569adb9e1c79.nq.gz
│   ├── b30bea05a9c238e4edb3dac4cef87929e8a2b157.nq.gz
│   ├── b38161ea38b160b291b9e9a418edb0f78ef6ed7a.nq.gz
│   ├── b44ccfa08ebfddec565b674f9025fd1f01440a85.nq.gz
│   ├── b4674c0d65ec93d3afa303b06b2ceb38806566d7.nq.gz
│   ├── b64dd9af37d41aff87b94d2fa7d0144267b6e4f0.nq.gz
│   ├── b866522686bdf50a29e9ebd60ca7f3a2bba2c67e.nq.gz
│   ├── bc58b1446e02d6cff07d29492b755779c1b3800a.nq.gz
│   ├── bd1ff1cb4c75ef924d6edd2e38f3d0077d966e1e.nq.gz
│   ├── be696dcc638dbdb871fd85e382a723f9f394f87c.nq.gz
│   ├── bfc75355911402977ea8365e26ec051cce465796.nq.gz
│   ├── bfef6cad97439161bd154be2944f1157f9af1864.nq.gz
│   ├── c4665e2483cec88f4ea0b3d69dd513fb5997c2fe.nq.gz
│   ├── c49b954ed0a2287e78818beab5a0cf7cfc130a40.nq.gz
│   ├── c756459e08dbebb7f28808e7675d2121b0bb2ae5.nq.gz
│   ├── c81412827ff88b462375674adabd58ecad2f6e9c.nq.gz
│   ├── ce012c6edc8356c4b5605efbdab0f000d54568d8.nq.gz
│   ├── cf069ab2e31e0bc00e91379b7b654734cb6bc72e.nq.gz
│   ├── d011188c7b359888829e8447ac4a7ba0cb5f2e60.nq.gz
│   ├── d065bbd560b3518d961087090d627b2f483e8821.nq.gz
│   ├── d0b2d78ad11fe69a0296ba64159f33f2ec4aeddc.nq.gz
│   ├── d16238d3eb886eb3044d4e696093ab20c781257a.nq.gz
│   ├── d180200dcaccc03ff159bdea27f94fc57cb57e79.nq.gz
│   ├── d39acbb4ec8cadc2e15f04e6170f9d6ab14df9ec.nq.gz
│   ├── d3bd15864cbfbe322d2790c7855840d41e169d83.nq.gz
│   ├── d4d2f2a7bc973d88ad179f1b2304e72739086509.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d7226ca467dfbbf88fb92b7966d04946c6859009.nq.gz
│   ├── d81d4a2d60d4dd2508c2e1e08cadf385010d9a17.nq.gz
│   ├── d95ea7f71238daec66e27bef8a18fd54b274914d.nq.gz
│   ├── da498386ef47b4f16dd38532bcb118b9f5042c6f.nq.gz
│   ├── db3bfe1a652400bb6963dfc7ede76820781ee928.nq.gz
│   ├── db3c31e9b486685bea6a5f5a2d703abca521c692.nq.gz
│   ├── dc2806dd40f1f83d0cebafd1e9d25b1c13aec0ab.nq.gz
│   ├── dc9a5481054115d8390a9c1d2e6418777defc226.nq.gz
│   ├── df76b8e954c2990a1aa8876f356f5d12fcbd11c0.nq.gz
│   ├── dfaef62828fd7bbde51ad42784cf6fd9046cbc8f.nq.gz
│   ├── e0de019db351743fd9a5848cf6051e58df4b93d9.nq.gz
│   ├── e13cdf0524167865f819f360d50e342be789f8fa.nq.gz
│   ├── e1606e188fb6b21965161a212e08d3258ccba4b5.nq.gz
│   ├── e2c8e860eaacd4ca9ef219e9ba604c5997ae8fc4.nq.gz
│   ├── e442c9faa057ca384f3a9e82ddd6abf484b34939.nq.gz
│   ├── e4beb29a215142ecad24d6fb397f1322835188cd.nq.gz
│   ├── e65f0ae7aa91c2dea4e226a2cd2d7f1b546ec569.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ab397447455aee53e00152f221ee6473630213.nq.gz
│   ├── e6dcd9caf36451bc1b1d8035a17188968da94020.nq.gz
│   ├── e746acddfaf48aff24dff583e98dafb3770f2ef6.nq.gz
│   ├── e79a90c5e500ae97bf2922d28f56866be85d8394.nq.gz
│   ├── e7ff5f196808b14020264064b8aa15564a25c417.nq.gz
│   ├── ec26cd6741bbb64e3e4f5fcbb4b5e71903a197f4.nq.gz
│   ├── ed4e862cdbc2ae558557bf7761e8049e38e9299e.nq.gz
│   ├── eff78731acbd2aa26ac428637e60d3e319645be1.nq.gz
│   ├── f048927fd8b5f2ea7d27d3430a5fca6e520106fd.nq.gz
│   ├── f1029f586203a757eee13cd918ce87caf100519f.nq.gz
│   ├── f5b69682426623f733910dee1dbd06bf636c6ed0.nq.gz
│   ├── f6fed7649fe34cb5aa13b0b85cca81d8cf7e54d9.nq.gz
│   ├── f722f50a2a5783f3022bc7cba5b24bf213d9b3b7.nq.gz
│   ├── f776668d15078617cd5b77a485b39cbb281ed068.nq.gz
│   ├── f7e4fcc31e5e17e8e9f18ff6a04820d6c41dd212.nq.gz
│   ├── f8218d821f474e903fa0edd6890a6af9e83eea3a.nq.gz
│   ├── f85dddb88d0c792f7dfe20f8d598a0f1850f63cb.nq.gz
│   ├── f94f2fba7592dd9c1ca12bc218564c9926a943c4.nq.gz
│   ├── fd1f10102eea1c45c18af43eaff2cc249dca9761.nq.gz
│   ├── ff52245c9cfaa5bcf811785450528ad234783e84.nq.gz
│   └── ff8a18a5ca69502b9f7f2d0b1c84b34a9ae15493.nq.gz
└── branch
    └── branch.nq.gz

8 directories, 200 files
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

[canonical/kafka-k8s-operator](https://github.com/canonical/kafka-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
