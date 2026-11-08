# Repolex Knowledge Graph of allenai/EMO

RDF knowledge graph data for [allenai/EMO](https://github.com/allenai/EMO), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/EMO
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 246fdec72e599319c717aefe29a1d1fdad7c97a0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 246fdec72e599319c717aefe29a1d1fdad7c97a0
│           └── chunk-001.nq.gz
└── blob
    ├── 0051ff4f320e3c83d851ffad913ee8c84ec5c4b9.nq.gz
    ├── 00bc4551e7c8c901ba9b5d1b1b82ecbc706ea3a3.nq.gz
    ├── 01c8d0fc43e6d3791181b2f4f033d4d093ad4182.nq.gz
    ├── 025e61bba2629571d57f6a6270b31166aabd43a0.nq.gz
    ├── 02c8b489c22b15c2b5bc228bec271d6378d44f39.nq.gz
    ├── 02d5464a3931c61d5ff23ec846d9556faa5ec9e7.nq.gz
    ├── 03675874bcd752e5e546ada0112d2cad5f8be536.nq.gz
    ├── 03dad8370c646779b11ef9727a71d0dbba6830df.nq.gz
    ├── 0400012ce4b72359a73a104f1667f7ca2f591ccf.nq.gz
    ├── 04ad9f3292a6c84a8a8addd90f1fdc182d05d975.nq.gz
    ├── 0535382c8aef288b2aa496f325a713d17fa86925.nq.gz
    ├── 06115080999e4dc53c6dc797570b922a323d32ff.nq.gz
    ├── 066afa4093ff0d96e090e368671f36493f555196.nq.gz
    ├── 06c4fd61b28a950c4527e567520f5203f1acc96e.nq.gz
    ├── 07272f5d5e60467776244155a273ea858f7fb66b.nq.gz
    ├── 075a3da11fdee7f04413f52280f4ab6dac4e6ae8.nq.gz
    ├── 07e63bbbff398f6625fece4ae00ec06bc6a178e1.nq.gz
    ├── 0848c9f4b1a97ed9d7e9d59b11b3dee3c686803f.nq.gz
    ├── 09eb545603c07d9c42b698148e8d27da26d8bbe5.nq.gz
    ├── 0af238facc1f911a5ccee6a8d2062eff8f7a21cc.nq.gz
    ├── 0b57b55221f57f00201a99a1363438a24824a3e8.nq.gz
    ├── 0b8932abf850818a1584573dec775df6c3288485.nq.gz
    ├── 0c1b430df40dd83f3a636ce02295623110faed89.nq.gz
    ├── 0c287ffed34ce4caf2c0bed894bb53168815cf8b.nq.gz
    ├── 0c6d4a79976537303f94d8e30228a37fb24c644c.nq.gz
    ├── 0d04bfbfdb24b69707c089b688de466c484d2a2c.nq.gz
    ├── 0d46b46ee6f4642ac872b0c3d41693c697fe4370.nq.gz
    ├── 0d578647e56f068d21fa0613230f866860bdc578.nq.gz
    ├── 0d5e66a487664168be13120ceeed54c135ff661c.nq.gz
    ├── 0df91166c5ecdae4ac5cec0c74965b5f386a3258.nq.gz
    ├── 0e03158adc6a62e83caab4acc6e782effe1917a0.nq.gz
    ├── 0ecf4d743671fb7cf9c052fa542e423a8d296465.nq.gz
    ├── 0edd0576f399a22efa48614fad562c556db1197c.nq.gz
    ├── 0efaf4c78fa885f97b391d81539cb4935a7fd884.nq.gz
    ├── 0f4fd9a196af4450ffb1e95b7367dbac3b7759c3.nq.gz
    ├── 0ffa82d7f74f218372b6b0e4d947c47590212afa.nq.gz
    ├── 10317e15645ff81ccc2c6911703e72dcc63e2bcd.nq.gz
    ├── 113443c65e84f49062834a0f364374ae20d19a5f.nq.gz
    ├── 11f07a88eae69ceb6619970f59715805c73b02c4.nq.gz
    ├── 1276c41a4d52d02d6406ea999245ef847095cb52.nq.gz
    ├── 14358a2553d1ba156b3aaa61546266adea009f93.nq.gz
    ├── 14467a0c815c575c07560b400a59e886cea21098.nq.gz
    ├── 158372bf201f29c78da95ece0028ba1f9240a39d.nq.gz
    ├── 15f54889b400bcd11e1043bdbf1ab3d7b781d393.nq.gz
    ├── 166dc6677926e20710702337dad501c77e1161b0.nq.gz
    ├── 16f6c9b601a854edb95dafd3822a6e0380c33580.nq.gz
    ├── 173f7c4b9d4bda6c15d52ee2ba32624078b3b6ab.nq.gz
    ├── 174ca6b3d89f2b0a6145e30ad8aedf681819d4fe.nq.gz
    ├── 175b47dc720336fdb9d6148638da7702b0961a0f.nq.gz
    ├── 179f6d9e5dce57b310a2c083007693833b58f027.nq.gz
    ├── 180b328eeded1efb6d4db1203fb854498e839f29.nq.gz
    ├── 191aa767079a95453a240f76f5c01f0cc3e6eb2b.nq.gz
    ├── 1928d7afa38f4892336b35f1b9586a58341231bf.nq.gz
    ├── 19480cdfe9cceabd688c4a41eea662fa70a1f4da.nq.gz
    ├── 194d9bee09db6a82c55a2f65e1f1f292be6dfb42.nq.gz
    ├── 1966beaac399c9f89f1b476a790898115da461d2.nq.gz
    ├── 1a80666834b734de6b9e9de08c633af23395e07f.nq.gz
    ├── 1adaebc7918d307764307a5fafeea17fba0e0105.nq.gz
    ├── 1bd3e3697625e8abf46d279de76d7560a4811612.nq.gz
    ├── 1be35d88031d595f0943b3d57458359a8b2fb4d3.nq.gz
    ├── 1c2b505329683e0b44e1d0791a43f64a2c12a041.nq.gz
    ├── 1c8ef1141525aedcd8f87477c3f86a2bd0f34203.nq.gz
    ├── 1d09dbab3309156c02eeccf8ba73c25032a3bf1e.nq.gz
    ├── 1d78fa8ddd616fc25eec2cf427a3c8d3202e56d8.nq.gz
    ├── 1ec573d24559f1f1133f36593ae9f46c2b1f6c2b.nq.gz
    ├── 1f4c8bb762ae31915f9b6813d6a98c1af3414dde.nq.gz
    ├── 1fe9efbbcfce8407517177aafec65475863339da.nq.gz
    ├── 201e79411e8178184627341e4f3af564b79789cc.nq.gz
    ├── 216633f5eb1a778d7a09b545fb12c33b914b40bc.nq.gz
    ├── 22ee8f95a8ba6cd20c15c4653cd5a96f3895b4ca.nq.gz
    ├── 23ada0b3ed59793adccebd69bbd11fdc700a9e52.nq.gz
    ├── 24120c315a1aaec2a174c52b61490711c4763c5f.nq.gz
    ├── 24c06577b1abaf695763ebbf1cd5404fc0857629.nq.gz
    ├── 24f18962aff4b95f069262e58c4e27ab5c87d998.nq.gz
    ├── 2506d425423722a50165d9ed705105ae0bba0496.nq.gz
    ├── 2513019fef6f152a20bdf337ad41a6131323faee.nq.gz
    ├── 27c66c6b801195aace99c6d402f5ba0e3269d8ec.nq.gz
    ├── 27d40e14d8e6911267931738ad0953ed5799ba44.nq.gz
    ├── 27eb690694e7a1a9faaae06fe3f3f9863ae935a5.nq.gz
    ├── 28006375c7885d09852304908a7ae5cbdb19f377.nq.gz
    ├── 283fcf6c6218f2dfb0fc3dab7325639b6631e34f.nq.gz
    ├── 28f7ad5d4670c7e50344b30424cc924fd75f61f1.nq.gz
    ├── 29d1309a0d6896fdb38a8014594bb4dcfa9ed391.nq.gz
    ├── 2a5617491dca8f5eedd224c6459c429bd14eb35c.nq.gz
    ├── 2a8a8da78609f1519ed0c1903379e2c4695984d5.nq.gz
    ├── 2c47dfd6892b0caf15859d5ebbb96d47f8b2804e.nq.gz
    ├── 2c96101f1b064cadb1ef52d77e89fad00261f65d.nq.gz
    ├── 2d7cb2b826248aed8eb9654dbca555440777fdb3.nq.gz
    ├── 2dc01c244ff55c982f0891236e7ea8abf9e68660.nq.gz
    ├── 2dc5d5350b95dbc3ad1e314f2b6a3f48d051d1e4.nq.gz
    ├── 2ea048e5cdfe0dc136c95f7e3f374b4dd811a48c.nq.gz
    ├── 2eaee2be0d42622a0ab4ed25ffe7fc29c6d00506.nq.gz
    ├── 2ee616716b62f5d38221545d57d1bf984d3b6270.nq.gz
    ├── 2f0d33bfe18cd93d7e824e907ffbd518cf255d09.nq.gz
    ├── 2f199b0081e784e724948daebfadfecf9fe01be3.nq.gz
    ├── 2f27786dbf9ec649340bd08bd492d5c85d2c2a43.nq.gz
    ├── 302511156568e4ea4d47b30903cd65cbae9daed6.nq.gz
    ├── 325ba78eb8f0f91a33d61276fa7d6510ec52e009.nq.gz
    ├── 33a5d2509d0ea636ee98d475e073effe30613ef0.nq.gz
    ├── 34558df03d9394d92b27f9656c95051e2d49d085.nq.gz
    ├── 354bd6463d2918aa8f43f91a90dc1880ca1dc85b.nq.gz
    ├── 35512445efc34ef57c3cf8c1ce241fc17f5e1b46.nq.gz
    ├── 35f467d94f9a1e15ca167034ac4926562f7a532e.nq.gz
    ├── 36b78eb2dc7e964d7c22708da0be076c4abb3711.nq.gz
    ├── 371786126095f63d41fc44a25609fb0f33dde80e.nq.gz
    ├── 375f12430244c8747cc6f35bd990b9ca594da9d2.nq.gz
    ├── 38bf2b42016cdac803c225fea123dca58d1113f8.nq.gz
    ├── 38f69946be3fd2c9c2463dd6e9f0d855edfe6eb7.nq.gz
    ├── 3951dd04bbab4c062fa8afe3f679ddc1d2e6e177.nq.gz
    ├── 39a3ca64542c51c18c088ab9857c06034a10a5b0.nq.gz
    ├── 39ed668e97b2a9d9bc43cb76ac7363092fc33d82.nq.gz
    ├── 3a51c1c17d35c6f71d7592eadcc38977f1c8b13c.nq.gz
    ├── 3b896de1e42959264ebe93667fb25e8f95a397a4.nq.gz
    ├── 3bd2390b5fb52c6d3270b48ca6de3ca357499e86.nq.gz
    ├── 3bd68f714245fdc8254e838620f1966b10e61311.nq.gz
    ├── 3c451707177341dc0b83dd66211cddce061ddc4c.nq.gz
    ├── 3cb0d326d88e61f390d2e20237063579f1b5f6ac.nq.gz
    ├── 3cb0ee0e3c78395404217abf65974e785b1d48e9.nq.gz
    ├── 3d0cfc241402cb9a3d6a7f44d8817f0a716d4427.nq.gz
    ├── 3d4d3b43a0f466315518764e127be8e258bee16c.nq.gz
    ├── 3da05599518b70d99812d74cb84167a5c905401b.nq.gz
    ├── 3e5fd78091453f1c3f6cfbecf63fb651864b0be0.nq.gz
    ├── 3e6ecf72efc3bed71f501c16f55efb33c9386b06.nq.gz
    ├── 3f3bab402e087f4ed0ec1b6a21ba254558e8751a.nq.gz
    ├── 3f44eba88568f9e615ec8cc43afe3cd536c37650.nq.gz
    ├── 3f538ad48dd02127f883e4c6c1cbc434ef2f5d7c.nq.gz
    ├── 3f5f9a8edc6eeaecfe85dad86672c173aa2fbd67.nq.gz
    ├── 3fd3a331f61be9204dd3dc565b7c94ae91ea7b20.nq.gz
    ├── 4026daf2d738bf5dcfd167b503fabf3b4fee2dc5.nq.gz
    ├── 402bbc4c0c8b153ec193c9838e9f48689aa56140.nq.gz
    ├── 40a799956e8882571fb02598171a13808cbf0a21.nq.gz
    ├── 40c69fe1a02221e33bf1360b5dd13043f2dcd01a.nq.gz
    ├── 40f2054b4261dcfa294812321aa1ad6486474664.nq.gz
    ├── 40fb5f453ca5a83a987ee996a00851a23fca62fb.nq.gz
    ├── 419509fc0a26fa757899f5de6d54cee0ea215e54.nq.gz
    ├── 41ad00e2b99081cdab0c7dfcfacc8876acb94ece.nq.gz
    ├── 4233f7798ba00c3102945a27c70ea63d64acdec8.nq.gz
    ├── 4260538ec46e98aa71aa2c3e7d7763fee5c1fa30.nq.gz
    ├── 42816c551ef256bdf65ba10f2b75f826344143f0.nq.gz
    ├── 4281d140ff8a2da74eeb2c182e52ea3a7f6f08df.nq.gz
    ├── 42b994c5b539ec319def4ef461cb908c192008e3.nq.gz
    ├── 42c497dd6742c0f9cb19ffd362c9fac9a9b45484.nq.gz
    ├── 43842029b09b3b879c35c5d4dfe9d2d6b6bcdec6.nq.gz
    ├── 446ef03c883d93fd92946a04b88b871dd9bf739d.nq.gz
    ├── 46201ff63ef747660027f4813e38b0ec5823e22f.nq.gz
    ├── 464c415e70111e4222d77a79c0cb1c028702e316.nq.gz
    ├── 472ac8ded1d3c3ba0b13b114cab327d375aa78a0.nq.gz
    ├── 487a9b66dfd2d5310c3c683ae76332b2919150a4.nq.gz
    ├── 48d0ad9b8c7aa4a0783274c682a93bec05ce8917.nq.gz
    ├── 492545d23c222d93bc210b3f4d097d544f5d4735.nq.gz
    ├── 492d5e88fb6f3a2a134f5e9da36f96564ca3cd77.nq.gz
    ├── 496e8cdf6c757464ae15e38d7e6baeb6dbb40f7d.nq.gz
    ├── 49719885072941e76ad33a4e21caffdc54490326.nq.gz
    ├── 4a0e5089b6dc3c10a7674bd0a2fabe6048052618.nq.gz
    ├── 4c4b58e62300cfd8ea0d6be3fcfcbbedfea8f05e.nq.gz
    ├── 4e851285cd7ef7c583a4c2287c5b991fe0d8bda3.nq.gz
    ├── 4ed83c056d83802b2014e0829f2eb49bf9c8a4b2.nq.gz
    ├── 503461c67b1c2709879996cebf1d06bcd4bdfb7b.nq.gz
    ├── 50676df2123fc622fc3b16c4aa79e86971d1111c.nq.gz
    ├── 50747070ab224949001423f3f1ddafe47befaf81.nq.gz
    ├── 507be0960699b0438d5b910374ed204073352dcc.nq.gz
    ├── 5141d075eef8175e668b8000c4fdee2539aa5f5a.nq.gz
    ├── 520fad98428b07e2ef211a3cde54a59fa3666b62.nq.gz
    ├── 5242d27a91f6eb34afb05c28403bf0def1cc2bae.nq.gz
    ├── 527c51247c86d071bdc4d535aff449441a45bfe2.nq.gz
    ├── 53439675365d7c96d1422d77e591e4c9b3ec3ec6.nq.gz
    ├── 5429710cd96a08106dc1976b36795da27dd8cb5c.nq.gz
    ├── 54ddf042580b3095cd014e45efaa175f20ce6324.nq.gz
    ├── 54e360730bdbb7039bda53117e7dd3f38bae2cd0.nq.gz
    ├── 551a334861fd59974dfe9b003d1310d82e3627df.nq.gz
    ├── 56277192c3b88187cac34862ae22a8338065bd0c.nq.gz
    ├── 565d76521ffeab743b8dfa9979fbddcaec76214e.nq.gz
    ├── 56c7fb250f988b8aa8407ae99dd6fc35eae7070f.nq.gz
    ├── 56fef287ce03d84f9cd1eb5e746414d8c9da4519.nq.gz
    ├── 5700a0aa5dd2fa537cc6b5cf15d2ca45a22c9dc3.nq.gz
    ├── 5730c94b46003f742d95cf0c6ceb15ce17b61f98.nq.gz
    ├── 5753e0e7dfcffb0da7373b762a9e3966a080e2c4.nq.gz
    ├── 589d13cccb7a74726aff7967470530c9645a0967.nq.gz
    ├── 58d495f94dd23ab1e4c9d12d94d461fe0a5f8a01.nq.gz
    ├── 58ebaeeef3aeb5e4cbf2e53fb0bf91ceb84194b8.nq.gz
    ├── 5942b69b18a0a7a996681437afb6e095079c4e9a.nq.gz
    ├── 5a724a9e4c8aa9133d764023a3e2dcb75f82f281.nq.gz
    ├── 5a96f7820c8bc4c72c3de13b3c5257fbfad8575d.nq.gz
    ├── 5aeaa08c75ea3211403b6a30989959050153e275.nq.gz
    ├── 5af6617fe4ed329901de9a54e8d4c239fbd0f551.nq.gz
    ├── 5b511a4525b23ccd7c596dc497282bfc3a7d59e2.nq.gz
    ├── 5b7518fb84a04a567042a312e120244c96f1d38f.nq.gz
    ├── 5bdeee234a6f9bb9dcc4609b8c6aaffc40416f06.nq.gz
    ├── 5bec2b1e93fc9824d3c4a6c8d3f40707dd6dcfd8.nq.gz
    ├── 5dfc182d251cbbb3f4653985ae605eca16beaac7.nq.gz
    ├── 5ecbd60dae33e08df64ef949df4d848c7ab7d903.nq.gz
    ├── 5f5368830141f218c365f3e715aa6ad61a09920e.nq.gz
    ├── 5fbae2570204cea7807c548faa55a7e9fa22968e.nq.gz
    ├── 6072fc3156aee3f5eb4a5043046e7027aca83de7.nq.gz
    ├── 60c9e5c39b881d1381b1475277df2027ed246c6c.nq.gz
    ├── 611b20d2db87d77a9f9f4b3610d179a9ab4a773e.nq.gz
    ├── 61c4421b97b3f11625a9fcbc314feb87e56bbb91.nq.gz
    └── 6324f50bcff2efc03a5b3fd8d187b0cb9024e3e7.nq.gz

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

[allenai/EMO](https://github.com/allenai/EMO)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
