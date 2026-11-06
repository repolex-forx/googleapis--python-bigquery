# Repolex Knowledge Graph of googleapis/python-bigquery

RDF knowledge graph data for [googleapis/python-bigquery](https://github.com/googleapis/python-bigquery), parsed by [repolex](https://repolex.ai).

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
rlex download googleapis/python-bigquery
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ca965f25fa3df5915d8763d277bb014a3de124cd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ca965f25fa3df5915d8763d277bb014a3de124cd
│           └── chunk-001.nq.gz
└── blob
    ├── 0080152373d5d919b6d310d21d1be23bcf81a920.nq.gz
    ├── 00e8dc1b2abaf9daf80fe343d655f117a8089ccc.nq.gz
    ├── 01097c8c0fb841c7c7749c9ce6040ff9212c2e79.nq.gz
    ├── 011c56d4e8e3ecbc7e16f28c79a06b1a0f3ae603.nq.gz
    ├── 01e538ae30160a064a91255721787f23c4324cba.nq.gz
    ├── 0251039579ca34cb5c8c2daeff08a780cc400fd0.nq.gz
    ├── 0260da5e4bc8d2c9ba8de0b1e9f409c5284ad359.nq.gz
    ├── 0277d7d0f29434780739644463490ff96f908468.nq.gz
    ├── 02b07744b1d1e81a179bf012deefb53c2c7b4ccb.nq.gz
    ├── 039f436812047176f9dd787fc07cb5f8af8dba63.nq.gz
    ├── 03c70bf63b2b65fa57f287a4716d9bef5d5ff77f.nq.gz
    ├── 040c96e226160f9e222de66e5e58da4c6b39b7c6.nq.gz
    ├── 041923da911cae10fc29b34bab30bbf4c20f14a5.nq.gz
    ├── 04932d3572b34acca659980c3a8e997a28d07d44.nq.gz
    ├── 04c99a55caae5d51f17666f554c2c8cea0aadfc0.nq.gz
    ├── 04f6312d3316410ef154998b68cc28d0ea0d455f.nq.gz
    ├── 0780db61a44655daf3af6b7ab255223eccc72cfc.nq.gz
    ├── 07b823e2c43856fb6c2510c1596595d4f73f45f3.nq.gz
    ├── 07c7a28b763d2409e7da292dc463f268390383b7.nq.gz
    ├── 083dbfc4f06f4932201392b866f5713496918b67.nq.gz
    ├── 08841ad729223361ad7789f586be98e84bb46803.nq.gz
    ├── 08d75302bc659c5cee9bc4a0b676ea06b4935eea.nq.gz
    ├── 0943c535a4149bcdc16a2b9182aa66967007b9f2.nq.gz
    ├── 0ac947db0d09044cea67870338e4cee1d055b8ac.nq.gz
    ├── 0b89f08630bbbc288eb750c95ac08b303a3f69bb.nq.gz
    ├── 0dc05ffadec21794f4d1a54e75a8c6ff1e256b14.nq.gz
    ├── 0df8463bed504e0432ed5e760262aeb0878c7478.nq.gz
    ├── 0e0b2cf1916a9d65e14307a5e517456590714cd2.nq.gz
    ├── 0e9eaaf8f78cbbb31e07e208e6d0095bbfc27290.nq.gz
    ├── 0f8ddbae1ed97d692d90f8ee95fec5736a4c570d.nq.gz
    ├── 11957ce2714a5749fa07c793fbf3e8222d7479c6.nq.gz
    ├── 120b0ddc43642d9be721745b311302ef25aebc41.nq.gz
    ├── 123aeb6e7947a2ff1e5e62e5bb1d76eb35fc2726.nq.gz
    ├── 128ab87d998b70b1454799ca3ef8e805cc3adad0.nq.gz
    ├── 13400d69cd5479a006c5700e45d1445ff1f226e0.nq.gz
    ├── 1446b94a5e3a4a525f91bb085b0f854bee3494e1.nq.gz
    ├── 14823d10a7f60ca89703b3265f7b6dc4fe7d0435.nq.gz
    ├── 1487f6e65b2b0a6569cfacfe220f22621492a037.nq.gz
    ├── 153746cccae755885dff4411f7f8865829af4f3c.nq.gz
    ├── 16581be5a49252466495a8c4492498e41a8d9b5b.nq.gz
    ├── 168b201f66f41cd99f06d7c1b8052c822992dc14.nq.gz
    ├── 170ed297684970ad7091b255170f3824f549d3cf.nq.gz
    ├── 17c06370d2e3f4de1fc97a31ec58311423b8dcb2.nq.gz
    ├── 17ef24d26c50d6186bdbaa69f79488738469f8f4.nq.gz
    ├── 1809df21f0b9942788a59b7903272635e68def6b.nq.gz
    ├── 1812b6fdee272dd155a3654a1e083c0f03e69892.nq.gz
    ├── 1861a822f2aedb90247847b47ec049c263456825.nq.gz
    ├── 18cd9a30aaff72fbf94269efd5b957007c69eba2.nq.gz
    ├── 19330500adc1c457ddaeb7b790a40e6092f5de39.nq.gz
    ├── 19390c7ec2bf866ac358a20cd36795bc3dd02084.nq.gz
    ├── 194e7ce8f388aaa49c7adc90dc95fd3724096381.nq.gz
    ├── 19b62fe7e063028446aaa49271a41d3b6c2357f2.nq.gz
    ├── 1a4c21330a5c5adf8604da502e8e11fec8d6863d.nq.gz
    ├── 1a8908295360c5d5336f69ffc025a7bf3f768246.nq.gz
    ├── 1aaa9c1bb3bd344a8855550ce85d4ee013f5d928.nq.gz
    ├── 1ae8689f975d61afb277bdf29d87f23a1403ff12.nq.gz
    ├── 1b464af6f332d9478f4be011bf3ec3ce09e4c18f.nq.gz
    ├── 1bc83a2309793bd5f0182dc341194e3f08f8e577.nq.gz
    ├── 1c06b66fe18a36db4d36a0c5b7772ebe9277d966.nq.gz
    ├── 1c4a9badbb43a115683dff863cbdac21d5cb09dc.nq.gz
    ├── 1c704b7457a12e6bab828ac19614178569550e6b.nq.gz
    ├── 1d3cc9f64fddafec2c6f20c6b5219f2a0f7505da.nq.gz
    ├── 1d74695f70b61c333a8a4cf1ff26658a88283734.nq.gz
    ├── 1dbb1e9b6fe05374b204f20e46903347313cb354.nq.gz
    ├── 1e4ad2904f5a0dcdc449fdd507310bbb44ad854b.nq.gz
    ├── 1f46f62708d921f754fa602da224099c8123d002.nq.gz
    ├── 1f892b5952224707e70adb808067f4506e2c70d3.nq.gz
    ├── 1fb5b797a7c05b3ef3d7b81336abaca3af9480a5.nq.gz
    ├── 1fe7ff2cdeb28aa6e899487dc91be01ff5e8d6bc.nq.gz
    ├── 2139f316ff835444655b0f020986b8fdfd7d7ed9.nq.gz
    ├── 21786a4eb08509738cd546ab3fe2bf7e029eec24.nq.gz
    ├── 22ccee9717332488ada6bef462eab9f4f6056b1e.nq.gz
    ├── 231d5a142d1354f70efa03186d87f1a357861740.nq.gz
    ├── 23d8288b731070d059fdddeae9f32ec7505b54ad.nq.gz
    ├── 24ba2fa997c016546e459ddf1a10f06c26f5cc90.nq.gz
    ├── 24df5446d712e0c7a4926ad24794b200abb9cce4.nq.gz
    ├── 24f3e0dbe1668c4c6ef5d9a8c29443901e9ead27.nq.gz
    ├── 2519009bfb56cffb0f3e3b1ceb28e985e0d296f5.nq.gz
    ├── 26c3945cac70e61a501762f2354a84bbfb8e0476.nq.gz
    ├── 26dce888fea416a0fad0da440091d3fdeb8460d3.nq.gz
    ├── 2703ba3f5b1320e0574362cefa249db269c5dcad.nq.gz
    ├── 279a954c78ea842600217801c03c9bec6b91a9a8.nq.gz
    ├── 288ef5f7179e5e534c2af5e23fe3ff0f9e1145f9.nq.gz
    ├── 2923d2596ecee37d81693983b4166b68947ac99a.nq.gz
    ├── 2ad29ecbfed66eba7af2d8e153da51c992316ece.nq.gz
    ├── 2ada205663ce9e0701027c0c574b21245c9e7640.nq.gz
    ├── 2aeb53849961934d67ff16f110613110a40a006c.nq.gz
    ├── 2c668d18322d98f363caefdc15397e283fc2ee5e.nq.gz
    ├── 2d0294eadec46d738c065f09388f021253ef59d4.nq.gz
    ├── 2daee77f36d28588ebaa2cd782c4373e513bbfec.nq.gz
    ├── 2e046bfbfb97f67b454462ae7d9ba01b2dd170c2.nq.gz
    ├── 2ef4be2e02a058155d9205a86b36ff1f25e67149.nq.gz
    ├── 2f6564afa858e0a21a3a7ba03982c17202d14017.nq.gz
    ├── 2fb21aff27b9489f93458592b2aa84c46ef5afad.nq.gz
    ├── 2fba65aeb3c4e60171ad6f1bc312303433b5e782.nq.gz
    ├── 307a4e4deca006228033bc3db7a331531164c198.nq.gz
    ├── 30e719c794b605545e2e31bb06c829c68ec88feb.nq.gz
    ├── 30f89759ee2b12815ad48c23ea3f15e699555925.nq.gz
    ├── 315bd5be8cd96033e1df2b66d47b3cd307f18f46.nq.gz
    ├── 31b836790f7c6fefbb4dc07b527ee99632ab6358.nq.gz
    ├── 32986c79287ade6066b1ddc4ff8e0fc690110744.nq.gz
    ├── 33065807ec346f3e3dcd42a21ad68da99949c1bd.nq.gz
    ├── 331e910e2adf90f54f026fc22e008009709019df.nq.gz
    ├── 335d2ecec7b75f7b68317c0f2886a6e4a1097371.nq.gz
    ├── 35041aa1b9657beb797f26c9b1bdce0ce88c71d4.nq.gz
    ├── 3595fb43f5c0b44f434d4b803476faa881eb063b.nq.gz
    ├── 35cf61cc89514fbc7ba693b87eff97a405225838.nq.gz
    ├── 35fa529231dc6df2cd4b4f92ee34fdfe1ca3e470.nq.gz
    ├── 3624ed0f36e699947b30e5b26a52877499271c19.nq.gz
    ├── 36e9984b9e2b567ef6d132d2eed56f3413969f22.nq.gz
    ├── 37f7129d06186c0fcfdc9d75ed55168fece90d2c.nq.gz
    ├── 3953e31625abf803a50f22fb5fdd221863882c44.nq.gz
    ├── 39dabb55db68215bfe6404b4a9a9a6ba7ab8d23e.nq.gz
    ├── 3a2bef632acd843a328d6ebaeae366b57c786a20.nq.gz
    ├── 3ae6e9ebe94d332f89fbc15a64b76b3876a86e13.nq.gz
    ├── 3be5304fc153786cd12992cae41b9b54c35885cb.nq.gz
    ├── 3cc4b8965a685115128493476da439950aae91b5.nq.gz
    ├── 3e6d5aacc5319632e890f1497e3f3c71f7bf5aaf.nq.gz
    ├── 3ea4b1aae6c74c5350389b1f35c236281eb3a9a2.nq.gz
    ├── 3ed912b5a4a89122a9857726421e9a91512e800a.nq.gz
    ├── 3f1f854301d5efc0b9c3cb609db7c5354db73ff0.nq.gz
    ├── 3f7eb66475892dae6c95ab827afcfec327b3c6a6.nq.gz
    ├── 3f8653f4bc9b0b3941d5e297e4b688dd8ef02849.nq.gz
    ├── 3fe20bec0f3aaccf5e2a0ac9e6649036723ca675.nq.gz
    ├── 409a83e8ed5f42de8e88857e4bdab1042f4b9464.nq.gz
    ├── 40b739b76ec5cf5c75cb929f6c98bc4245435392.nq.gz
    ├── 40e24882277e25249ef2728e3853229a8d4456a8.nq.gz
    ├── 41898432f6b94ba9a19da45f939f2100dae38de9.nq.gz
    ├── 4209048205a534f883ea5b105f8bf2411e45594c.nq.gz
    ├── 42b5bdc6a15249e40608fd47468b83d7e5e55612.nq.gz
    ├── 43bf4e1b397f10a51ba39e745c8c3bf5ec0bd414.nq.gz
    ├── 441385536ce0ab20983a961144693da37297013f.nq.gz
    ├── 46b5937139ebf5c25ca9a2ff51910d1e636c0bae.nq.gz
    ├── 48f79699706e1ea990af459b1f33cea134830589.nq.gz
    ├── 49f5406ab4afc8d6bde86da6755b19d31c81786a.nq.gz
    ├── 4a6771c4639b7b35aa4592878657015922ef2136.nq.gz
    ├── 4aa872fa42bfa9fd6e47ec79051f804eb8aaaa88.nq.gz
    ├── 4bf0bb49c127298a4e9c49a5724ee3951d18af5e.nq.gz
    ├── 4bfd306cd6455ec3d676c7c61dc931224bbf678a.nq.gz
    ├── 4cb76be8eae75e0a51cfbd564ee018e922ff3b37.nq.gz
    ├── 4cda6596516ca5ca5b48bc80c30888dc972c7fe5.nq.gz
    ├── 4dd0d9296c8ed962d2fe3601b055b93d109f8a39.nq.gz
    ├── 4e53236e39e7633c8e8d5a7c1a47bd5a8b2b9150.nq.gz
    ├── 4ef99fd865a1819e37461b3693b3db9ddd5a940c.nq.gz
    ├── 4f481cbe92499b2acdc355984469d9b3a468367f.nq.gz
    ├── 4f6c02452e1c8548ad5e4dada27ebd36d9f8fd0d.nq.gz
    ├── 4fbd93bb2ca4d982f578388ee47499e8a421f50e.nq.gz
    ├── 4fcc3dcd8ed1f3034aff7986e29e01a87a6913ca.nq.gz
    ├── 4fd239765b0a4d65cad121c57adeb33c3a894fe8.nq.gz
    ├── 5070a199bc58842dd6364fa0a6596d7e6025dbc4.nq.gz
    ├── 507201872cc1d16cd5bc53b6cea81ce8faf507f8.nq.gz
    ├── 509b8951bd612e56df4c30668e2cbe28ccfcbf53.nq.gz
    ├── 50c9730246b8462f01ec193adce1f38ce283dd25.nq.gz
    ├── 50fec964973212c5b45fe3dd407b44f8b1f707ad.nq.gz
    ├── 520545493290fe80a5b878b54d365517c79fbda5.nq.gz
    ├── 5260e52464740275dafccb10d57ec341db0c0c19.nq.gz
    ├── 549d67f761faa3e64f7917651a791ac26405c866.nq.gz
    ├── 54c8886cd30eeef97c1d192eadd947340b2026d8.nq.gz
    ├── 550724076ba532f9def831e94495072195464583.nq.gz
    ├── 550a6779256ce5ab62591bdedcb40077db875e9d.nq.gz
    ├── 5541a6738ded21328e5ab888191ee975ea841989.nq.gz
    ├── 55486a39a2de49984c975147a7d584bd61b49b3d.nq.gz
    ├── 56696f8689caebc519aa73435ad96f34bbe4a60a.nq.gz
    ├── 56be8497e4c288f69ed19702946052827e1db558.nq.gz
    ├── 57132a1b99b5f925f5709efce46103b03530aeab.nq.gz
    ├── 5750c7a9890e84ea9c84abaad1b29473500bcab8.nq.gz
    ├── 57608968a3fac13f2f259a5b4ca9b4e8aff26b6c.nq.gz
    ├── 57bca074a7cd453513520a9873f2e36649d590ba.nq.gz
    ├── 58d56ce743c954742d665cd6ffd40c852c7e1860.nq.gz
    ├── 5aa01bab5bf33a147bb3ec37eaa7c8a528c1a711.nq.gz
    ├── 5ae345247e4c304324942df00b51f468ed8329d0.nq.gz
    ├── 5b5339350a60846ae3a832140e19dc40f077f169.nq.gz
    ├── 5b8cbe1c357975e96893df055510e5c712f8a8f4.nq.gz
    ├── 5ba5622e8618a5ee910fc6b8a3d79f25ca7c7c32.nq.gz
    ├── 5c52aeed64707225702e459dd6cf555bba3aeae4.nq.gz
    ├── 5c55e278e0fede97ada5d1d5c249a81bf2a77adf.nq.gz
    ├── 5d55860ccec3ca0003b532b9665aebe018695c13.nq.gz
    ├── 5d64b9d2f2562704d0b009821e0ede521fc34dd5.nq.gz
    ├── 5d7991c91af7f9923d4c5ee09433686eab549eac.nq.gz
    ├── 5ea33d18c00cfa606b49e4a3be879925d7896885.nq.gz
    ├── 5eea993ced9ba3f549efaf05e573ae12a7fc01df.nq.gz
    ├── 5f4d686b358a48124dd76cb3d4dc1178675fc1de.nq.gz
    ├── 5f8650b2b9a76af6fa5fbbd621c6b2642f47687b.nq.gz
    ├── 5fce08d62afe40ce62a685a834e19bf64cf28c4d.nq.gz
    ├── 603d142f25a6aade595f607ce4fb24959fe969a3.nq.gz
    ├── 604e5ed2e4bfe7e1b0f4bf443217561785383bf9.nq.gz
    ├── 604e7f730312ecf7e21cef5c4450e92ea257e906.nq.gz
    ├── 61df76aaae07bccfed632ce35974199d73fada82.nq.gz
    ├── 62e0d540c91c930b52cdf1342e2dc224d69177c5.nq.gz
    ├── 630d8d0bf61ccb93d7cd1dc3758f4dc7aecb951e.nq.gz
    ├── 6321aea35101db90f32a020afc7ed41308a29a57.nq.gz
    ├── 6365857f33c6c4c98eb292cf87dcfa000b301fb9.nq.gz
    ├── 642c18d15c114dfa9165ed918fe1ec4ab0768604.nq.gz
    ├── 64d8b1451e79bf10927e5d0e1e8456885bac68ec.nq.gz
    ├── 64ec39b7603cef0f9b850397f94ebf2d85ebe50e.nq.gz
    ├── 6598baee77e10ced18aea18c908f8eaa38f1c5d0.nq.gz
    ├── 65ceeeb5e4904afb48a75df5c91c7985626a9885.nq.gz
    └── 670eb7ccfaf84813786059d5966f35f34fda8f8a.nq.gz

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

[googleapis/python-bigquery](https://github.com/googleapis/python-bigquery)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
