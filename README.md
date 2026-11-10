# Repolex Knowledge Graph of paupino/rust-decimal

RDF knowledge graph data for [paupino/rust-decimal](https://github.com/paupino/rust-decimal), parsed by [repolex](https://repolex.ai).

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
rlex download paupino/rust-decimal
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a7f0216e837f3f3973759e7e9fae28783d33ed77
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a7f0216e837f3f3973759e7e9fae28783d33ed77
│           └── chunk-001.nq.gz
├── blob
│   ├── 03b9e01e6a287bbf3f2e56a59fe1fdd0bcd93532.nq.gz
│   ├── 06ab8d22cddc739347dd2b4a7d22f99913075856.nq.gz
│   ├── 07289b271db2512a1a4d726df3ea305665f5e6f7.nq.gz
│   ├── 080f78e26c3cfaddd1d7702ca90f83bf22b5e069.nq.gz
│   ├── 09d26cabed5239dceb794319523a48b886de0470.nq.gz
│   ├── 0adfe5319740c9f62404d8b0dd95908f023d4f5d.nq.gz
│   ├── 0cac371a14c804eb06a543e4791c0ed032532804.nq.gz
│   ├── 0fd93c33220b1e047839a14d683ee58c70a7c6d7.nq.gz
│   ├── 1084301ee098715ec829da48022d57bc1feddd9c.nq.gz
│   ├── 118d5ea58245834c8144083664d279911d8a7555.nq.gz
│   ├── 168950a0f74d3c9691c0b68245bb87e987a5dad9.nq.gz
│   ├── 1e4a2d8dfd68b2eb45eec4b0aeaf138d1a680aac.nq.gz
│   ├── 1faabdd184b9bed3028b6cf514927cc7edb46769.nq.gz
│   ├── 2110186b52a68692d3ddf27da47544121187ed91.nq.gz
│   ├── 254b105046dd9dbbf168a3cc884b8794bbf37e4a.nq.gz
│   ├── 27d86a9f00aadcc9ddd29c59b49a3dded38a2813.nq.gz
│   ├── 288592d02f1faf89de7047ccce73f5ed3c3acf63.nq.gz
│   ├── 2e72704040b5d5d71aaf904e059395c3dd63b26b.nq.gz
│   ├── 2ec61c11689bcc75da2c2fb0587efb6df45b6bda.nq.gz
│   ├── 2f5e99844932cce9bddcf898cd1ea4c687abfc69.nq.gz
│   ├── 3501da6465c4d18c3a148b745f38ee478ec9ee26.nq.gz
│   ├── 35f92e34be5eff3b5d02b8e820f6091bc3a0813e.nq.gz
│   ├── 3739bb617693ef7069278b75a640a9e38bb40fb2.nq.gz
│   ├── 38edc8f9309f77c2e2e95400dc8ebd156ba92412.nq.gz
│   ├── 391ff554277bd9f7c678437d2d79b04ea3e870a1.nq.gz
│   ├── 3a3f7afec1a4a9ed774d93fd31b7a41917cefd60.nq.gz
│   ├── 3d04f7131e60df0681f9856c8099960c15f0f64a.nq.gz
│   ├── 3dd1af6ac5f396841349ebe8703b9abe3d0cdd09.nq.gz
│   ├── 4082c101b398630511dc1159de57e6ecda3794c4.nq.gz
│   ├── 489f8f5a1de2e8944b1d29ca2758bc506809504d.nq.gz
│   ├── 4bb41d89e9f15173d6de8a53a23e58a985058bc7.nq.gz
│   ├── 4ca6d0166997307ca317accf426560c64902b06e.nq.gz
│   ├── 4e5fe2729bcc81b010662d61bc4bdafa90c75d81.nq.gz
│   ├── 539f839f5cc2026a8943b175eb51fa347386bf32.nq.gz
│   ├── 561319343b5e789d1b7f9eeb6dc447580952a928.nq.gz
│   ├── 5823947dbb36e838453e6a7e28b90da6366ffeaa.nq.gz
│   ├── 5abca7ce6bdf392e345a01b84f042df40f74bb36.nq.gz
│   ├── 5d34f9422a992e726bef46cb88669329d8f44240.nq.gz
│   ├── 60a3450ae1e5f613ce299b2c8fc4e0ed84047d73.nq.gz
│   ├── 62babd9c229dbc866d92165bf2b5ae0ef97125b2.nq.gz
│   ├── 636085bff544af8dcaaaab165c65e812ba3c97db.nq.gz
│   ├── 68364efa4e57390dc3a4f6ce64f0816b34305ca3.nq.gz
│   ├── 6b26614452985fec0aa83360bb6e83502afd9551.nq.gz
│   ├── 6d014aab46367dfc9a33de70141b3aed464731f9.nq.gz
│   ├── 6e0f0937648bc0a68e946b936dbf7cd39de54a71.nq.gz
│   ├── 7327ea5d7ed8c00121ec7561297a71551ab20d72.nq.gz
│   ├── 73d8b92ee3df3272ccc7204df842360aa085a477.nq.gz
│   ├── 74a2046d9e1b302029eeabe5d8486e7954d8e90f.nq.gz
│   ├── 785b05b7203d007856939f364cb2ea3e8b115e24.nq.gz
│   ├── 78fa0f4e51f0c5e953f1af148e2300fbf8cef318.nq.gz
│   ├── 793bc43c552373fc2d09ffed186606b7a0f5df3c.nq.gz
│   ├── 796e51d39d0f87e331e07f3396e483e40e0a3f8c.nq.gz
│   ├── 7a20529890d067e5109785c616a321d9f431b574.nq.gz
│   ├── 7a8dff4001c9f59e17fc08756119d0b7be3a41d5.nq.gz
│   ├── 7b6454d59b5628d116fe41b9b0c5fcece0821c54.nq.gz
│   ├── 7b86ac24c0f9ffed5e3e5a172b31836c141a3a49.nq.gz
│   ├── 7c67da587971b6ff1b406e70d895b6fccd4fe8ca.nq.gz
│   ├── 7d011e62100e401d42e258802efada014393dbec.nq.gz
│   ├── 84f080adfa8eedffdfc265802f0766fba0448bc3.nq.gz
│   ├── 866c75610557c1ec858a56438df569401967eb38.nq.gz
│   ├── 86d92f9d9b500aed3fd0d8b369b4486b079b5b14.nq.gz
│   ├── 8999787b395b0ba6a5d90dd833c42ef270d8569f.nq.gz
│   ├── 8c740fc623b8d41d35a82f45c90f8d43b166fe1a.nq.gz
│   ├── 91f5177fff5d9c63f33bdd38ad25b23d7b7db83c.nq.gz
│   ├── 94dd8dd3a7964febeaffa1ccf107a1431d941a74.nq.gz
│   ├── 9590a79a263009551dc56f7f85486b7ca59c7329.nq.gz
│   ├── 97cff8d1b6e088172af3ed7788b25c65a8cf2a56.nq.gz
│   ├── 988e9fad1a2794d07b08903b4721c192a71de58e.nq.gz
│   ├── 9f5267dcf6a873a8410df9ec9d6e28c5a0b35d9e.nq.gz
│   ├── a1bc9f22a7271c0a1536b026af2190fb70ac5e57.nq.gz
│   ├── a8b410d241ab168030751eab4d01dfbf39a05847.nq.gz
│   ├── a96280ad3b4c16698e4d5327918c6b8bc140d454.nq.gz
│   ├── aebf4fbb60a915dc89e311d2983a01703c491614.nq.gz
│   ├── af0203fe44a350c5293dd00a8ec7a96d2b81acd0.nq.gz
│   ├── b2d7010d50a0ceb89e37da07581ac497b0fad90d.nq.gz
│   ├── b320c4d0360af42a7401ad0d592a6af18d8af503.nq.gz
│   ├── b38a474c4d0923f68c5cf3642e9702e7e44465ee.nq.gz
│   ├── b5a6cbbfd4f7807f58db9250609f0cbe0e72e252.nq.gz
│   ├── c26a82e09c6205da281babdc09fd5f8199765808.nq.gz
│   ├── c5aa469c27e2c178743589d8a06a317c3e8b01b6.nq.gz
│   ├── c86080edf95e0d07290638b1bd99bb60badc5685.nq.gz
│   ├── cb40b410d3806f7d2f4bf35ab7a98fe0ba5fcc03.nq.gz
│   ├── cb5ac59537f608f9fc61ccf37eed2f586fb17222.nq.gz
│   ├── cbdf40e2bc6828eab6bbdc367fba52c59de70acb.nq.gz
│   ├── cd9007e89a3b1f730c6d4e19b97ddf063bac06f6.nq.gz
│   ├── d175c6f15fee4ff45cd48540e52c2496624b7839.nq.gz
│   ├── d1a8e94077ee529a680492a9460190b564bb0da7.nq.gz
│   ├── da0126a54016b7693e286eb5ccd5c784d6685390.nq.gz
│   ├── ddb215c293894bdb089e3a1652106502c2bae042.nq.gz
│   ├── dfc1ca6073378a807e83a98f4363d5c428c48fbf.nq.gz
│   ├── e664ac4c78b416e5843d53d9da65a22f8410de30.nq.gz
│   ├── e83564fba21688f16d33513920d343cdbf19c1b0.nq.gz
│   ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
│   ├── ecafc17eb6a67a46af8c9c828759391918b1f876.nq.gz
│   ├── ecc7b40ebb137b4b1cc5b49273d4168939d1f736.nq.gz
│   ├── ed2cffca48bd854af1e3c1815985a2098a14ae76.nq.gz
│   ├── ee200d1ebbcdf13ab4e0bbb6aee46d9dfe309cf2.nq.gz
│   ├── f0022cd58c608feabbe2112aedfe4a97b87c29d5.nq.gz
│   ├── f0045468964b9b8a78d0cd18ea7a97a329a0f3d4.nq.gz
│   ├── f3cbd09391e64f06ad6777cf12aec3eeac256520.nq.gz
│   ├── f7c5859ad14ea69e035fc78361033ea1cf199d98.nq.gz
│   └── fc72123011f116bb6ea314148dacd74973ae82f5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a7f0216e837f3f3973759e7e9fae28783d33ed77.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 110 files
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

[paupino/rust-decimal](https://github.com/paupino/rust-decimal)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
