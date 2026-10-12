# Repolex Knowledge Graph of spec-first/connexion

RDF knowledge graph data for [spec-first/connexion](https://github.com/spec-first/connexion), parsed by [repolex](https://repolex.ai).

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
rlex download spec-first/connexion
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a23d44e0e0421fd83f5ba132269bcfd04b855a16
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a23d44e0e0421fd83f5ba132269bcfd04b855a16
│           └── chunk-001.nq.gz
└── blob
    ├── 0064006effd267449aa133dbb9eda234c0fedcea.nq.gz
    ├── 018ebd08c337cd60d4ee583eb50defdf960305d9.nq.gz
    ├── 027bc3054092226ba9799b9ab9e1651fbbd60356.nq.gz
    ├── 04bc145deeaf95973f552a9091593d630c170d89.nq.gz
    ├── 0541ce29b6369a0a65581f9db62f13f7340d47c3.nq.gz
    ├── 05b03b61f377f0075d4a2a8fca2d3acc17436c3a.nq.gz
    ├── 06674affbeab150c6dbabd4a6db04bf44729f3fc.nq.gz
    ├── 076db8698f540f14b3bf20cff9c40adb2f5e3857.nq.gz
    ├── 078570e390c12a99a5ebd1753660d0993c754b8f.nq.gz
    ├── 0a2159536b9d8ca60f416247e0007e0521a02801.nq.gz
    ├── 0a83e16a790ef3d55d8e6ebf1706e0291a083e7e.nq.gz
    ├── 0a88619fd15110f227b09fa0aca757ecbbdaf802.nq.gz
    ├── 0aa58870d52cb64db44b733953620cab8c6a7251.nq.gz
    ├── 0abcc897ab3fa54ff2400eb31f26c82805b9ad23.nq.gz
    ├── 0b728a3a45f1b5d245ba6d915c8b8a1cf7a02b9b.nq.gz
    ├── 0bb22098a72f8d3880aba7af838d4e1dbbefd299.nq.gz
    ├── 0c12854b2a67db9d8b50b102b0f3233b17469b29.nq.gz
    ├── 0db6c4f76f6fe996652e1898b8dca0c0ace285eb.nq.gz
    ├── 0e1fa2efca3499d28efde10be0abda1679a6cc72.nq.gz
    ├── 0e9da7fa381dffbbf47f9b44e82d9730d0b2b651.nq.gz
    ├── 0f7f3fd4a67ff41be9eb0b45563f2527dea4e82c.nq.gz
    ├── 11633a04b3d0539fe5cdfd7d88dbe2f2334b6789.nq.gz
    ├── 138f5b0e67a62108d9225f7aed013be1ddc2f63f.nq.gz
    ├── 14b1b5bca5aff627cecb5b56bd049e7a6f50ea49.nq.gz
    ├── 150ace8e51b7df4b4ef0adada77253d6e38e2074.nq.gz
    ├── 150bc5d09651b1c79d1ede13d1e0488ecca9298a.nq.gz
    ├── 158d0cc18e6218ee2268f0a3dfb94f027d6764e0.nq.gz
    ├── 17357d82c040c43a52899d419c3e2627afdace82.nq.gz
    ├── 18603e5081a32ea6a9b4cdbeefefe36decaaa726.nq.gz
    ├── 18d83b5a3c14a16a60286cb345cea24929d5974d.nq.gz
    ├── 1970a9b153020e1b729518ca100b2d85f76c0716.nq.gz
    ├── 1a37cabe4489fa6af09ed6d32973c514c4cd4a92.nq.gz
    ├── 1d787c65aa2590f4986413e92416f5a05f5a127b.nq.gz
    ├── 1de039bddca182626e9455420a6b0cfe435167c0.nq.gz
    ├── 1ea5a18ca53553fb209e14be9a7115af2f74891c.nq.gz
    ├── 214929f78c1a3b28306ef0f2c5c88f53629f87d7.nq.gz
    ├── 236a92a835d84e12bf1b2f9a6ec6c701deb4d2ea.nq.gz
    ├── 23e3b00aa8b2cade7b4922358e0de3100b3e6bc0.nq.gz
    ├── 23f62a724e35d369fe610a33f98bd139ff6174ef.nq.gz
    ├── 2410eea3bfd66cc705c25ed1d6f6ded0b7d4f305.nq.gz
    ├── 266ac36c4a29e8fd2aff43d62e49e985ba6890fd.nq.gz
    ├── 277d1e23623db69df3afaa620a0a2397670dc965.nq.gz
    ├── 289d348572a0e469e4ac03e8b53a25f046eee4b3.nq.gz
    ├── 2905e126ca5af55e99fb2ccf5f5a28f705d93eb1.nq.gz
    ├── 29c5627e20abed2e0cd7ef12cbe04a09aaf02c96.nq.gz
    ├── 2b0de63a799918da3a05330e3cf18b0c168d9725.nq.gz
    ├── 2b2bc56528987f271b3a7c902ce3f57bb39415c3.nq.gz
    ├── 2b4b7edd8b5250f57cf1fc9b04b36cbeb81f3c6c.nq.gz
    ├── 2c0810ab0b74a97b97db707415433d2dc9c9b226.nq.gz
    ├── 3295305e3dcf4aa83730dbf36b41bcde59d9b8d8.nq.gz
    ├── 36354f7908a7048ba64f4a7b80b43be590c5c4b5.nq.gz
    ├── 36e339aae42ca93f8a437e1cdcbf440e530c39e1.nq.gz
    ├── 374a49074c4c09d5dce3a6e3bcd36f36a9ec53c5.nq.gz
    ├── 384525f3392905755564047fa324e8ff95c6b8f6.nq.gz
    ├── 38a90f7a664e860da4e5f5eee4063ff0d4ac8b0f.nq.gz
    ├── 38c1642849e3e5c24fc73769f3c4fd9e2c11a384.nq.gz
    ├── 3d51083d3f1e052f6af26179b24f544dcb4a7cda.nq.gz
    ├── 3f3e728ae43129618ca51f098935cff4929dded9.nq.gz
    ├── 3ffae2c51d13d836f0c3dc1c0d0311e26b98ed03.nq.gz
    ├── 42cf1e890379119a08a0d07543cc773caf6d9263.nq.gz
    ├── 43c4c32f526cfe71d7e737746b78334bebc43831.nq.gz
    ├── 459ac7def799b787871a0fe1b4c8839a198f3484.nq.gz
    ├── 45cf62b96733ac549ec1b906783cafed2c3d2b7e.nq.gz
    ├── 465d565c50a1ed990f51556c8e50931860508102.nq.gz
    ├── 48cd5735cbf0e588c412a885fcdc77172b5674ac.nq.gz
    ├── 49806abae6fc192fbae38d240caa20409f0f5474.nq.gz
    ├── 4b26600721f94ccdf6ae0e38a8aa43dfbaa58659.nq.gz
    ├── 4d3bba247d3c6e35c65bec40b307a9c82c4b6c51.nq.gz
    ├── 4ea0b49b69c2c52336b190b407e43f05a0c6939f.nq.gz
    ├── 4efcf50b5c9fd22f6dcdf89021501f638c71f6ec.nq.gz
    ├── 5166b2e2f2014e0231f9ae52d159897cab9b163b.nq.gz
    ├── 524d68695740735acbc618e1911e11d68eb02d3a.nq.gz
    ├── 53945ae7cf2a8e86c7986dc8a969c532edb867ff.nq.gz
    ├── 539b9aa21a5adb58909471a2bd16414cf6a63ede.nq.gz
    ├── 542d5d480ddc349db8ed1c8c47e2baa3ce42ffa7.nq.gz
    ├── 5589f0426ec8ed015c68a4da5993767b7dba88e3.nq.gz
    ├── 5680dd60372b50ab60479d736b2ff32a8660e911.nq.gz
    ├── 56c5aec0d33bbd63102dc52f8a3ed9fb816d1901.nq.gz
    ├── 570510f99c13cac5400918c033d1c1e35c34d375.nq.gz
    ├── 57f334c0687fd7fd4a8b709d96786860a3051b4d.nq.gz
    ├── 5a586bb2649d08b976fb23bb45e9f4d1b33282c4.nq.gz
    ├── 5a73cad1bf22768a9c19035c6485f3562338e50a.nq.gz
    ├── 5ae2d36831aedbda251fc6ffb4bc54d03046c599.nq.gz
    ├── 5bf64399c6df6c822f27692d8283a0511ceee879.nq.gz
    ├── 5cd109839fe3f6dc6753906073d071b090f70a44.nq.gz
    ├── 5de062ebf1eba8ca6e0401d51c3d2a0433d09f01.nq.gz
    ├── 5dfe0a84e9e22e110f24cdbd4fe73a31851ba5f0.nq.gz
    ├── 6013646e64f11e4cb92e60001d3c65a3555e32ae.nq.gz
    ├── 6202d78366ed0ade8c5e27d995ee4662f3271093.nq.gz
    ├── 6266fbed5832ee80344855a36ad0b9b6ec9c8827.nq.gz
    ├── 63bb59fc8fcb9b092c397cefb864cd9943c8515e.nq.gz
    ├── 64b6e7c34c0e436e2a739ba730ffc3e9f409ba28.nq.gz
    ├── 66b561300d6774bef0d03b7e5708ecf15379e24a.nq.gz
    ├── 67390f940fe7bb35f78e36b530f713bcce8b98c4.nq.gz
    ├── 67daeff6de4566803c3f2293d274d02b55d5422a.nq.gz
    ├── 693ba343d1292d2f92f99259c6e828b9ddc686fa.nq.gz
    ├── 6a0ecd676e99488b56f431888405b7e8c4351e96.nq.gz
    ├── 6a8e56590be291d0c0c091bc02d4774cbcd1ed38.nq.gz
    ├── 6b026c24316396389fbd934c025dc57ce7962a0b.nq.gz
    ├── 6b11caf5604bce38c81fc435aa9c0c99d0b5c233.nq.gz
    ├── 6be3b86603d41ee970d5b9ac5bb4a2c035122029.nq.gz
    ├── 6f7c2d9aba6a816b36af34874c40e0c0deaa9be5.nq.gz
    ├── 701e0a21001d240531b0fa34c373f19513e86e7e.nq.gz
    ├── 705233067c08bd6839f06ea8773b87dc829bd105.nq.gz
    ├── 7101b57da04fab9717ac667b693c2e12e7b89b6c.nq.gz
    ├── 71808402f6297eb3b6340ffe336d9b8f94f135e1.nq.gz
    ├── 71a1febf78cd9d0a81281bc4d78589411e4b8988.nq.gz
    ├── 7230be17ae26d473ceaa94510b6403a2b02ce5a4.nq.gz
    ├── 7285471bf706f3752413ca03eed96f618b12b0ae.nq.gz
    ├── 7450119e1234e22877ad70fdf5cf23b5928eb2b1.nq.gz
    ├── 762121b762f361d890dfb50d70d5a8dd6e8e7846.nq.gz
    ├── 782f92da962f5e05917fc59f0bc633d9b27e4098.nq.gz
    ├── 7a4a3ea2424c09fbe48d455aed1eaa94d9124835.nq.gz
    ├── 7ab3a0f0b37089f2efebf36fb136c29e401bde66.nq.gz
    ├── 7ba26d60ac497b55f50c9b6959fa47c392b015fb.nq.gz
    ├── 7bc85a8a0b3a5c89b396bee5f33fdabe29630787.nq.gz
    ├── 7c4e31ea71059f151fa30c96dbf13bc8f6977d0d.nq.gz
    ├── 7e98b00cc4b05dde8a5948b7f27f4a7f1ff2456c.nq.gz
    ├── 7f39e46af977181d7e78dfe5fbf8670841e7b8dd.nq.gz
    ├── 803a51d758a8d8b0fb26eae766ba2b15d46727ba.nq.gz
    ├── 809c032c9f412959c9a7273e5b8834c0663ada00.nq.gz
    ├── 81b9fbf08240859f8e2ae6e5984993442e7db74b.nq.gz
    ├── 81e3949ebc967d52e4f33decb5d14b70ed86a990.nq.gz
    ├── 8323234f5629eb64913348c4c1aff9ff702476b8.nq.gz
    ├── 8796a74f95f698f01dfbd80532eba988461d60cf.nq.gz
    ├── 87b7787057f2d53c751e69f6d2d86ddcf8940190.nq.gz
    ├── 8804fc73fb473a3da87d974d59160872e680358d.nq.gz
    ├── 8933eea91af458c3a0ebf6bc934793e49fb74c97.nq.gz
    ├── 8b7c625055b70e72ebb49cc2291eb3916e8c16d2.nq.gz
    ├── 8c930ef78c83b6ed477ed78c2604f740749c2a0f.nq.gz
    ├── 8ea742c86ce04464a5ac005d9f4b32ed3abaa015.nq.gz
    ├── 8eb76c21028167b34caaa83f9c160718c53db809.nq.gz
    ├── 8f00bef1a0fa9104ed6b7add0e9175062bc8e6e0.nq.gz
    ├── 8fd8ea509ae7ee1d095ea60e703720da9d171abd.nq.gz
    ├── 90457992c89dafd2f3ed17a138b8f8a3e02a9c66.nq.gz
    ├── 91eb8aa4d52005057112d926d25524e8c569ee8a.nq.gz
    ├── 9462ce5e50b5cb34a5bec174dc60689e5821ab8f.nq.gz
    ├── 9481c0f69bd34b1bd241f38db0bcde9a4cf2fe13.nq.gz
    ├── 948e0418b665948dcc34bc96609f182f02898065.nq.gz
    ├── 9797c80e334cc7189ed127ee85fdad3ba9d427c7.nq.gz
    ├── 9a5c389762c4dfe4bc52b8903151a76d2d7ca76e.nq.gz
    ├── 9ae6a7b3130bbe70cb41d784c28705ce2df18cd0.nq.gz
    ├── 9bc299b2ce84c3273f5658cdcc372861d64e4bbe.nq.gz
    ├── 9c8e6c5b2056810672280e52ac4f128055eff0b5.nq.gz
    ├── 9d345266e12f728ed07d37c868518ec7cc73edbc.nq.gz
    ├── 9d36057b48c3a24a8ef55d759c786478a934ed74.nq.gz
    ├── 9e73bf45ab8cf6f1b6dabd505329962fc27e6e54.nq.gz
    ├── 9ec78d96224c3668622da7a7ab2a888b9ca7a77a.nq.gz
    ├── a128e6c0e50418054abee45f08047f10865ed75a.nq.gz
    ├── a2bf828124b36fcff8669a2c1994a1b99c3138c6.nq.gz
    ├── a327629a25457d2d919b3512d8dad8bd9ea6939a.nq.gz
    ├── a3488298972ba871e3030d6c792e950ed175f3ff.nq.gz
    ├── a4225652ae25df02d9cb6afab9809b5e75b9a813.nq.gz
    ├── a45ada28461357f5d0922225b024899109515b86.nq.gz
    ├── a4a05b857a066ca3f67be65c90ae307110fb71aa.nq.gz
    ├── a6e0984546178d9cfad45e1a9619e9363e884850.nq.gz
    ├── a709f9c613f9685ddccbd8e78966111108585026.nq.gz
    ├── a715ed394b1b9cf75216ed094050a3815e12b8a8.nq.gz
    ├── a7879f3b481d246ea1e47296e42340a21ed0ad44.nq.gz
    ├── a82a253deb78fd26e4f4953cb2e1c60ce55d813b.nq.gz
    ├── a84cfd21fd2f38dd5a1a77869ad7c260c0cb532f.nq.gz
    ├── aa9b0cf3097f960c2f9702863c0c5b6f21f93e43.nq.gz
    ├── aaaa565c5ab62cc0b5c1cb341330891e171677bc.nq.gz
    ├── ac3d70d331bc77bcdc32b186359a26d6a08ae24d.nq.gz
    ├── adf59b585bc052589fa0e0d8c1eab1227da435e1.nq.gz
    ├── adfa1b1152a238ff21db3a2b88f44de95fa28cc8.nq.gz
    ├── afcb39c490c2b08089b0f52b4802bd3956407575.nq.gz
    ├── b0cb0bc8a5d17dd2fa5373ae45c08c74d8945ff7.nq.gz
    ├── b0dd94a7079344408ba004609b8b6312098eeeaf.nq.gz
    ├── b11194684d76ca6fe51865757b1e389bae4d8e94.nq.gz
    ├── b1df94b6538ebcc05f0963886b37f173506afd9f.nq.gz
    ├── b3cdbc688c2cf816e9f3d70b39369bea30eb9c3b.nq.gz
    ├── b3daa29809f460106c6b195c6163352d5b684d86.nq.gz
    ├── b514e51cedcc7353e2b4d0d6830acdd778e71ff5.nq.gz
    ├── b5e8deaf76cf41a93d079bb0f98ab3c0ba07f738.nq.gz
    ├── b816053ec9e6bef77d04a4af1656cbd092db91bc.nq.gz
    ├── b98c310a81611083c53b4a2738578045c79e4efd.nq.gz
    ├── bac0316b3a8fe75a3acade9eb222e9a46807ee4c.nq.gz
    ├── bc3bc1f44eb6ae31ff4e7d8d263fbc5daacd080e.nq.gz
    ├── bec773dba6bf780f3e7477daa82aa7927949b4fb.nq.gz
    ├── bf0b84130081d500197d2371241ac92fe6ab8f42.nq.gz
    ├── bfde3ed0370e961b60b7c0703c1b736e5a7901d0.nq.gz
    ├── c196f72bdceb9614f58c955a1814db4b4ae9db55.nq.gz
    ├── c20f49df7ae627aba8e7c1541ae795e6b3f4034a.nq.gz
    ├── c24cf0e7549a188faf50e94487953e9b833f01ba.nq.gz
    ├── c5086bca87998208f380e2606648a723501fcbf3.nq.gz
    ├── c53341cfb2e128bec88e2244c12e8c8727c733db.nq.gz
    ├── c5a27f4a5f4af96d416b9f38fee700fa20a8952e.nq.gz
    ├── c5e1ffa99ec358c99d8515ff21912c3e65f349bd.nq.gz
    ├── c63e03a575d713afd3039396b6074754d9b2a9a9.nq.gz
    ├── c7cd5aa6d897a6f7819742ee1881ceb0b24b82af.nq.gz
    ├── c86a6bf29b7ce2386aaa3c082cb77193f556166f.nq.gz
    ├── c91b89de4f4acd4ab3447ee5906c3abcb2374e99.nq.gz
    ├── ca66a6c619c84ba76835b3b99e651b68fc2e59ee.nq.gz
    ├── cc069a5d4ed02ea14282a4a02825c583d1c8c21e.nq.gz
    ├── cc0bae039916afd48548278f73492e1c74911ab8.nq.gz
    ├── ce4974b360b3385b70bb8a4ea921027cd64e3bd6.nq.gz
    └── cee68a5f24ca7ba5f57488eb9a9e585df2772e25.nq.gz

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

[spec-first/connexion](https://github.com/spec-first/connexion)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
