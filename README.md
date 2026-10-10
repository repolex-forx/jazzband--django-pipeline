# Repolex Knowledge Graph of jazzband/django-pipeline

RDF knowledge graph data for [jazzband/django-pipeline](https://github.com/jazzband/django-pipeline), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-pipeline
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d404c473f05ccb12959a667da1d8b86710a83fdc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d404c473f05ccb12959a667da1d8b86710a83fdc
│           └── chunk-001.nq.gz
├── blob
│   ├── 046b8f9a7f65eeb5e65f4579ceaa55c472980de1.nq.gz
│   ├── 04eeee8395cd0cf45886f9398d3a347549d8f1bf.nq.gz
│   ├── 0593aa53faad9331808e273e48a206bfb184475a.nq.gz
│   ├── 08ef0d9f0031cb7960686186604f87b9ca061134.nq.gz
│   ├── 09d8e83f4a9254cebbef1549f3f23d315b84f124.nq.gz
│   ├── 0bb176694af141d2573b6a02f0d32ba5e5a8c851.nq.gz
│   ├── 10cb5a29904bea67b5c4820bd2691e46e017889b.nq.gz
│   ├── 13c807c9544d58113c0bf0c4560b33cdfc879efd.nq.gz
│   ├── 184f81aa46e9e6c291b6bb57355c4f76de2367fc.nq.gz
│   ├── 1a32b4876c495630a8362fb129343ad5ae52fffb.nq.gz
│   ├── 2321afb0759841035640bbbafb7922f9143df245.nq.gz
│   ├── 2b54a3c6de1bc198f68b2ade012bb1f04c065762.nq.gz
│   ├── 2ba3105c7778eba5bf91a625ae74db3d7cfb1fc0.nq.gz
│   ├── 2d18794dbaf272835469f188f951698e1bb0a8a3.nq.gz
│   ├── 2dbccb3321dca34182afbe3f1f5d234f6605f1e2.nq.gz
│   ├── 30e87e8b01c239e1dccb8aa51429980214ec7aac.nq.gz
│   ├── 3305e0c1a446674f699281a3bcadaf570f7ecb47.nq.gz
│   ├── 33debfa8b20606e2966a3258c583955e65612d0d.nq.gz
│   ├── 348bc3be5637ae33abfed66cadc643f1df388d60.nq.gz
│   ├── 353005939222ab56e7cf1c2d576c168df70218c8.nq.gz
│   ├── 3d910ae444c9df0d319d54beb64f6e6e911d4083.nq.gz
│   ├── 3ea0434c690e94a4553425dd46b5974d5035a0d6.nq.gz
│   ├── 3f38cca1742712e8936a11df5b6a0d4a7648cf9a.nq.gz
│   ├── 3f78fa5b0fb8663888468154b42efa2df0ced311.nq.gz
│   ├── 4112a85f438432b702c7a908f8cbe9fba47f97ed.nq.gz
│   ├── 41ce62d027e5063e1ff82c184a9080cc395b951f.nq.gz
│   ├── 4421af346da76f195f411610914f8d03235cbdad.nq.gz
│   ├── 456620c91ea451f34541171a318e5992a1738de6.nq.gz
│   ├── 465ce41a5192c7f9740daf4ce0a3e2a2d5670ce2.nq.gz
│   ├── 468864e897058207a36771a7c7c38cedff45a52e.nq.gz
│   ├── 4cded97cd300a9edf145064e51a7cadafe95c1c0.nq.gz
│   ├── 4d609994c6bd397ff50890dc99a59b3b6afdf51b.nq.gz
│   ├── 4de78cc43a49b0df87b9c1212ad29f46db45b3ee.nq.gz
│   ├── 5075b4ed76071256c0e0a72988bf692d4e925765.nq.gz
│   ├── 517d053837d3c047e7765f7244667fe592b78418.nq.gz
│   ├── 570867357301e05d7856860efaed7e3396bd68ab.nq.gz
│   ├── 592bfc2643a1aa3b465aa1b126339fafb40d96cd.nq.gz
│   ├── 5a001c4d2dbc4608bfe71cbd29ba49d4fb43e933.nq.gz
│   ├── 5a2b550a3cdcbfd45970cce6419ea8166f1005ca.nq.gz
│   ├── 5f78289c00488e33e65798f1cdf570c9d3c0c08c.nq.gz
│   ├── 60cc7ca46fe0fb2360987f898e3bc7c58a6002cc.nq.gz
│   ├── 62142d5c473ff424c8094e935049e49ed4609f75.nq.gz
│   ├── 6237a275f96f544190b04feb249f4d9ac9e3d4c8.nq.gz
│   ├── 62d639812e995bac7f833fc4d417db16d4755ad8.nq.gz
│   ├── 63c76ce5747798db7b70fc9bafc1f62cc0cd7412.nq.gz
│   ├── 6529b3ccfc87e587056e4a71e91c5a4912093f8e.nq.gz
│   ├── 6a0a6d076056a03ee32aa017c25e76bd26c184ed.nq.gz
│   ├── 6d3c8d4965958dad77206ce292314da7eb9ca027.nq.gz
│   ├── 6dbca2a2af19c2218e262e8b22f6781f96c54f88.nq.gz
│   ├── 702473f29cba3ca798b725056be4c42e3b555595.nq.gz
│   ├── 722cee046e829d2c3ee21e6b228cd503c71e00de.nq.gz
│   ├── 726d98078926fc1794986378e2d7bc4e185f45a1.nq.gz
│   ├── 72977140221bfaaaa49ee690d9bd962259b228b6.nq.gz
│   ├── 7925319741f34e71135b573dbd11906193a48e73.nq.gz
│   ├── 7955dc05f1d2a5aee60ce6741a7aa43cb5ded2c0.nq.gz
│   ├── 7a264de30c07cccd5f35c6f5cb84ecb7cb687644.nq.gz
│   ├── 7aa1eea56ec56b6a1ed750c27a873ccbad708d74.nq.gz
│   ├── 7effe0ec942d6fb4816d47557ffc04b8e42d8237.nq.gz
│   ├── 81653c6e024f341cdf9e0f22994e84921f017ed8.nq.gz
│   ├── 824c6c3ce82460e61e4a9d12fcc12168c0b611a8.nq.gz
│   ├── 827003a23a371474bb35ad7e47bf6bf5730c6429.nq.gz
│   ├── 8283ffd2d5ac17ba6af07de07388890a95ed5255.nq.gz
│   ├── 82d77ff41b21beed4e337f643f47aacd58e54cbd.nq.gz
│   ├── 83600cf3e95b27004fce2064c64242a04c0bedbf.nq.gz
│   ├── 83b1691495bcb339d7e8bc843915377c3e992809.nq.gz
│   ├── 83d6f479667bf1ca1ab2e1bcc4a894237cf0f915.nq.gz
│   ├── 87baf7ca48b0fdf3d61bd957a00bdca604fe02ec.nq.gz
│   ├── 882d7b36b5bdadf4367c875586a5651b0b0d8b50.nq.gz
│   ├── 8ab90b03c52959de98fbc9fd62efbc85b8206710.nq.gz
│   ├── 8ac6b8c4984dcd382e54c7923325af6d226ca3df.nq.gz
│   ├── 8adac3cc972a72c89ea772e5f8076cba628a06e7.nq.gz
│   ├── 8ca9cd9eb5747e6102ec75dd0bf8f1c7894bcbaa.nq.gz
│   ├── 92c871027e31c4b2c40d9e5ec48a57e59704e621.nq.gz
│   ├── 93faa632a579a8a55806b7292e1c8920d5e4d49a.nq.gz
│   ├── 95f609935da0e9d2c84d662d0110f8af5b42d78a.nq.gz
│   ├── 9ee79765fcc5d08af74909ad09cc0ddeabb82059.nq.gz
│   ├── a20f4c63fd7eb8c925f972e7209469a08a5a6ba9.nq.gz
│   ├── a3015d496315d503e833dc3fa15aceb4443df35e.nq.gz
│   ├── a31022c79a4a20c41a16d39860bd2952317061d5.nq.gz
│   ├── a36643e54b99f28c982381282e71aafb5bdcab4b.nq.gz
│   ├── a37eb01b6727fc65eb49d5fce94d9bf1ad39ab0b.nq.gz
│   ├── a3dd76e5b466022997fd6041e332ea74c1e2d412.nq.gz
│   ├── a8e7105c587272a87e2ee59cd1dd11b08a00c24f.nq.gz
│   ├── a98a545adb84b05c9c6ed5c3af7f2978921612bc.nq.gz
│   ├── aa2be8beec7dccbfc0262fa30476dc6acfd41e00.nq.gz
│   ├── acaa8cfc07d26c2b422224480f2efa495be6382d.nq.gz
│   ├── add1832836fa9d7f2c68dbaf58479f6bb615085b.nq.gz
│   ├── b041ea32613847877fa7d3727411ca49d8239ba5.nq.gz
│   ├── b2d7179e68182a33b610ee33a196aa35e7683d21.nq.gz
│   ├── b5de2444a7236a08554adca8e01f9f6c9c912a1c.nq.gz
│   ├── b665d239358005d03e386beff0e123a5c382e017.nq.gz
│   ├── b76fd94d891a2569a3e7de0310f74f9112e14fd0.nq.gz
│   ├── b801ac8c8cac4dfcc4b785c202fd99ca913fec1e.nq.gz
│   ├── b84b51e7576f54b61c2ef4ce73c68a3238eba247.nq.gz
│   ├── b88948577f2c80ac58cb1179891063667adcee4c.nq.gz
│   ├── bba21d1c222ab33b9d34ea6a9f666f66834ee674.nq.gz
│   ├── bcd7420d5be1f49a3209aa0136dc3cc454ec9214.nq.gz
│   ├── bf1c16fd7dabb0adbea501a5911b562033457c02.nq.gz
│   ├── c26922207b382f4d997fbf05e38a4f89b05b0d09.nq.gz
│   ├── c3815fb6dee8bdd405c45f6c8d1fb5e84344dc0c.nq.gz
│   ├── c9a71788cb5bc714a22441a3bc059630e1019ff0.nq.gz
│   ├── ca53c4324ea8deaed8b96f690f5eb6f71dba94a0.nq.gz
│   ├── cbac67343f0e7414ef55bf51fc65619eee9abfd7.nq.gz
│   ├── d35fcc76befe22238f793272c3a007a7d375f9ce.nq.gz
│   ├── d40e7dc06d309540cef77a1e1c769cdc9dd3df87.nq.gz
│   ├── d427430cca6f817133db9d7198952f9d22f39823.nq.gz
│   ├── d564b5673d9b5fab7453534c933729da4153ab10.nq.gz
│   ├── da0615bf6ed522192835e0f3face0d073ef453ca.nq.gz
│   ├── e084b238a49fac4114036133b10fe7115edcc93e.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e576514de7554a156bbe4bc5ed4bedc42168b876.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eaf670d147377b4cfc53196cfa1aa2d77bcac449.nq.gz
│   ├── ee38c52c444faa2a97e4365657d6d3d0bc89cba7.nq.gz
│   ├── f23de09465e01f4875f0812a2205de7016ce9f97.nq.gz
│   ├── f271f5b6f4d22aa682a6b6072f1a46c0cc7bf4b8.nq.gz
│   ├── f37adb367b44627741a23703e3da6dbc3e14b036.nq.gz
│   ├── f41423255c4d8b3b534c4e316c709e1aca814d39.nq.gz
│   ├── f4eae6a650c24a6fc117885124563f5bef2e5fc5.nq.gz
│   ├── fb54d7e7ea090359919df1c133ae957bd77121cf.nq.gz
│   ├── fdbe9a4a78fbed6c3ae0b3d3dbc45401dee716c5.nq.gz
│   └── feabc7bc5f26df8f9da86c357ccd30c2b0fd5204.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d404c473f05ccb12959a667da1d8b86710a83fdc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 130 files
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

[jazzband/django-pipeline](https://github.com/jazzband/django-pipeline)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
