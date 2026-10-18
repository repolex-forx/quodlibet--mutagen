# Repolex Knowledge Graph of quodlibet/mutagen

RDF knowledge graph data for [quodlibet/mutagen](https://github.com/quodlibet/mutagen), parsed by [repolex](https://repolex.ai).

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
rlex download quodlibet/mutagen
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ada28b2cc92c515f3f26640a6feef6516d195872
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ada28b2cc92c515f3f26640a6feef6516d195872
│           └── chunk-001.nq.gz
└── blob
    ├── 00e2a0dbafdb151a6d4c55de1fd4e11c0143aefd.nq.gz
    ├── 024def8b9861a24bd6f3873366b02493959d3ced.nq.gz
    ├── 026ac5d10e204c8a691ad6b61846e49ecc94a9bc.nq.gz
    ├── 02c97f968bd83e66fbfc9b4ad4b223e082d6fa3c.nq.gz
    ├── 03dd80c95f5a5beea4ba3282bb3ac2f0857a342c.nq.gz
    ├── 03f05c0c2c01536c93bccd9f51e4022c8766e047.nq.gz
    ├── 0417d9db4009cacb34d55a60a4a12676256dee0e.nq.gz
    ├── 05bc0bc466653b802b329054af2d155ad7b8db90.nq.gz
    ├── 061891b8bf73950cdb47fba9f9bce3abda7bbec3.nq.gz
    ├── 07b8adc47c8cbe7c57cec6daee63803efd3364fd.nq.gz
    ├── 08f389f4a17218b1c3fe46e25b38278e43984d92.nq.gz
    ├── 0929ef0c99c3eef0fed3a372e3135abca7e4a362.nq.gz
    ├── 0942f7dcc2db89a3bfc6ea2ed88fa3069e1ed082.nq.gz
    ├── 0bd7f9f33dfa28317996eab962cce5cb2d2afc0b.nq.gz
    ├── 0c1e8cbfa9b5a7ee013e421d1399f835947ef076.nq.gz
    ├── 0c880151b6b60b5f5ac4823a064320710b687449.nq.gz
    ├── 0d65ecc187abe91c5ef3a17bc27ca9591a15d3f6.nq.gz
    ├── 0db6129de8a92564f737bc470b667bbb29037c79.nq.gz
    ├── 0dba4b51bdbdb281a0c7d99c842199ac820af59e.nq.gz
    ├── 0e45ec5e172fc645cfd16551156ac311200ab898.nq.gz
    ├── 0fa085538031e7e10f7d3c7cba9f6a8c9bcc56f1.nq.gz
    ├── 0fb1c1cfb5f119c4b136b406617bfdadf1d8baf6.nq.gz
    ├── 1119d2c54a9296301b654bb5d3512e5762e19e69.nq.gz
    ├── 121a01bae105c596522130d7f5d29eca8878c887.nq.gz
    ├── 12ff966a55eca17ca6cd7ded9e217cada418f9bb.nq.gz
    ├── 138b6b66858d359becc4104f21c648716568f075.nq.gz
    ├── 13f0e33a47884ff5522b343a91d86af38197fd43.nq.gz
    ├── 14090564d0ac66699701f5d3fdcfafed33488707.nq.gz
    ├── 158c61f9c33325e69395452234bcfe346a96a361.nq.gz
    ├── 15c88f273fffe58eeb08b7f12c06a34ca2d69512.nq.gz
    ├── 173d4b52865d85f3475854e5db9902bea7904b9d.nq.gz
    ├── 1774c11b3121a7373bb380c14989eae01682608e.nq.gz
    ├── 198704c27dcd9e7982b4d3484187b14557901558.nq.gz
    ├── 19d90ad6ec299f38991e74d0493c3f1e3120006f.nq.gz
    ├── 1b07fc6d77d56f13246d6adba27c73caab48f1a1.nq.gz
    ├── 1b7369e3abe9f38c87116020c5f9c4e0b22cdaad.nq.gz
    ├── 1e5b31bfa515332ab3d02d424e6166d4a57ce54c.nq.gz
    ├── 214f7ac4eb710e8e21de093ee7959dab8fe86bca.nq.gz
    ├── 224af53edf6907bccc8888ea00148cff86e72d1b.nq.gz
    ├── 22a6aa4408fdce2c0d106cd397086683537b677f.nq.gz
    ├── 2348a41a340a205ea80cf335a447badd562e4f39.nq.gz
    ├── 2454237e7d844fcdcd92b3ad22a6f4c980c4c800.nq.gz
    ├── 24e15deb8c85ef82baf22a231901d646397dd8c4.nq.gz
    ├── 257a9d2692eec042c2e531f562933932dbd1ab2b.nq.gz
    ├── 274b20dfddac3ca91029fd02724022197646a134.nq.gz
    ├── 27c312b813a789429b4ffcd5c47879fcdba24311.nq.gz
    ├── 29bd1ad58f1054e54afb8b48693ed517d357017a.nq.gz
    ├── 29cdee9b012e957b5ae92e9913c8df45571be3f3.nq.gz
    ├── 29d7f2d15a4afd635003acbb02e2c8ea2af68349.nq.gz
    ├── 2a077e18b29f7ebf46aebad9a8a6ed2d92cce83e.nq.gz
    ├── 2a109b353812317da9e5a2c7ef3958c0558bc869.nq.gz
    ├── 2b55824f054b37ec8df0e68a5df1d4d49954cf62.nq.gz
    ├── 2c457c979dafd3d3c0d943b3f4bc6f1c42a0f9e2.nq.gz
    ├── 2eba22902442fc61bc4a82035ddc37035103f210.nq.gz
    ├── 2ef4e755054366d3b32655624d6b1d5accdaf0a5.nq.gz
    ├── 30b4a2f784dc8ccda2270d5385b9c22f9aa64a7c.nq.gz
    ├── 30cf78c0f166d3c5fddc8d5429880181019c8aa3.nq.gz
    ├── 30ee5502efcb5b4757db72fa02660192f46562ba.nq.gz
    ├── 30f2773163aa909b723a8ee8e0d94bee07f62490.nq.gz
    ├── 30f8d3ca0e3c68db1ed362ee84f5e6572683ac71.nq.gz
    ├── 33b1559b4c66ec2dc452147f3df8f5733f712aaf.nq.gz
    ├── 3405545a29460883251a5ccd6135ae440bca5815.nq.gz
    ├── 351ac364e43078f42b01a88d75cb00dee73cf4f8.nq.gz
    ├── 36b7074fef6eca82f987c2ee7d50e9e7761dc9e3.nq.gz
    ├── 37b467d6835a81cc99307943f2b7e26281d9f7af.nq.gz
    ├── 3976d8e9ba4df90338e0bc353deb48ba70c98207.nq.gz
    ├── 39f702ca73525c64085606c5c96844c97321aba4.nq.gz
    ├── 3b18e48589aafaf678af7029905488c806a35e20.nq.gz
    ├── 3b3ddafa138f6c8382bb1947864b1ec4c4840dd6.nq.gz
    ├── 3b793d66f5839b80073683adfdf84e2190eadedb.nq.gz
    ├── 3bcfba31276ab30931bd83a9bcd1a98492259b15.nq.gz
    ├── 3c5686ea54e5e1abd3203f7ac4d7f5f3454e480c.nq.gz
    ├── 3c9a000f870a4cd223e39317afb54dda6734ba3e.nq.gz
    ├── 3f30d38adcc36d12e29c4d66a3b3d5177ab52f90.nq.gz
    ├── 40919647ffedc08b3f98e69fbaf677a31d0e54eb.nq.gz
    ├── 40fa74bc38232ccfc1b8e27df386ec297a976767.nq.gz
    ├── 41714416760792085717cb85fa1542e5a7e28981.nq.gz
    ├── 41a2e5c533ec3099e688daf7d951d2fab72ec1aa.nq.gz
    ├── 41f92490c21d54d434f3e2b72fb163f7e5973c77.nq.gz
    ├── 4208d3dfa045ea14a47c8eb837085d197cb3978c.nq.gz
    ├── 440a96939289f73be7d2fbc6cea2fec53b6e95fe.nq.gz
    ├── 44645ad03f88f66fb48612ac37ca788685a56d70.nq.gz
    ├── 44c191067a310a06783caafc06e11cc7c2b1c53a.nq.gz
    ├── 4a25499bc018f0a4f4c9acdfac3d5aebfec0082f.nq.gz
    ├── 4a2b6b17c20d2e1b060ed96d9b943a67565ed57f.nq.gz
    ├── 4a756bafa7f6947a86a4e8f4c341f9178f294f55.nq.gz
    ├── 4b2142f363bc656f0fe96cd70a97f709cd4058bf.nq.gz
    ├── 4cbceb3c97977747977423c92b2e39e7f7a7d192.nq.gz
    ├── 4cdd56f7a06af1f18ba285f2c60f02a2c0bba154.nq.gz
    ├── 502b64a5c52a201a72dbdd897799b0a221c285b0.nq.gz
    ├── 50ec01425338f8e0d67c3f0c848eb7b862d68e1a.nq.gz
    ├── 513f39899e451638047b00990dc223c8506a8eb7.nq.gz
    ├── 51f0a451d18a151a8e372200217839b5d74cd486.nq.gz
    ├── 525e06070b89659647e569e5f240bc657ac4c932.nq.gz
    ├── 56ad5b889b65ef8272c005333b1485f997a02f04.nq.gz
    ├── 5762aee77b860f99dd016e76aa8d119b1389d758.nq.gz
    ├── 5ca456cfdb54cf84183a83aa037f6f4a6f0ca65d.nq.gz
    ├── 5d01fc46ce289bd89dada47bc8f058bc7e703747.nq.gz
    ├── 604fb8f3a4bc1d25d6d6ce0718b5ba702759cc1d.nq.gz
    ├── 60af03b09d580ab4fbefbf003f7bea6884ee0492.nq.gz
    ├── 624dc1a315cf3ab0d72850ebe5b8025d41d8bd82.nq.gz
    ├── 6279cf240ecb78deb4e07945b6bc1646c8614fe5.nq.gz
    ├── 62ef07adbc525dcdcdca3de7286ad556df9d8e21.nq.gz
    ├── 634d3635f019ef0f137831798cd3c9fce3964fb8.nq.gz
    ├── 63e2d9b2975143cfc9f744d68dd4d3301f15c859.nq.gz
    ├── 64ef526eb374d9bdc9d53489fd962554e8e6f691.nq.gz
    ├── 67594446a0d5fe16c62433aab16fd10105d817f2.nq.gz
    ├── 67d7c6f2deefb2ed3bfcb8baccb49dd5fb73cf61.nq.gz
    ├── 699c5dede63c9856cc434ad72c7af094ca201751.nq.gz
    ├── 69cb76019a474330e99666f147ecb85e44de1ce6.nq.gz
    ├── 6d17e65f0f865303397cdb08632cca5a2aa0365a.nq.gz
    ├── 6d4dc42b76a3454815c045866f7c5feaf1d832ba.nq.gz
    ├── 6d7f381ba669afa0a4d7d7135b982b7d144a9d5f.nq.gz
    ├── 6e4e9c554cad109c2b1d603ec240f8d8afd17d3f.nq.gz
    ├── 6ff0c9922e1901c9ffe82aa1c06ecb61e330f2f2.nq.gz
    ├── 70572b4587f26b1dfa1b93035b65a90f47ffe511.nq.gz
    ├── 712bb7963f624622b7f56d35bce32dd6334a95fa.nq.gz
    ├── 71608a5ab4f05208bdb64dee1a80b90bc1c45ba1.nq.gz
    ├── 71f02c1573f9da792a3feafe513c1f3907d22e83.nq.gz
    ├── 722b4e2951dbc9228eff2807e424cc576cc33f4e.nq.gz
    ├── 72b86d50be3f73bc0e32e59afe9acf692fe6d029.nq.gz
    ├── 72d1acb27ef884bb9c8c425e8d74e729baa32d4a.nq.gz
    ├── 74c050b1c71813c9eead68c78fb8deea5f846580.nq.gz
    ├── 74d2f03d6df52cb1422b48769f24dfa9159f2586.nq.gz
    ├── 75ce18ec1b1f867ed9b3cca42c4eabd048608138.nq.gz
    ├── 77282315596bde5dc06fcf92d87aaab9e146a786.nq.gz
    ├── 792bd619195d9e284e306d31b2dc8f5110b22add.nq.gz
    ├── 7a69493b54d6a25ec631ee9693ea75a7d948147b.nq.gz
    ├── 7aa8b466c644e7449408f8b1939285fe1f4fea82.nq.gz
    ├── 7ab9791e2015d3b3717c8769db529908ecd75810.nq.gz
    ├── 7b0b56ad95f837f1f94ef600dc7eae2666ad11af.nq.gz
    ├── 7b193ad0c30f503dcb8ca1e27c4ea4866d45c0fa.nq.gz
    ├── 7b9782a3022389436f572c58ba9f1106c6afbbc3.nq.gz
    ├── 7bcd6eabc8076f62c22032b63cf1a160875eb170.nq.gz
    ├── 7c2061a64a07fb1fef5534dc4cfab5a6d32b1b28.nq.gz
    ├── 7d41b8f68d85c6e8af7c60132bfb010f1a139fdc.nq.gz
    ├── 7d782bda7fb41a6ed339ad631cd65d4b146bf253.nq.gz
    ├── 7da45319fab8e03dd6fdbd45a90969beee9ab538.nq.gz
    ├── 7e25f338846536803361081da4be065a25b75b72.nq.gz
    ├── 7f5dea001cb62cc0c238d9b8ce62d13da9105065.nq.gz
    ├── 805a83b017afd68483477b4e65b482ee67236557.nq.gz
    ├── 82a3d0476744a15837ac9db64400ba9c6f25999f.nq.gz
    ├── 83f86b5079910fc1a6b2dd41083c9e7e1e96fc61.nq.gz
    ├── 843ab6ae65864e7bc5aa7264714d73ef72b1bddf.nq.gz
    ├── 8472632917f65c168bc2020a9df74ad34e0c2595.nq.gz
    ├── 8591f2c15e08fc635f40626bf729e47c10273ab0.nq.gz
    ├── 8765765a8bf6f52469b89d71af5d9afa7f44df99.nq.gz
    ├── 880a2d583dfdbc10f90549af27327946dea6791e.nq.gz
    ├── 88f739f9a9d427a06e21c4ebefe99417c332d378.nq.gz
    ├── 8a1ec7dc664da57e4f262379221efb1bdb3eee82.nq.gz
    ├── 8b049e986154737c87bab6c8c877f11b27c97398.nq.gz
    ├── 8b21395cc5cd8804151ecc7de6ae2d92cc867a58.nq.gz
    ├── 8b5d0d426cb851dd5d57659314a31910f4fb4a92.nq.gz
    ├── 8c82d141f6beaae139f0602b182311f7c4d8ce6d.nq.gz
    ├── 8da4cdc7d85604c77dd625d7ba823ea046368957.nq.gz
    ├── 8e56a5237e7a48c69d5814e45fa5ce7617656af0.nq.gz
    ├── 8f30eb14b205194f81b9a2a4e6b34c0f700d5382.nq.gz
    ├── 902a90f5d210e35019b836d4300fda8afaf12ee5.nq.gz
    ├── 9200c6a24d471ac0d60fad4c50025719bfa44e6b.nq.gz
    ├── 92ce4e5c3098fa06f6ba7e822b103cd3a3cb422b.nq.gz
    ├── 943576228d9de0de6190bfe497856641ee6126eb.nq.gz
    ├── 944de6d5457ddb26ecd3d0ef196da6d28d4f70f9.nq.gz
    ├── 94b5bb2f3a99fc895aeacc651d765db366dfb0f5.nq.gz
    ├── 950ad4cd4d1822336fcb68c9ad089eade3b7a1cc.nq.gz
    ├── 99aea2d2ae576f069deab0477045fa0e0b10b4b7.nq.gz
    ├── 9bfb4687718bc910b564039f04ee1b9b86762f31.nq.gz
    ├── 9cc00ba8156b8ef1b16401b0efe65b6d64a1b1de.nq.gz
    ├── 9d3c40e0111a7a691fe024ac4063d7338f5b2420.nq.gz
    ├── 9d5032557da7561bc5baa7cde56820205ce09c71.nq.gz
    ├── 9f1ed73e44837eb4eb00222342a0f9cd32591296.nq.gz
    ├── a17d0b4a52f504fc9df4ccfcdb49cba6443f1c63.nq.gz
    ├── a1bfb0a845c1a46ad40002b160b63a4ed04ae04f.nq.gz
    ├── a236cf82020a357602843724cf8a5894aba9b892.nq.gz
    ├── a268d5ded16877bd90de2e7e4174d391f9d07d49.nq.gz
    ├── a3073a255eecc15efc13d063c20d3a3ced2f9d3e.nq.gz
    ├── a35e5bd2592b84b5e6d561876e907b7143585640.nq.gz
    ├── a37af1fd15be893ecd3a3f90233eb6ee07dab4b2.nq.gz
    ├── a41f14e9ea2175684ff2ab74d3682ddbd0785765.nq.gz
    ├── a52838c62bc5c43bd53d34fe98152901cb0d3c57.nq.gz
    ├── a53db8ce1be6e5bc8466d791eb084f614601b999.nq.gz
    ├── a64f4be51335feb9939d3ea6784e14df7aef5d42.nq.gz
    ├── a67a25c8e6ee0c251f8a0fbafedd670acd2e2533.nq.gz
    ├── a6fd2f37c8b1114d973d841507a3e81110756a6a.nq.gz
    ├── a74adf99247ab42c20fc4b2d34a542efef8db18c.nq.gz
    ├── a756a6917c1dc774556c84d5251f3070a4470aa5.nq.gz
    ├── a7e6cde4227218c4eb85d2d1e0b42d95ed76be2c.nq.gz
    ├── a9b4b2cb3763ad14d86b13fd8a90e946934aceb2.nq.gz
    ├── a9cb02e165f2ce74b580c632391448862c44fec7.nq.gz
    ├── aa533104d6fde177772775137cb7660a3be11418.nq.gz
    ├── ad4a8720bc3d0e8bc0ca00419851c49d8be90237.nq.gz
    ├── ad51f52912592a540324a7d5a74184a8c96592e2.nq.gz
    ├── ad7b1f6336b8757218e37ce45c1049d2ac38ec68.nq.gz
    ├── ae895ba21cb8d6ca9561db087d4373d976503e3e.nq.gz
    ├── af9c67caf695db2ef6afdd715f3ea65bcf4d35a1.nq.gz
    ├── b0669acfaa8587bee97ccb106dfee9cd44255264.nq.gz
    ├── b23c9fd0e4d0081c5fb1a3c10a9bf91ea590ea5e.nq.gz
    ├── b31a2f81246d3060e200fc748319079d598eeaf4.nq.gz
    └── b3357d53d3231861cd408fa3c66ed80b295513c2.nq.gz

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

[quodlibet/mutagen](https://github.com/quodlibet/mutagen)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
