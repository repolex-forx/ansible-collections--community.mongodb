# Repolex Knowledge Graph of ansible-collections/community.mongodb

RDF knowledge graph data for [ansible-collections/community.mongodb](https://github.com/ansible-collections/community.mongodb), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.mongodb
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 395a0c27e4e19d53d4d12c2ca4e2fc7902ae02f8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 395a0c27e4e19d53d4d12c2ca4e2fc7902ae02f8
│           └── chunk-001.nq.gz
└── blob
    ├── 00928b0af0592da9179e50b9a8bbc21dd6d008bf.nq.gz
    ├── 00da833cf1483613e3cb89ec226527ed8996b49c.nq.gz
    ├── 015642bb385d6f8cd3d5c024eeb3856d5b81ae50.nq.gz
    ├── 02580d1657e2329d919dd4757fd565d2a15be3e9.nq.gz
    ├── 027552c63a60aaf948a6d31884fc74cad6140a54.nq.gz
    ├── 02e646838f9bae9c1868a0af08f07d0899aa36b6.nq.gz
    ├── 0633db98492ff36366e9959ec290a8ebb1289155.nq.gz
    ├── 064e00a2c007a0f24827530459e81ca9d49dd479.nq.gz
    ├── 08024e35b4a19867f0868945f2d37ce5795708fd.nq.gz
    ├── 09633e36afc66fcd8395be61701c4da0ed97735b.nq.gz
    ├── 0a1bcfcb3d66af37604cb9b8540ecc568bc5d769.nq.gz
    ├── 0a89570753fbe373250949f877c908bcb0d00b7b.nq.gz
    ├── 0a925ed8b64ae387ab9119de746a2713e2867aa8.nq.gz
    ├── 0b51e5f16b79fc95c0ab7bea5033b54bf8597bab.nq.gz
    ├── 0ca7f037118d36392256cca3496407230dc1af9c.nq.gz
    ├── 0d4e9997331d6bf1839b2d7e1c1af0408e98aca3.nq.gz
    ├── 0daa79eece62e33d12031347bd2384f243d1c184.nq.gz
    ├── 0de8aecd1fc8201b345647ea46e2950f8a4070f2.nq.gz
    ├── 0e1368a671dd7dd0bcf9114a38666d6bf05e67c9.nq.gz
    ├── 0f0db5a7e7cba79366ff81212b97cbf199781d0a.nq.gz
    ├── 0f9c69fe72f9a29df7bdb3104488319e4c69808f.nq.gz
    ├── 105f0bafbcb1016ddae983ef7387356de59c5ee8.nq.gz
    ├── 10dd8449134df56c962be03db85e2b2aafa6a8ac.nq.gz
    ├── 1162fc03819480c328477d16068d60795943206e.nq.gz
    ├── 117eea8a656cde69cd50eacc2bdd59e6670912f3.nq.gz
    ├── 1248497d8c0679d83054fe14528818a1cf7184d1.nq.gz
    ├── 1256729f490051f49c1a7af978b74a49f8a7ef75.nq.gz
    ├── 12be2de335771c16438f4c563a3b0a4212973b14.nq.gz
    ├── 18edefe0665b2894a324920e73c5b233cea9766a.nq.gz
    ├── 190d26225a191f8dda0e404f9f931814d6217fa8.nq.gz
    ├── 19848fbed96ba3eeb3575763ad6164eec7d412e8.nq.gz
    ├── 19ed2bfe0f5b9ee33e410d584714a6bfc2d22fc0.nq.gz
    ├── 1b24d5a66ce6ef526128dfefd7b83cfdd5e28e14.nq.gz
    ├── 1b44d4f617fc666954a0917737eb4c1d0b39f05d.nq.gz
    ├── 1c3a49950f543bcf9811c09c489e831be477aa04.nq.gz
    ├── 1c4fb2f5b95b1754ca26d5be5c4f2fbf4bd17378.nq.gz
    ├── 1d9facec36de32d4b2f64987b33b54382dad9707.nq.gz
    ├── 1dfde0cc1323658aedad58186cf6b2378ddc06c1.nq.gz
    ├── 1eeaf9226e0032d1ea449ed05e67ac62c92bf050.nq.gz
    ├── 1f736d9e75607dd665e4593212c8b4b98f30c33c.nq.gz
    ├── 1fe0cf5d8e2f2a4dca70c33974cd61ea94019b67.nq.gz
    ├── 20311e9101c7af3d62944642a56b71b6967b6c3f.nq.gz
    ├── 20e544924aa18de67b02ae8a10ba33d1bbea7548.nq.gz
    ├── 22130d268c53cae75842ca87a24d71b6ffad49a2.nq.gz
    ├── 223ab1ecae0fe618ba32771347d6865ec6ccacb9.nq.gz
    ├── 22d4c37004eb0b4c1754f6a22c6a460004accd37.nq.gz
    ├── 238fb5f0d840ebae43c79a8dec18886b4ccb1565.nq.gz
    ├── 25f2b6290b4e1cf1aaddc5f69f4a0efe064de531.nq.gz
    ├── 26c8906b059938794a510f8d7cd281cd4052f0a3.nq.gz
    ├── 275068140f4454605d9921fb698272a8a4406cd9.nq.gz
    ├── 27cda37bbd2c975ae4bc833e2617c7089b1ed3b5.nq.gz
    ├── 281302f5d051f48ddca2a882d765c0776b2c861f.nq.gz
    ├── 281472a8832e164cd87b75d6c196d13cbb224723.nq.gz
    ├── 28441e931d7d57fb4c7cca7f6a67ec6b43269d42.nq.gz
    ├── 2a4aacab799fa06dfde62dc2ec76bb4356ee8290.nq.gz
    ├── 2af9972e545db0e694df728385e840a88cbd9945.nq.gz
    ├── 2b36fa9eb3a2f3014105f16d8cd70a4e871d720a.nq.gz
    ├── 2b4ca2e06612ce7a5fcbb31aead19c7df46af17e.nq.gz
    ├── 2cc82be8cdc3891e6e4d0be2dfe03f02d477f244.nq.gz
    ├── 2d439028ea5d3c9b9569f52e257324b11156ed6e.nq.gz
    ├── 2f52f496cd5985bc5680691fc86049383e6d313b.nq.gz
    ├── 2fc340c43da870c784ce3a150b2dfc8bb4005122.nq.gz
    ├── 306f15e4dab6adba2938bb391bb9bed1a2913d08.nq.gz
    ├── 3143b6f8e7b469b4c243e2446d5a4bae5d6e18a9.nq.gz
    ├── 31693f3a63afcdde33a0145bb3dbdbb0e7735cf7.nq.gz
    ├── 317c146db996510c00e6cff58cc836565e2d7e82.nq.gz
    ├── 31cdc5e9cc9d28570e408c839367635d0956a6de.nq.gz
    ├── 32f372d0f8dc609dc3aed502900a79677b27877e.nq.gz
    ├── 35016205de7f06da87ad7e17804a51620272fd2c.nq.gz
    ├── 350bf33b8c054f08d8ad55de7051900f07529bc5.nq.gz
    ├── 364a5934543e2787952a6e7834b6b3122aa079a0.nq.gz
    ├── 368cb966bf6bf9429709f5a38d5e4bb8f5343113.nq.gz
    ├── 375c798369729341791de9feac9ccfa84106a1fa.nq.gz
    ├── 3b050d0cfc74fefc52d15357ce637670d7461549.nq.gz
    ├── 3e31e2fba195ac08cba5219808991e724492b822.nq.gz
    ├── 3fd577f6a9716e2ad4ed485fde051ed12e0f3621.nq.gz
    ├── 3fd788ec2507745c1092be9618f59883dcc4435c.nq.gz
    ├── 40d7903b123fd2cefe1f6f0196166f0b36dc98a7.nq.gz
    ├── 4109162391dfd5ec99b41fbb9fe8fba3c56d4df9.nq.gz
    ├── 41fae6fb0c40ae96b11479e21b3cf15dc663b8e9.nq.gz
    ├── 42933bf2146082606c514f0d5172f9346d9f76d1.nq.gz
    ├── 43143c54ffa736f1e05fedb15e2d78a5dcb1eb23.nq.gz
    ├── 436cfdcc86c5bcb3126f17f058bf1c8605ababcf.nq.gz
    ├── 43c1e4a704ab8c6fdecb31fb393d278715db41f8.nq.gz
    ├── 43c462fb8b3baab874fe469ecfb7489843753a9b.nq.gz
    ├── 43e1983d7c593f69aec1a1010bc9564d20d37159.nq.gz
    ├── 4419c0689b8ba2871455d4bab1475e970cff21f2.nq.gz
    ├── 442eabaf6426a02bdd9bd8906809106d0613a429.nq.gz
    ├── 4435593f195f5c04dc21b8b505d187b2624072ac.nq.gz
    ├── 44ae6f9030502f49b9d2cb798425093e716e2aa4.nq.gz
    ├── 455c3db5044df86c43b26342b848203b71dfcd8d.nq.gz
    ├── 458cdc63abe7445ac0e62833b8d6c154f1c16c76.nq.gz
    ├── 4634dd8df16b59a7f8297ea44ca0ce9d41202f9c.nq.gz
    ├── 46db45796e5da07a479d3c5112089507c7e3b1ae.nq.gz
    ├── 46e4c005279e8c73219107a39d6081e85f1d2bc8.nq.gz
    ├── 47197a81c985463c8373069d5f11fe5a53bf81f6.nq.gz
    ├── 48ed1e4b85c4277858343a1b0638feb99435ac99.nq.gz
    ├── 49277bf16bfbcbaa253192cd36d7f262e041205b.nq.gz
    ├── 4935adfebc51d62b08934eb559b6ad4d763beccf.nq.gz
    ├── 499c72061a434cb613bf095a23f541b688b9e5ca.nq.gz
    ├── 49b383e0788f17d93bfa692fa3fa6976facf055d.nq.gz
    ├── 4ac57b0ad0fd5bcd15ce47650fe50191054ebb98.nq.gz
    ├── 4bad5926d4585be8a70ba2879bf36f60e2b45677.nq.gz
    ├── 4c42d799e5358e3f2e11b389e27947f090f7b43c.nq.gz
    ├── 4cecbcadd861050fd8683ef08d08629ac2660b96.nq.gz
    ├── 4dca6e2e3cc88c59341761d3b5953c73e8bc4b43.nq.gz
    ├── 4df9dd94914910eb7188c9e8ad22ea142da00eb1.nq.gz
    ├── 4e72a693daf88846a946cd77bd62fc5bd5da0034.nq.gz
    ├── 50113421719f041ac19d32a475a3a5ad6a7d607c.nq.gz
    ├── 507e9812fa51f66bbba730d48c59749b2c8eebb5.nq.gz
    ├── 50ad1874f6b14e5c1ae88aadd1d5844acc4bcee4.nq.gz
    ├── 5147d700adcdd3e618e0153be3aceddf6122b6b2.nq.gz
    ├── 51dbf9b6600194d5e7946a2ffa427389e1c78c88.nq.gz
    ├── 5307bca6e2868ed398342e46fdd4c030778527e6.nq.gz
    ├── 5354321a6ab16e9da69a0ea1d7293d512cf023b2.nq.gz
    ├── 537c90465b50ecc2e34a166f83f01adafa498a68.nq.gz
    ├── 53e974910bec455c7c0bc1c1d55bf4e00da2bcf2.nq.gz
    ├── 549508f92cdbb23f43ddfc2f75d68a6d7a53535a.nq.gz
    ├── 55e4ed52c37a272b6406da5e4892c217d23d3e8a.nq.gz
    ├── 57d096337cc7ddfbe510a744f948e0913f10edf1.nq.gz
    ├── 57ebecc871697ad8f385b6b6592f7b74e4fdb148.nq.gz
    ├── 57eeb6c090a48279feffab0ef2c6922ebb41b3b5.nq.gz
    ├── 5820ace9aac0a7b8b425a65f0e80583897268c53.nq.gz
    ├── 5a948d5c91e23177506ddfbd9865c01a0e4d72cc.nq.gz
    ├── 5ab42a4c798531e0d89cfbd20bc7d5222b94183b.nq.gz
    ├── 5aef024064233e0364a85e364c917dfffcaf3bb0.nq.gz
    ├── 5af2a1b73d0aa22d47fd9ae80ff1cde15bae9dc8.nq.gz
    ├── 5af99e70576d06f30304e7fef0e3e06a8dee60bb.nq.gz
    ├── 5bf5f61b8ba2f92e414bbed71c71609d11cc1f44.nq.gz
    ├── 5d1a43a171807e3811bf5c983c65c880a923a40d.nq.gz
    ├── 5d3174aaee284f029955979318f066c4b0d8e56c.nq.gz
    ├── 5d380b90130b84179fa8244c9ef555bf87aaf762.nq.gz
    ├── 5de5339c253f0656bcaf92345e09c5409c40754e.nq.gz
    ├── 5f5b9f45c2c0ea8db0d55072e8ed1d8c70ef2bd0.nq.gz
    ├── 5fcfa2e1268b1dfc4a6422ce6da38fc2eadc3e1b.nq.gz
    ├── 618f5e4177cbf32786fb60c87bb70c59663dfde2.nq.gz
    ├── 63e3cadcdd1d0e28923400d0a3f8a2b8d1cfd475.nq.gz
    ├── 64f06d4ed33641f76858a9658638fc4c68329e22.nq.gz
    ├── 6594d748099d6b14084f22daa7a2cbf3c9249295.nq.gz
    ├── 6654d66655e02de021ba1370fa4ec4f787cf3d11.nq.gz
    ├── 66a84a14f7b1dfbe7804898ba8bd4c9829c55102.nq.gz
    ├── 66c28338fe0c426c9265fdd8f1896946a0d9056f.nq.gz
    ├── 69191cb9360292beb2f39a848679d7638a6eb29c.nq.gz
    ├── 6924237c4d0c1c98593fbae4ce8fd4408fe1d5e1.nq.gz
    ├── 69918f71bc439ce47eec8a2b49c359d854643e45.nq.gz
    ├── 6a087ff8912e1db5ca6dd753f4078556fa12b2b4.nq.gz
    ├── 6a369dbd72a22976e8625a7ba40419a839c20f4e.nq.gz
    ├── 6b0a8e2a8ab1aa8124515eeb2c248060f6eb5d4f.nq.gz
    ├── 6cf656be1491c2c6b09f4c69984c4ae91de16a64.nq.gz
    ├── 6da5a095c301ea890c0d742549310416558ad137.nq.gz
    ├── 6dd354411aced9b32018cebde9ab1a13bc23d8ef.nq.gz
    ├── 6ded7a5348875cefd778ce0f8b1573827d33a209.nq.gz
    ├── 6f1a11bc7301655d2840b6c22d891e38b813e4ab.nq.gz
    ├── 6fa6d530d10dd6646e0c6403e5e3c939183c52df.nq.gz
    ├── 70c02eb617c60ba332efd517893fe592d8713e11.nq.gz
    ├── 71aaccb1cb6ba19cfcad9b024a5c4952e8e7d043.nq.gz
    ├── 71b261ce77c1734d0fda2d8786f8b32296d20ade.nq.gz
    ├── 71f3a8c60c0d7b6ba6bcd749a3e4840a858b6a63.nq.gz
    ├── 72893a0aa5ac9c323d11fadcad0b0b2d58bfc081.nq.gz
    ├── 730d4167db0a41047444a0d26e57392fd5c1532d.nq.gz
    ├── 734d7a619c8c024667562f9644905271169d006e.nq.gz
    ├── 735057703b125808b2538549ad7e8571da4baa15.nq.gz
    ├── 739754ccb502fe0486fd13b7470ba803ee1c8dbb.nq.gz
    ├── 74922dab4e64108d9eaddd7782b0ffd1e5c130e6.nq.gz
    ├── 761a1cfbbe1cc93faaafc01230877b2b1b1dab26.nq.gz
    ├── 786f72e8a240fcd0609b273bc5a64e99acef9c94.nq.gz
    ├── 7a56df93acb52daf675a68c95d5eca6861c4a214.nq.gz
    ├── 7affe3242d7f1b8f7bf70aca5b8aab40d23bb398.nq.gz
    ├── 7b3a3601fd12986e89d0553e502d51b281f6fd40.nq.gz
    ├── 7bad6728ff209d1e6aa24374a83ef6b3006e3f54.nq.gz
    ├── 7bf23fe567dde8d4e56fc9b0d321b759fca23fac.nq.gz
    ├── 7c218d1c825ed7f983744894bb1a7ec5ee1fa425.nq.gz
    ├── 7d9f3f1b765f8c4a7d99ae8c04933ed1f6e36a1b.nq.gz
    ├── 7e6b74b2acc9566048e33a7f64ce8df572c1ff32.nq.gz
    ├── 7e80772610dea036f84fd443b07e3b53fea59e09.nq.gz
    ├── 7ee3607fff4c89d7043748ed5699754bb2d2ae1f.nq.gz
    ├── 7ef0a251acd5f5420c89807f934648da5f34f561.nq.gz
    ├── 7f55b9c8a2f79adda36fc37ce89a79929ccfbc42.nq.gz
    ├── 8011c2b204217145649071e970fc3eeae50c8aba.nq.gz
    ├── 80f42d64a86880790a8473bfdb4433e140b76e54.nq.gz
    ├── 8251a83e7f4452b4a9bd0ba541b6b53932cb8fbf.nq.gz
    ├── 833e8c313aa723ff54b54af7b8858d00924c7a1f.nq.gz
    ├── 838b51430fdd18b5face60aca5f37a6ac5c2cc03.nq.gz
    ├── 83ace491c52b932e9f040fa6521d5e7f19e2e42c.nq.gz
    ├── 840e374ce4d4cb3859a5d932d2d1b5d7aeb7bede.nq.gz
    ├── 85bd644983d1a68e8946c5e5b5513a86f3af10d8.nq.gz
    ├── 85ca8d28c6b30b8f6841a59dd7a153c9797260dd.nq.gz
    ├── 85de212d45b4240f7e9eed7be351c6edbc46fd4b.nq.gz
    ├── 86f13d816458630271eed3cb3b64b3d4b1c7e316.nq.gz
    ├── 8717a4d63943378ef9852df00ac3e9d89437bba7.nq.gz
    ├── 87d71aa2bdf099a7ba7edd1a46145a7258931652.nq.gz
    ├── 88276760562cb58bb9bc47fa890e8a3df1125b9b.nq.gz
    ├── 883bf917b143b758559ee33cea68f6627c66a656.nq.gz
    ├── 89e972a17c7ef148e98f34c3a997e10c50d6fd31.nq.gz
    ├── 8a661f8b95e431de16086faf9589602e788df38f.nq.gz
    ├── 8ae6892b4d3853c50e691ddeb57ffe8788a6f920.nq.gz
    ├── 8bd5700fe2079cd74b498d2a141f07c2b92e82af.nq.gz
    └── 8c22d98ff6b627245d32aadf9b10844ca7bf13cb.nq.gz

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

[ansible-collections/community.mongodb](https://github.com/ansible-collections/community.mongodb)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
