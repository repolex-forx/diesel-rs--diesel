# Repolex Knowledge Graph of diesel-rs/diesel

RDF knowledge graph data for [diesel-rs/diesel](https://github.com/diesel-rs/diesel), parsed by [repolex](https://repolex.ai).

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
rlex download diesel-rs/diesel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 07a80d4e9f32d62bec3d425d85c1ef5b8cddc80d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9311439c61a0d5d35312990a889227a41e1f183d
│   │   │   └── chunk-001.nq.gz
│   │   └── 9628f5ca470dea2adaa8194365541e304e3d56dc
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 07a80d4e9f32d62bec3d425d85c1ef5b8cddc80d.nq.gz
│   │   └── 9628f5ca470dea2adaa8194365541e304e3d56dc.nq.gz
│   └── repolex
│       └── 07a80d4e9f32d62bec3d425d85c1ef5b8cddc80d
│           └── chunk-001.nq.gz
└── blob
    ├── 006355c819b6dd8236a5c127a9f1b253e1821f94.nq.gz
    ├── 0064005eeaf957cca1b036a802096498b8b8c52d.nq.gz
    ├── 00afe5ecf6bc4d9e022a01210c9430a53189b517.nq.gz
    ├── 00e865609ad9ae896965e9553223f2ad1f384bb9.nq.gz
    ├── 00f52b32ec7be9fc57685e26001f3b9f5fdbe9f2.nq.gz
    ├── 00ffd46c4b96b137b6b3bb02bc41a744f8a5d5d0.nq.gz
    ├── 0104aa4ee47073fdcc5b9f618f1fb8bf7ccc8a8e.nq.gz
    ├── 010ffafcc778c2a5e64b9dbc2bb636fdca54950f.nq.gz
    ├── 012748f7bffe32c27aa3150717a59d57d7604e72.nq.gz
    ├── 013e9b838eede06954a36b0e9776cb861c84b3cb.nq.gz
    ├── 015abb203e3544eec03dd270835b70c099ec46a4.nq.gz
    ├── 018068a3d3251c70ad628d6d166685f905aa3b4f.nq.gz
    ├── 01b838e5f809da5588d9750323448ef89a64fa6e.nq.gz
    ├── 01e8f253582e3989e7cca5bce6fa6c6c557e702a.nq.gz
    ├── 01fbb0a5ef21ae04e236d4a11c367d739f27b7da.nq.gz
    ├── 02210e996b76f7efbcc0c879f136f56ee7274c38.nq.gz
    ├── 02256466ef98803a9e85cbf21e635287264c66b8.nq.gz
    ├── 024210b546d1eea75e09ee8c615696da8f7004f0.nq.gz
    ├── 025ab11ea069ea43ba65e63376fce645cbb22562.nq.gz
    ├── 025c8da9e869613998154eee25c750b73f7f5adb.nq.gz
    ├── 02d488b9bd9f97f3a6b274a3b541e096b187401f.nq.gz
    ├── 02edab392a24b901e2819d4e4085a979e2e0f9a1.nq.gz
    ├── 02f402149801c5eb25921f4b93bcd33bc37dafb0.nq.gz
    ├── 033794341e115f15d9506587faa8f4794e188e88.nq.gz
    ├── 035391c588960ebd663e5cd23d5e9b3976103205.nq.gz
    ├── 0374fa06440e8f66b90c59799d266c2b26613cb3.nq.gz
    ├── 03852500b3e4eb309b343d5c81e91f7db92000f1.nq.gz
    ├── 03a1d1831cfb324b422b7f65a6ab3e580b823cea.nq.gz
    ├── 03b7fc8f5f881d2bd60eeb6e3d4d7fc1abbd468d.nq.gz
    ├── 03e7e9864f65614a06c4cb37dd1be6edcf434031.nq.gz
    ├── 03ed1655366a0f94db13548a2031e10c8d9edc2a.nq.gz
    ├── 045a9c819050b30b41fd86fd5b58f2ef1bd61922.nq.gz
    ├── 045b9de702094b114175952e914c644ca53802ca.nq.gz
    ├── 04674de1c311f6e7bc919469cae694f86ca03b2b.nq.gz
    ├── 047187b314bc8e108705a277e058d0609204309d.nq.gz
    ├── 04780584e523c276d0323cc92ce101583d08b8f8.nq.gz
    ├── 04803cec39fc397572cd5becac531277045c6d20.nq.gz
    ├── 0483a8f956ec6c60f6614e848454600926754815.nq.gz
    ├── 04cff9f08552ca737cd8050a3e77fc9fe8bad78b.nq.gz
    ├── 055d8d24aa72d4dbee86892f882b47aba132a2ae.nq.gz
    ├── 05c84a05515d9aa57f0851ca1a572934934924e4.nq.gz
    ├── 061d0ae88b16ef5aa9811349c4e08cd10700df3d.nq.gz
    ├── 066a6d09f03b1131825d1875ea84485cb3e18fb1.nq.gz
    ├── 066e93d95e281355a0ad32c4d3f5f6c150f56b9c.nq.gz
    ├── 0680c88cbf80ba2c4d7e15e95cea54c04620355c.nq.gz
    ├── 074c8f8b7afd1c7de95b94112d1ad4b57af37056.nq.gz
    ├── 075e34f9b27f3e8872f27b29abc6acf2034a37cd.nq.gz
    ├── 0764fbf46a858eb4e4c5d4ee21bb7ea2813ac8aa.nq.gz
    ├── 0776054b358f3e1585c263fe001df63d1ad24e24.nq.gz
    ├── 0777ca23a03992d23333427da476db4f31aca393.nq.gz
    ├── 07a52ef125f9da3db50ccb7a9f24523670c6340f.nq.gz
    ├── 07db94d447a4cd02def772d64ce8d93dbdeeb595.nq.gz
    ├── 07faf83e2bc5c54d32305da695fa1044426788b8.nq.gz
    ├── 0813f33eedb3f8bbef16e12fdcb03f8f927d8e5e.nq.gz
    ├── 0845c1bc36b411319e0e7a4215884632ceae403d.nq.gz
    ├── 084c3d77592f0536f4536d8b290a7a04b7b9e054.nq.gz
    ├── 0859affb050eb6d985c00fcfd892f01a213a7cc5.nq.gz
    ├── 08be469a96a5018e44064e1215d641578b17e1d5.nq.gz
    ├── 08c4cca233d17b07382684015fd3d9b1a3e5cb09.nq.gz
    ├── 08dfd72eaafb2cbc5bb169598ec697e0a43bf804.nq.gz
    ├── 08f177f86b53724addedb0273f35882c022abfff.nq.gz
    ├── 091cc2f9d7b95bcaf6c396bb72064760dd26fd5d.nq.gz
    ├── 097e7ab5eb21919be4f5a292b24b60cb3be82e29.nq.gz
    ├── 098bdc4452e9add49774d3651fdca99ba51a9e2d.nq.gz
    ├── 09a166d7c0c72b173f27d9e2466693684fcd9f1a.nq.gz
    ├── 0a1706fd2051ffc906802df02e529ff4fa110f44.nq.gz
    ├── 0b25a7b13fd799b576b0f8b55b9e3796f857c210.nq.gz
    ├── 0b2bb704a52c6e0e1d78b15ea8447f3420949fae.nq.gz
    ├── 0b6f2d2e5e382d4671093654214d6dca7be48074.nq.gz
    ├── 0b83295789688063c7bd7512a2d8088a8b61e255.nq.gz
    ├── 0b9cd06866f8f86abd1747dbf3ed3bdd6ee8f8d2.nq.gz
    ├── 0bdcb374f890f420a85fa08464a8eae957ac8f66.nq.gz
    ├── 0c286f29a820b8f78c45e0e95869a424e6dbddd6.nq.gz
    ├── 0c3cb1b956a464ccbe7c91c85314663071868f64.nq.gz
    ├── 0c4111dc831f43610304ad04e803f9af23812f45.nq.gz
    ├── 0c5b75e16470e4a0ed91e0d875b7283ba307046d.nq.gz
    ├── 0c60d368b555c80496e39519d3e8545f09c098f9.nq.gz
    ├── 0c819f54899a68c3f40f5a64658bbd38d8dbb086.nq.gz
    ├── 0e071565f2e78411952b451c417dd17f9ba9c823.nq.gz
    ├── 0ec554e37542395229fb8dcb5472ed096f368252.nq.gz
    ├── 0ee76e3a5c93a92a38ef8ef0e864561372f130fa.nq.gz
    ├── 0f68f277b93c28a84c42a7ace1cdb054cd00a633.nq.gz
    ├── 0f7093128bf47affe0c22cda8faf5dc3c77e465c.nq.gz
    ├── 0f7bd11497d20802f18e1d25e53c2caf732d93b0.nq.gz
    ├── 0f8d10baa63e104fd7ccee209d40c7bbe17b3419.nq.gz
    ├── 0fc286834eebeb60124891fa0fac0fa4f124a6b1.nq.gz
    ├── 0fed4b73405079f0176a5c87a95c3a2b307ccc67.nq.gz
    ├── 10592bf1633908d2f9002a5e9a5507438d44be58.nq.gz
    ├── 107330f33ef0508301aa10f73c5b0ce024954bc9.nq.gz
    ├── 1076f8ab732602ff3d53ff61a0f40ad4f26a6a8a.nq.gz
    ├── 109c58690818edc511be608186147ae64b0d28d8.nq.gz
    ├── 10a80815535e3565a5110c8332b55c7a6db3ac55.nq.gz
    ├── 10e86f9b2ff2ee3c61714ed80c6659a4778941a3.nq.gz
    ├── 1119e369b8a1428986869eb198c3ac604f0ed6c8.nq.gz
    ├── 1135e76a6cde94a744cc17d8bec66e6c8a31f15e.nq.gz
    ├── 1136b6f9e9fb0acdfb7cc47791ce2ba24bb2ab18.nq.gz
    ├── 1151652a290de2f1e24d72270e00f0fa74785cdf.nq.gz
    ├── 11be1b0e151b7172af22b13fd2c35b49214b1c19.nq.gz
    ├── 124603dce690c6c699f69af4d3ff740dd20ddba0.nq.gz
    ├── 125cda7bdaca7343727fb84709cb0e34702fc875.nq.gz
    ├── 127cf4845de11c26789bb55bb53cd34e949be773.nq.gz
    ├── 12819dcaf8b7d37187ee82772f56623f563ae2fe.nq.gz
    ├── 129c42fb65991f91540827acf09fe652dbd3c234.nq.gz
    ├── 129eb548be2c59cd811539756de3ca2dcbb7bbd4.nq.gz
    ├── 12a8b7ba9df5761deea7edd3cef2151629125c8a.nq.gz
    ├── 12b6189e9bd2bc2721f2b3a3bb58dffd1de203f5.nq.gz
    ├── 12f7f88fd80192667bf77655110ff5088f8e826a.nq.gz
    ├── 13337e1e5a520e800db1d0b3cb7edf61e3a1b4a2.nq.gz
    ├── 1356f0468ec6f25b9e7c36bc08f279fbbcf70d03.nq.gz
    ├── 137cbe0539d77f3ebbf9ff8cb2a664ff4ae31b4a.nq.gz
    ├── 138a8a639610bfcc6da3f4819245a5f85cdfbb57.nq.gz
    ├── 13befeea1e9bf9a677967e5c6f3ac5a641556e28.nq.gz
    ├── 13d151d4b1c5bffa862b19e5e5eacdc6a2722b34.nq.gz
    ├── 13df19cfbd2067c6710f2d1b3fd3e31b467387e5.nq.gz
    ├── 13e51bc17a1e4a20fb97f0f62d99d979afa9d0bd.nq.gz
    ├── 14036056a044a77fd88092d3dd47f7a7a859a46e.nq.gz
    ├── 144c9eeb6aa8b52c4d2bb777a2f98ba27418aeee.nq.gz
    ├── 1457a0c8b9386a7dd6315c30a7d5b6c56745dfc7.nq.gz
    ├── 1470ee455dc6af1479ddbac8fcb541cd63f0ee03.nq.gz
    ├── 14928f83ba95d9521bb1f3fd92ce4772b47df464.nq.gz
    ├── 14a0a6554aeec4a6b3e13ad79fafb002a3c70fd8.nq.gz
    ├── 14ac8eef10b8ef7e5a40a1c1fbf59b5a305ef16c.nq.gz
    ├── 14b3bdc75495d629098d724ace4bc14dc2e0bd7c.nq.gz
    ├── 14bb0c2e22e85cc63026ae2ffb39c5496f0b6012.nq.gz
    ├── 14d8142d6e3e85bbac9592449766e878bb94e600.nq.gz
    ├── 14da8803f9dba2234268f296e021504f95ef02c1.nq.gz
    ├── 1517f63a4e0279e2b04b07bfd8e74ee3ae28aa52.nq.gz
    ├── 15223d7122f05d3fb2b928835b95bdb8bebb7e00.nq.gz
    ├── 153ee5bdb453be3439333f135903ecd7daf0a731.nq.gz
    ├── 1599221b3c6b837c5a73b68590a0d0847c52d5a0.nq.gz
    ├── 15ff18f51d5ad4a6665e2e311f5f44341ac3a66b.nq.gz
    ├── 1651d895497d8728f2af5f1e417b8ffd73e3aa67.nq.gz
    ├── 165ff54343d2f9a55fd956546e1b89fffdc35ca1.nq.gz
    ├── 166e051936d5cf27ba552ad029550b4057bf88b2.nq.gz
    ├── 1687f6c7b2b6a3cf1d472e3a43c3962e51d663ce.nq.gz
    ├── 169c7de3247ed5f895b77c731010d6f19e5e5daf.nq.gz
    ├── 16aeb18d58e3f7affedce2c59d30065f64106e4d.nq.gz
    ├── 16de9d2dcf63afd24889b41dd655a9127e029868.nq.gz
    ├── 16ec2da0440f43617d3b6659cdee3806dfc0d79c.nq.gz
    ├── 16ffe227dcc2e5d13fc052cd07f7116fcdf8d6bc.nq.gz
    ├── 1715a36e361832a5afa99593cc652741835e7603.nq.gz
    ├── 174017d6e0c0cdf730b3c379af2e5dda6da86a5a.nq.gz
    ├── 174d341946d24dab06217e4dc10d29bd2bb24492.nq.gz
    ├── 175281cee6c54f0de8cff5ea2561de00683df44a.nq.gz
    ├── 17580de495d6b7247e5e14ffb001ee4917b204c7.nq.gz
    ├── 175f82a4b7614f3315a671073711ac94327206aa.nq.gz
    ├── 17689cb6a3be27e026a8b53dbcbec38a302866df.nq.gz
    ├── 176db110356f121cb0e2972d3ddb5070af04e68b.nq.gz
    ├── 17c48ca6ff6fc3ac68f7c9e3e2967612f9effcf7.nq.gz
    ├── 1859f7db79a019e4adeaebf0e98a1bfc88b8c774.nq.gz
    ├── 186b198e34aaf25baed836ae1e63db4ea6d2b90c.nq.gz
    ├── 187bdf6d3b12f0eccb7b94bedb7d04cf894010e7.nq.gz
    ├── 189e14ed97115cd5784ece50b208624296297d61.nq.gz
    ├── 18b39a6f70942eba241c5fd6aeaa7de90dd847cb.nq.gz
    ├── 18d588c00e3e34dba3d0fccbc5d47591ad6de9e0.nq.gz
    ├── 1905f60aaeecf93bffc0c110db33a31d0daa6062.nq.gz
    ├── 19104efd91d4426d49fef197e6525e26de4e9f22.nq.gz
    ├── 19156a1bd90f7f4d4fc1a080c787343d5949b745.nq.gz
    ├── 1936d543d69fcb382727efb5839ea7043383c8fd.nq.gz
    ├── 19680c728e7cd9ff0f7453d13a90880c58e05185.nq.gz
    ├── 19d4a49baac6b5a969340c4daced11d09f44de87.nq.gz
    ├── 19fa76f5de1eea5c0328a5ef70a45b52a819ba6a.nq.gz
    ├── 1a27d5e5d970313dc8a61013276c9471290e4b15.nq.gz
    ├── 1a43c7fcf8034eb9c66d3641c849a108c0582bf1.nq.gz
    ├── 1aa809a91b0aa5c7c69fae74071e553c77d7353b.nq.gz
    ├── 1b07e5cfea788f9b156b25d2f6cfdfd25fb51f22.nq.gz
    ├── 1b16a505cd47657818a43b97bbcd818515e8b03d.nq.gz
    ├── 1b16df8e0d7efeeb4d6e5b30a5b7a012512281b9.nq.gz
    ├── 1b3cd460f828effcfc66c9554fb4c29bd2af0393.nq.gz
    ├── 1b8c4d93062b39a4ff88ab7f7f805486fab197ef.nq.gz
    ├── 1bae0cd9c5bad9281ab14200f2c2a41474f8d358.nq.gz
    ├── 1bb8883ad16dac070c3f835e15e7ece4a9806cf8.nq.gz
    ├── 1c3134be4e303ac79ad975c715379031cb1ae650.nq.gz
    ├── 1cce25070040cbb05fabfde5c62f1fd0bcc47d58.nq.gz
    ├── 1cd601d0a3affae83854be02a0afdec3b7a9ec4d.nq.gz
    ├── 1cdffb21f0c9239e897f12a29e53656dfaa8f0ce.nq.gz
    ├── 1d0321e1b70e861111663131e6f3a03d77fa2865.nq.gz
    ├── 1d4ebd9d82e854bb62c95bd311bb4901c23b00ab.nq.gz
    ├── 1d6e062357f7cd62aa32c027a88cc1973e5a5e55.nq.gz
    ├── 1dff0b3a954d8b2269db9f9f055a353b39a3e924.nq.gz
    ├── 1e4d1b53534ee1d205632bec3f3b46a1da92724e.nq.gz
    ├── 1e52dcdefb5285dead81a5a9bdce7795528837fb.nq.gz
    ├── 1e64f995d2973f91a9cb6792e7a4eee347399a19.nq.gz
    ├── 1e79168a37a2c49ac3a7b10d867d9bb83cb4c1fd.nq.gz
    ├── 1f0e29732f5084c2f22fc4572715a96ab9f8166b.nq.gz
    ├── 1f1720b8141bef561bbeaf24530ed568c93515ac.nq.gz
    ├── 1f3c259f9b190ea5dc33202398f5843edb81805c.nq.gz
    ├── 1f5801887e5fc3c34b228f346ecbc038c66a781f.nq.gz
    ├── 1f92dfeca8091fbfcfda70998eeeebd789376736.nq.gz
    ├── 1fa12fbe974bc9e791b9080c32a9da99fe5c602c.nq.gz
    ├── 1fc9be7aec09919be301ba524604d8c2f5ce48f9.nq.gz
    ├── 1fe1783c0a97c2d6ee89d70504cb60fbd3c62648.nq.gz
    ├── 1ffd74c1e45887ba671a336082fa55860b221c0c.nq.gz
    └── 20296cf53396097502db182dc85b966dd0e4625a.nq.gz

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

[diesel-rs/diesel](https://github.com/diesel-rs/diesel)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
