# Repolex Knowledge Graph of NousResearch/Open-Reasoning-Tasks

RDF knowledge graph data for [NousResearch/Open-Reasoning-Tasks](https://github.com/NousResearch/Open-Reasoning-Tasks), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/Open-Reasoning-Tasks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 35df7000b8f636178e303add868415b30f92cad0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 35df7000b8f636178e303add868415b30f92cad0
│           └── chunk-001.nq.gz
└── blob
    ├── 00db66a361c8293e923c12861929911cc2996686.nq.gz
    ├── 014e8cae32e24d68d80fc878397bef7f59d361d5.nq.gz
    ├── 022bf95146abe092c6d59c49a158a211f3f14ff3.nq.gz
    ├── 02798f444e6d60538d721625922c70d920cab407.nq.gz
    ├── 027e24cca97d419c9b3c0ca345d5ef3c58eba246.nq.gz
    ├── 03093fed3e901a2914127c320753dfcedb016aeb.nq.gz
    ├── 04011f6068f94fe536b6452dbedaece09f7c270e.nq.gz
    ├── 0540af798e64d9b819a030809196e9dce0719274.nq.gz
    ├── 0605876b8478123da926a05f88988fa743e3e330.nq.gz
    ├── 064788f71937660195f682a07664c96692f35c9d.nq.gz
    ├── 0bc4728a7504254ec164b23e0180d5756dc9e630.nq.gz
    ├── 0c286fa1255ba85b7d4aad9306785ce48f4bef13.nq.gz
    ├── 0e5f8a7879142073d9ce10f092055636d2e6bada.nq.gz
    ├── 0e933f2d5eb893bed845875420816bfb8358e220.nq.gz
    ├── 0ed0749f450225b7486181cffa02e622be9a8a18.nq.gz
    ├── 10010002bd4dd4425d7a6475c9441a365218198e.nq.gz
    ├── 10bb764352998e466287ed69b5439a6b0bd0a51d.nq.gz
    ├── 10e66e275496c2e75fe89771d1c113d77377abd0.nq.gz
    ├── 1165ff83b6dc9f53a26a4187033fe178e93cf45e.nq.gz
    ├── 11a312b33fde1e4be5778e766d38d4df2fb5b61d.nq.gz
    ├── 162eca97eb7568584cd331261fad845561183faf.nq.gz
    ├── 18cf2113d630a2e9dc7ed46f2bcf250ac3fe0bb9.nq.gz
    ├── 19e0d421aa61e77104b3b2c9d9704e28ce60d32a.nq.gz
    ├── 1b146263c809cb90b4c6ce2b003d2d7ce94ad4f5.nq.gz
    ├── 1b5e678ef522c43d9e328fc8c4968f766f8f10b5.nq.gz
    ├── 1f4df3ab8ba754b76f2ea5cfcf07dd1472dd0a7d.nq.gz
    ├── 1f5d6ee7b00214419ffeaaec40fbc4c0385f32a2.nq.gz
    ├── 20f2c5ff90d4ea5e412009fbfa6671508bd5f5ad.nq.gz
    ├── 21d0025cd821f2daddaf7db232d7f6e76b0aac3e.nq.gz
    ├── 21d3244711cd9c2fc4d758ac238eabbe7b7ebb52.nq.gz
    ├── 2300f8405cb7a389f30577789ee5e9223883f372.nq.gz
    ├── 237f7b04af5aed1e4cff4936ac186c6042f22e08.nq.gz
    ├── 2408ed443fc6699ec33cf530a41d6fa2e31ac355.nq.gz
    ├── 250bbe1406866bb5bf68ca9d04c1834f9e18a461.nq.gz
    ├── 2534b236661a2bf613695ff096aaa415f5e4d6e7.nq.gz
    ├── 25b1997fa8c21063f64806a64bffe08b21546b0d.nq.gz
    ├── 2617e6c3e55ba24f3520617bdd83e50c54e795b2.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 264bdaeff03ddc9c727802f29f0ebd997e9c1aa3.nq.gz
    ├── 281bb9974f07a0993bf37fcd3d91bebbd92352fc.nq.gz
    ├── 281f6bb5c80d3f2f97fe0e718ec8c84302aeced7.nq.gz
    ├── 283834fb76d45cdc6ec232eba954cae254df7220.nq.gz
    ├── 28b3b0534c9b5be86b367dc4e2108b9d3d3a3e5d.nq.gz
    ├── 29ade02fda2dcb3422bde127b0e69f77de5817ed.nq.gz
    ├── 2a392481c0e2b54410bb00b70705e71e4fb62c1e.nq.gz
    ├── 2bc73a10a5c005e4ef7bb2f0ad069cf8f98a92ed.nq.gz
    ├── 2cb33b6b128e18314421467b388427fc1048b080.nq.gz
    ├── 2cba291c8240c8408e9b7a186921bc7a214f9bea.nq.gz
    ├── 2e0555ae5a320da580b38da2da3158f690cf1644.nq.gz
    ├── 2e9b141e79a4396aa974826449c1ef4890f45c37.nq.gz
    ├── 2f912b69204eab395b9cf010f7f1841cb4cf0f06.nq.gz
    ├── 2fbe30bc8326de270692798f30a1bdee0e102302.nq.gz
    ├── 2fd4628b7023a60c71c527279e793074d82c28db.nq.gz
    ├── 2ff739d549b14e8a543f6543d7ff20b2b5b354a9.nq.gz
    ├── 2ffea90de1caa1b2e319d96f2dd0cb6103110588.nq.gz
    ├── 30ac3664e803bc9db0303ed3c1c16676f2771996.nq.gz
    ├── 31809dded367a4eda751b15f008cf47e6aeff20e.nq.gz
    ├── 31aac99357e0fe845d9eca5ef81466b2ed5c49fa.nq.gz
    ├── 33880fc3aff3fb5acdf14fb8a1bb79c1565e2e9f.nq.gz
    ├── 35059e509776a733cc0582a9f2b45da872d8a00b.nq.gz
    ├── 351abab706c5540c2316e445e201c8d27455ed12.nq.gz
    ├── 36d63fdb9d7f84ac6907f5b628bfe6f0e5e69643.nq.gz
    ├── 381edc425ecffb57fe60e5fc76fa3bd8a31a91dd.nq.gz
    ├── 392775429f55ac52adaf74779a5f09dae1fbb924.nq.gz
    ├── 3ab7c62dc78420900d004f8be8d53d717a5d268e.nq.gz
    ├── 3ac2aa9a9022798af404c5c4932cc536538423c3.nq.gz
    ├── 3c5a31c9e530ee878ddf731dd64b4d4cff5e0273.nq.gz
    ├── 3d1971a9bb64aa5b8d92b8529e30607d80cb6490.nq.gz
    ├── 3d78f1de198a1a7ad0d91f76471457c0df53753c.nq.gz
    ├── 3d991de112d29fe2b8445e379833ec684b39239b.nq.gz
    ├── 3dbeb407f82a77a9d830feddadd6e5dfb2d31ca7.nq.gz
    ├── 3e44b772a023c84d0ba787486c2cde0c8a625290.nq.gz
    ├── 40d6ebf143097c61256ba4693eb8197cd7c8a4c8.nq.gz
    ├── 413574689027c6bdc147bb90af93b4967c848347.nq.gz
    ├── 414ea0fe9a32a5385d084652c912aadf82b96c8a.nq.gz
    ├── 42bfd987a5f12ea6742020ea1488694ebd6590cc.nq.gz
    ├── 44ddbcbbaaa008e84f954f960806dcf4cb3a6bf9.nq.gz
    ├── 451866604e43f4e0269d2343178714c9c129e247.nq.gz
    ├── 45eafc59ed8cebae47ab298bfdc9440dd1904e9a.nq.gz
    ├── 45ff72b525c9ce297d29da5c64cb4e9096c34250.nq.gz
    ├── 4657d3aa156be1219e5b9904a97c15d5ff6430f7.nq.gz
    ├── 476b51c3d9231212266dd91b89b20e163a8cd067.nq.gz
    ├── 49794d3d36e664ba36fc5044024af2d82682364b.nq.gz
    ├── 4a61771d7cea31f047c38c1f265de12fb82f9953.nq.gz
    ├── 4b02eb6ac795eb1c15278ee89d589ebb471dce57.nq.gz
    ├── 4b5403e2fe4aa285bddee1a70f29fac972895d59.nq.gz
    ├── 4c226e45e1a19931774a90be37e0097cb584dd2c.nq.gz
    ├── 4cdf317fbf622d4f3b77349c3fb835439a09b0dd.nq.gz
    ├── 4d725b18b0f43a64f9cf7b1a9e322711743bf698.nq.gz
    ├── 4da75f44ece6f997de674ff1bc5f4549489bb2e4.nq.gz
    ├── 4e20920000291e104c3b6267bdad62545835bf6a.nq.gz
    ├── 50b54c4210a26fedf90b6c55d254c5d955724b3c.nq.gz
    ├── 51103a25c821f2de0d036970a5b1ae263794f8f5.nq.gz
    ├── 51a2a7aae7df71c4464c5fae7b8cb2a23f6e94be.nq.gz
    ├── 51f8bb3be94bd0913271f9c22cb96f89f813b791.nq.gz
    ├── 583861c43b98ef9daf0ce4d69c34532a6eac174a.nq.gz
    ├── 5b3b16180640c3e4288f653324c6058fcd716e19.nq.gz
    ├── 5bab4434375addafe10a79c05e2f040ed7e8d9f1.nq.gz
    ├── 5c93841593eb3193e5cbc57448f40724516563c8.nq.gz
    ├── 5d6331669cdfe6668ec736c2f1bfc6ea1d71459a.nq.gz
    ├── 5f46b23a639a4800c4f7b51c29532f90202d726c.nq.gz
    ├── 60585ae2a6fd2277a02c1813359caacea82f603d.nq.gz
    ├── 606ecf88088894ff2bebb69731f45be9eabe742e.nq.gz
    ├── 6095bd02154c38239db30d560046e61cb422cde6.nq.gz
    ├── 60a4c9b3e5f7b13b94a7a2a335011862c3bbeeae.nq.gz
    ├── 629a3c297ec488ad20d7dc404278fed2d30346dc.nq.gz
    ├── 63323e456cf541a4daaa2c3e880876a31a3e01f3.nq.gz
    ├── 633e8d341b0f2aefc94fec22129b18a7f4d567de.nq.gz
    ├── 64303021a4ad6fca92783177f75aa757b294353d.nq.gz
    ├── 6439b3d63c5d4f5eb0d13675df65fa0e22b9ca67.nq.gz
    ├── 64b8218bfcb6bcedec047f55ea23f81cc2420dff.nq.gz
    ├── 64f6c57132523725f54c062a88f85715188ab779.nq.gz
    ├── 650bea5e9f290cad4c08b94fdb864bc42993df26.nq.gz
    ├── 65c0b4ae6fed8a41be1c1ec630e037a696f4419b.nq.gz
    ├── 66525541fe3220adcd76eba190b117428e040037.nq.gz
    ├── 678e87277c1e4587afc60d1c018a4e0cb6cc97fa.nq.gz
    ├── 6811ac4d0f298d81f9312f00c74a71302e8bd703.nq.gz
    ├── 686601018330fb5e9616d8d9fe869e26af5522b0.nq.gz
    ├── 687edc3e424cbb125b9e52530d7108005e9d7e59.nq.gz
    ├── 68ebc11fd35c52ed7c4e2be146f700c6d98a04d0.nq.gz
    ├── 6942f68620329b4fbecf6783f54ee93ebca139ac.nq.gz
    ├── 69d088e59bafb26b6dcd1b5c0375b8ede892e77b.nq.gz
    ├── 6a62ee3659e21909b0bfc840d58dc7c01153dfc9.nq.gz
    ├── 6bb8e6ee0e6804d7f5be639693f268adb01d3135.nq.gz
    ├── 6be16b87fcc818a60fdfd9704b3a99e3ccb24561.nq.gz
    ├── 705549a04c94f94216b20eae42d21a35356c0c63.nq.gz
    ├── 744af35232c67ac0d9ae647aa715ecb965286d2f.nq.gz
    ├── 7601cbcc6b602cb8b86d8c945a970f274d2fa18d.nq.gz
    ├── 761f39b11f660779c80bb8e4fb1c8e52dd6888bf.nq.gz
    ├── 767ee2ed9bc0327b363e1cc51f88e5f6d772563c.nq.gz
    ├── 76937582b07d333fb3cf3ca255059b1fb037dc34.nq.gz
    ├── 770c6f7005ccb0447209673ef2f27c461620a52f.nq.gz
    ├── 7730039cd52229bcf4759cc2f437243466c33f94.nq.gz
    ├── 77315fb7d5d8d17ca77a583de4cc82807b4067ff.nq.gz
    ├── 78917e5bbb054634031073948c5156781343a45f.nq.gz
    ├── 792f90eca747c8ec2a3ef08ab58d3c3d7be49e59.nq.gz
    ├── 79909cf2f8a2bd20b2884e2b3ef6d46fa5117fca.nq.gz
    ├── 7a70e4a71f304be597c501242d90ef7a6be2d7f2.nq.gz
    ├── 7a9e8555a31fd1bb4f944edde9ec5ef82ed93e0e.nq.gz
    ├── 7bb08806f4677ecee5f29630c3f481668ffb9ae1.nq.gz
    ├── 7be54056f8913107f0e1c803f2a19429fe8c3b6d.nq.gz
    ├── 7cfc3baf63f6e4f6cbe9bdbbdd25424af74cc11a.nq.gz
    ├── 7d176ef7dbd309f0adb04f5441022b509a009d34.nq.gz
    ├── 7f88ecda07a83527e0649ba44006b44bc8ac2185.nq.gz
    ├── 7ffdcaf13d3733b70854c02f680b7392a59264ce.nq.gz
    ├── 819850fdf08d91ebddc1bd03927b579abec9bdec.nq.gz
    ├── 8236537366acb9f377570efe75cbb89b453de100.nq.gz
    ├── 8326ede5c36f89eb7b627ed47ffa6df3009293b2.nq.gz
    ├── 847a0677f62baea92d94b65dc76db64770d7f953.nq.gz
    ├── 85873d4775a4355068e16ce7a449b452a867bcd5.nq.gz
    ├── 859bff0d10e4a2776a6af15e7c6c436614cd9024.nq.gz
    ├── 86091509676d7c9b5eb8539a744f776d61a81ea2.nq.gz
    ├── 865d49dea1b5fca44c999cdc85a4d64947c67cf1.nq.gz
    ├── 86fa1c1a8cc767abbb17a6704180e3f3d5d384fd.nq.gz
    ├── 877a45cdf651bacafc657c70dae06b92ae80bfca.nq.gz
    ├── 87b31ca192a4cd25ad34e9ea09eed7a20a3a094c.nq.gz
    ├── 88903d1d336be5ad645c586caf9a4a11b9169fd5.nq.gz
    ├── 88d0bf5131f42cce4929492da79519b51b3c4f5c.nq.gz
    ├── 88e9478e8324375e6ac0eda26dac9866b424a04f.nq.gz
    ├── 8914f69badc970f7f44654fbc60096c3399c2311.nq.gz
    ├── 89d1bb413c595e4920b9fdc715ff68ab613152e3.nq.gz
    ├── 8a04dd01a6b5638ec3bd36653721e9866b949f34.nq.gz
    ├── 8b3f9fc90666c375b0804e5077df5a784d72902f.nq.gz
    ├── 8c0a1a75a560a5fbaf6dd610c4e43a765a8bf47e.nq.gz
    ├── 8cafc5504f4205c53875c4d8b96d80b8ddfb53ea.nq.gz
    ├── 8e1425ed9298d67cb025b1ce7b70434fe7472e84.nq.gz
    ├── 8f3111a2d353aff8c1e08b08d9ec71e2b065a6e7.nq.gz
    ├── 916ddc7ffcf52e61f80bb26f5d63570d0a5d9b73.nq.gz
    ├── 920ebcb52ee88d32b68bd6c96e19580c5bcb3b2c.nq.gz
    ├── 925f4ecd1e0e62f60cf82a15cba4750be0388896.nq.gz
    ├── 927c8ef9842c016687c5106d011ab1cac37263af.nq.gz
    ├── 94a3e6087d44ba239a7e51521c4a1bc439d4dae0.nq.gz
    ├── 9734e059023e8dc4d985cf3e36be0cd3e3afd90d.nq.gz
    ├── 97f98bcbb1e93c5577d9c6836be2f22b63fed6d8.nq.gz
    ├── 983b51609de7c154f95d325f826be1e347d992b3.nq.gz
    ├── 9be17f103b87949b0c38982cae9816cca9aa9007.nq.gz
    ├── 9cbd929ca2be09c8086696517e0ee7ae0f540c57.nq.gz
    ├── 9ce9fdf3b572d470ee6bbe9a76293a7bb5c72983.nq.gz
    ├── 9daea8e6ecf50780812664c1b91b4107a64e1fd6.nq.gz
    ├── 9db01443e4c0a84b9d4a098a2ac5b54940c31f8b.nq.gz
    ├── 9dfb62c6e964b7ab989896c74a476295db293326.nq.gz
    ├── 9e16475f741584f7b77fc78a8b87f365b0a4fcae.nq.gz
    ├── 9e637a80b31e7a889bc3b70d085a8d160f1f6bc9.nq.gz
    ├── 9ee05d4dbe1edc2ccb1c31ede79d9662f797aa1e.nq.gz
    ├── 9f9068e280647c33b908e964e0f337651eac1c3b.nq.gz
    ├── a09d482eb1de80684b6df822b54b69b655533f0a.nq.gz
    ├── a0c10da606e80e0e86abddae2136b7a84cc8c397.nq.gz
    ├── a10d737786caa673312dd04acd7e0adbfafb5867.nq.gz
    ├── a14ef7e3aef0f4ad7ef2caa34e3cfde26d96211a.nq.gz
    ├── a17d44226a40ff9b7c71e45b9449e28c1ea875d2.nq.gz
    ├── a2136b46c57087b9485e141c3f99230c8c5ae038.nq.gz
    ├── a49032ff82f2ed64259587b213e93a04bcdf3d20.nq.gz
    ├── a58d2dc54213c32359bcf72e179a99cbf9e895fd.nq.gz
    ├── a6d4b2e7a4f99df1ca8b6ff231e60b721a3f86ff.nq.gz
    ├── a8c93b1cdbf96db4b2995db4fd3e1687aa1660aa.nq.gz
    ├── a979bdc9b8dffdfe64d0faaa209b2a7829f1b704.nq.gz
    ├── ab2dd988cb00913f0b36553a83d4738c895d7b98.nq.gz
    └── ac7d3eee98c9dc4f4f827449a2d12160c6b0ae26.nq.gz

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

[NousResearch/Open-Reasoning-Tasks](https://github.com/NousResearch/Open-Reasoning-Tasks)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
