# Repolex Knowledge Graph of tfranzel/drf-spectacular

RDF knowledge graph data for [tfranzel/drf-spectacular](https://github.com/tfranzel/drf-spectacular), parsed by [repolex](https://repolex.ai).

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
rlex download tfranzel/drf-spectacular
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1a5c44a15b2d06744f49285f1f58992f938a05fa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1a5c44a15b2d06744f49285f1f58992f938a05fa
│           └── chunk-001.nq.gz
├── blob
│   ├── 00181d123bda247d31449359cb5b819884a01da9.nq.gz
│   ├── 04090dcf270701d60b51cba39a272694d8bea148.nq.gz
│   ├── 041772b113b571c18fa51d2dacc3fd7753d0af5f.nq.gz
│   ├── 04f5f0e79d768697c338c6278807a9cde4dadcdd.nq.gz
│   ├── 0555eec6c8a4c943048f783ceb0530cd467f8830.nq.gz
│   ├── 059237c81c95030e391adfe8375323c30ca9c669.nq.gz
│   ├── 075faedbf111cc92350f92c042571704014e010c.nq.gz
│   ├── 0839474e4937fab4642205c17d61e8655f2728cf.nq.gz
│   ├── 090a7fec19131a2285d5e6ef8b6ac5573b3a66b9.nq.gz
│   ├── 096b8a74613c200866ae271b3a97ccef698ef552.nq.gz
│   ├── 09a5ce8270054927d8796daa581d485af6351722.nq.gz
│   ├── 09c6192cc6ff4fdaf633332324dfb0c24d59811d.nq.gz
│   ├── 0bd9f857ac27fa21e4647acdcda14a097191929f.nq.gz
│   ├── 0c9b954efc61c52ae5c3e781d5d356a38137bce4.nq.gz
│   ├── 0d28276c79915bd1c66175c88012dc377e9bc938.nq.gz
│   ├── 0e1eb53f3562b91580f12444abc59b8f3e67f5e2.nq.gz
│   ├── 10c6489ed3fd9f0c92b03279aa953d948f59ffa1.nq.gz
│   ├── 117b168cb0925c2d7c0b4a4165f568012f13f418.nq.gz
│   ├── 123ec41dc06f39316a0270fd91bed22bdef33154.nq.gz
│   ├── 130f1744919cd59a043788e0ee3bbf422c01b0a0.nq.gz
│   ├── 13153a8218b4c52dafd834e902f52307fa213dc3.nq.gz
│   ├── 13e46e6c22a8a41c79f8d3cce63597c54f0c262e.nq.gz
│   ├── 1649344f1ca4e2e86766b490e46e759dcd67ad8b.nq.gz
│   ├── 16f11d701ca44a34200d4fc1b92c0f8ec012e168.nq.gz
│   ├── 17575225e6e4f995e8051933c71ad916f1a1f35b.nq.gz
│   ├── 19387d901fbfeb964b863866b3b704fccb75b74e.nq.gz
│   ├── 19729e0499e16d6a32444ed08c4718260c736d55.nq.gz
│   ├── 1b5446e34b32aac76234ecf12d26200780fee1c6.nq.gz
│   ├── 1bc015f1b1d410f954b141966b357cc76b4f6e45.nq.gz
│   ├── 1e5067d670fd0e54fb17f2a690e1c69fdb72744c.nq.gz
│   ├── 1f2ca7ccd557b086e534b7f86cbdc5946ab6dd8d.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 21e82fa264bdeb04a0bfeb803a04f48c0ef0cdd6.nq.gz
│   ├── 220e55da8bb40942b3d3ae6a0a0b51a1eb0c68d3.nq.gz
│   ├── 263075b5bfc56da931373a1d2d63060d81b82b64.nq.gz
│   ├── 2754e2590b8b3f508d3171969e7a2f81beb88548.nq.gz
│   ├── 2931b1ed7864da7455adff56fda0b3a38e41f366.nq.gz
│   ├── 2937b76036a2540ae7b2b3becaefbfc397746e33.nq.gz
│   ├── 2af2fdc5b8ce871a09f1fd2e54233626145b9e0b.nq.gz
│   ├── 2b9a05b2b764567a01ae6305f84fb6662f4035a3.nq.gz
│   ├── 2ca61fbd5e544bd0368371980562aaca21d74199.nq.gz
│   ├── 2d48aeb6cb06298db56cae7e1471549f101ff90c.nq.gz
│   ├── 2d60ea012e89eeb60c5777880a84b24f64a19fe8.nq.gz
│   ├── 33ade7f37e6c255088f3c0b2c6bef112818d8710.nq.gz
│   ├── 35988edc6ad048658bcd8159249a33a4846fcb58.nq.gz
│   ├── 395a8a9ad98562d2b82d0bb3b1fa675477313f66.nq.gz
│   ├── 3af900bb2a6053aeddfc0ec677b03ead0e720d28.nq.gz
│   ├── 3d3846754e93f2121533ea5a75c72fde01ce4298.nq.gz
│   ├── 3d7663ff189ad5a0d2d0f208292e2b8713af3134.nq.gz
│   ├── 3f6d059f04f8c0d9d63e981f48490ed7a8f16cc8.nq.gz
│   ├── 403c4a6d739182390580eb48d1e755705dbc97f5.nq.gz
│   ├── 4217a3f2d487d0b7ed8c6043aa45c2d4a0107022.nq.gz
│   ├── 4411c233a52e6eed3abdc1d908a9d7beafdd2052.nq.gz
│   ├── 460d42b9ddc2a6fe48c92ee51b2856ab1bcf2fc1.nq.gz
│   ├── 48710f669800d53e4d2e4073cf806deb36714d8d.nq.gz
│   ├── 4caa2d1cb446e7f68481cd1efc70030114ed292e.nq.gz
│   ├── 4d6d06f6ef7909d41c8d0c93fa74a89e85b3df47.nq.gz
│   ├── 4dc0eb5d42e682268541a989e2b6b1347cf99b5f.nq.gz
│   ├── 4e3464af25e68ac9d10a06e2b667bb879807651e.nq.gz
│   ├── 517cf2608b6d6b55ca8c624ff6dd4ce62cf45d47.nq.gz
│   ├── 52be567d57728c36a92bde94d4dcc2cd7b8560d5.nq.gz
│   ├── 552424bba46fb2e6bcfae1857f4ccf0742f90421.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 56924c8c809dcfbf7dd7b4f7c97a0911863302e1.nq.gz
│   ├── 5721abe7937018926fafde686c10fa06e6ffc3a9.nq.gz
│   ├── 5ad5c3e9744ee2806c5638de02774c5c5ded303b.nq.gz
│   ├── 5af5df55f13343946ee95734cef70ab07cdae86d.nq.gz
│   ├── 5c5165f7848b87269383191f326449b94e4551a9.nq.gz
│   ├── 5ccb0b100b3373ea107236612a974221daf52932.nq.gz
│   ├── 6216465a8944a6b254ed2b3183939407e0c39895.nq.gz
│   ├── 62f51ea420e89d2e31317ffd42c3550010756743.nq.gz
│   ├── 646f15c8681bf166d7f8ae3cdce5966150649083.nq.gz
│   ├── 64e4f808cc587fbbe0d7e46ee846eda554b658e7.nq.gz
│   ├── 65c8b4061a9d173cdb3b17bbd09f004d5d85c0ae.nq.gz
│   ├── 673c4eaeee65f7ebadeae753b81415169c352f32.nq.gz
│   ├── 68e2395948f91c702e2c4a275ab1b892aec524c0.nq.gz
│   ├── 69dbf7a5e3ab2a2552c1418e74d14a54afd1fc47.nq.gz
│   ├── 6cb1b8c6d99f7ebfce09e09e10192019677136af.nq.gz
│   ├── 6cb8077893d9462d4bac4e742942ac91ad426730.nq.gz
│   ├── 6dda335d24ee9342efdbb15fdb9251791d3a850c.nq.gz
│   ├── 6e8eab891481ccf1f27409377dcdefc4ca571979.nq.gz
│   ├── 6e99874c7a9a611e66d1cc96cf74efec49a3132a.nq.gz
│   ├── 6f8bb349118bdb00c750964665c4e974d02151d7.nq.gz
│   ├── 703308df572f7db772195463c9f07e3da010fed1.nq.gz
│   ├── 7454c418865a2bc08e5628f5657cc203ade4a8aa.nq.gz
│   ├── 74ec8978cd09d65aa8d434f9d085dae2fa55d5f9.nq.gz
│   ├── 75b2496a8d166669bb789967d59807a0b12d5426.nq.gz
│   ├── 76001f6264a3b7b267ce2acb7052d3f702180eef.nq.gz
│   ├── 788ffac92a7bb3d75989158750b97950cceffb06.nq.gz
│   ├── 7ac300b6b09df3ec347f29b32c4a3e13ba7d9d7c.nq.gz
│   ├── 7c44890b0caa6d6135d64baa6b23783ffed28b5a.nq.gz
│   ├── 7d9ee72b4698896e3856dbf08bd209a9c6d1abe5.nq.gz
│   ├── 7e18cffd600ca713dd3e4ff318fb4206ca21f2af.nq.gz
│   ├── 7e67ba274c313396981503e68c839d8f6150892f.nq.gz
│   ├── 7f194c6673705f02670c5fa9e1049b5e1feeffe2.nq.gz
│   ├── 7f60d5c5345aba13682658a0fb1b6ffe50ebcd32.nq.gz
│   ├── 7fc79541013aceb19eff36cb75aab493568b410b.nq.gz
│   ├── 804f127c90c6f35b75f79157c029d88211f74c2b.nq.gz
│   ├── 80fc2675a62be0dd39d9ad27f0b3234a330195c5.nq.gz
│   ├── 8228f8e347879db12178aa79c1765bd97a73849d.nq.gz
│   ├── 836fc6cac97e8d1af2d52ce09ebe9110fad97613.nq.gz
│   ├── 83ff6f9a8207973222f46a88edb4d9b674e144a3.nq.gz
│   ├── 874a99d0facfc3d90d26e2db81104b618c06151e.nq.gz
│   ├── 8834b49df58963b853983563799dc9610a148cb8.nq.gz
│   ├── 89016826d3772f6e95040fb05a6c3c63d364b618.nq.gz
│   ├── 8b98f8ac1a895e56cb1c1f1dc5d045f64d0c7e71.nq.gz
│   ├── 8f3cf1fb7bcd7c0b4461f0bda1841b90ff8c1a49.nq.gz
│   ├── 9069c66967a0c61cced92cc50b3c9aa10a2578fd.nq.gz
│   ├── 94e7eb6d32a87c52a6ce6a94d51813613a5b4ec2.nq.gz
│   ├── 95a8adee0de4ca7fb81dfc50e4368f49cca20bcc.nq.gz
│   ├── 971658355d086bc8d45bebebd5c74a6b41809899.nq.gz
│   ├── 97c5742ead1c994c47a2f461df0a8a58976c06fa.nq.gz
│   ├── 98282fe4162511214e4bbc4b79518bd3998fd69c.nq.gz
│   ├── 98edb2edec0173191ab5169f33b208430b7d9269.nq.gz
│   ├── 99d14cdbd5dd6587b59b3630776f26e58ee7f668.nq.gz
│   ├── 9b40c1d780019d6eab501a97365d93cd50092bbd.nq.gz
│   ├── 9c2d2bd737b594fc2a84be8967a790198a2dff00.nq.gz
│   ├── 9e1de0428c8afbc708ce91a2bef86a83c3425ebe.nq.gz
│   ├── 9f3af9c26645cdf04080d304d1e242bbb41497fd.nq.gz
│   ├── a3ebfc6a9e32c0d57e92e16856e99d3853601845.nq.gz
│   ├── a423d9ed02d24db6207351acd9ba59728f27a6e7.nq.gz
│   ├── a67c4f554c6f5f61ead15d89946484240a6ecb78.nq.gz
│   ├── a77c0a22ce9c02a4ad64a4dbd20d55a0792b7477.nq.gz
│   ├── ab6557431efd51f86bd4aec85f596e53f86a9984.nq.gz
│   ├── aba844b041edeab265d6258d4276bbe3a9620e5a.nq.gz
│   ├── ae24ae4fabe6aa2c7d21c5b9db3b54168b28d96f.nq.gz
│   ├── afd272521ef9ea22d10a0f1a4635e542095b996f.nq.gz
│   ├── b058b13e8135aa513daa619c840fad19f80d8f79.nq.gz
│   ├── b2242422a611b434609cdbbfc2b7cd26fa1c2055.nq.gz
│   ├── b358b49a57bf5e8a60b2ebcae147e8003ef44319.nq.gz
│   ├── b81abbe40958f4390ad96e77fe55e37ffcdd2b23.nq.gz
│   ├── ba553ffcb152c9796353f4b2c416b8aff2e6629c.nq.gz
│   ├── be4e5add32bcb27b1502ceaa646062d3aebcd0e7.nq.gz
│   ├── bf2d6813a9d9bef1de762410b2b2afde507aaef7.nq.gz
│   ├── bf3a9697ea3c5dfe76b9a8164cd9d442f1e143d5.nq.gz
│   ├── bfe8b33801487a2ade786953c0ba6fd292b01cd6.nq.gz
│   ├── c051ae748c02becfd4a3c865e427fbcd3b21cae3.nq.gz
│   ├── c1627a9e16449b4aed0a829b813ecd7e3bd2aed7.nq.gz
│   ├── c1c8c2df9a63cfd172e63bd2190cdb8dff09ff92.nq.gz
│   ├── c29b28b66dd7577461ac25966d4d19ef2666caf3.nq.gz
│   ├── c47489cd3e1a904b18d623d19356a35fcc20fd6b.nq.gz
│   ├── c4fdaf78bed5659f4d8d8f590878929640e78714.nq.gz
│   ├── c80ed677bd63811640106211352d590d7e3bb863.nq.gz
│   ├── d2205312788a7b3ec87c60f0c291084c25c6a7a1.nq.gz
│   ├── d2465e8f0a197e17547d0e8635e03153abba3b2f.nq.gz
│   ├── d32c10e14aa08c3eb806cf0ac8c39cacf9a3a0cb.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d60c509fa44170a502be741cb476d13fb17045f6.nq.gz
│   ├── d83340c2a8897a68c891d9a9ec263c8255dfa456.nq.gz
│   ├── d8410ff36fcb9ca5fd9e462410df7640eb135ae4.nq.gz
│   ├── dc1d5b8dd6ec0d12f72035d32a130361e1c20b94.nq.gz
│   ├── dc5eb4ed75b8e6c2e3fb82ea46a04eef32784779.nq.gz
│   ├── dcacc96e9e57addadb30aee9919a1454da98566b.nq.gz
│   ├── dfde5262c3dc1c8a74d2fddae531fa79036bfdd1.nq.gz
│   ├── e2890665db78539ae3853f33811ba09cccad4e4c.nq.gz
│   ├── e330288dcd1b351f9b4a9bac200e3c36c5f6deb7.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7f87af0b9fd4219788d4bbe781e9939679a3a52.nq.gz
│   ├── e9fd1606d67a1a63495b96daf46959888875c02d.nq.gz
│   ├── eb2ba8bf5419c88d511d134b55074f169c77ef65.nq.gz
│   ├── eb828cda77c1535fcc43a6e279b777015348295f.nq.gz
│   ├── eb84dc984a1ace2e66e3d2e79fcc53170150a49e.nq.gz
│   ├── ec52e28b3c084fe5a5670db5a2b0706de36fec81.nq.gz
│   ├── ec7c24aedf2da6af4e9a0f149e17f73cdc152892.nq.gz
│   ├── ed17c1001c6d3a4417f38b3231fb9275f5a94616.nq.gz
│   ├── edb462d89fe981964fc97c95e38be510ee59eb65.nq.gz
│   ├── edf43951d6aac78e0a9595fc2db07554edcdc9a3.nq.gz
│   ├── ef4fdade1da2c42b12e60b043fb3f24797e3a33b.nq.gz
│   ├── efaed6697e79c62ac0b9b83db07f79d875647bec.nq.gz
│   ├── f1e085c8ca8c0494497e392f3b8e2bb3068ae69a.nq.gz
│   ├── f1f7ecdc86cbb80635faeb941da4a2a3e2fc2a01.nq.gz
│   ├── f25e7f6aa1c28ba118fb3389f71d0a1bd40be9aa.nq.gz
│   ├── f7a9f14c162d9240f66df19a70768f26ec30359f.nq.gz
│   ├── fc225bca19043f21eafef66e29f3a1f004684ab9.nq.gz
│   ├── fd68e0df92a544944d3bf35f8a4d455646fecd78.nq.gz
│   └── fff111101ec57ada6cc8535e040b2ed4518d5f09.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1a5c44a15b2d06744f49285f1f58992f938a05fa.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 185 files
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

[tfranzel/drf-spectacular](https://github.com/tfranzel/drf-spectacular)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
