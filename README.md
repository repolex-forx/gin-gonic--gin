# Repolex Knowledge Graph of gin-gonic/gin

RDF knowledge graph data for [gin-gonic/gin](https://github.com/gin-gonic/gin), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download gin-gonic/gin
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 15ced05c5316609bce5b43389f8e3f06102a8b18.nq.gz
│   │   ├── 4ea0e648e38a63d6caff14100f5eab5c50912bcd.nq.gz
│   │   ├── 6a2a26093d046d8ea92542a0fb38721c4ee40bd5.nq.gz
│   │   ├── 6a8b8b6651a228590bbc42145483ff864f4f6e89.nq.gz
│   │   ├── 6ad6205e9c94a4b8a320219e28c37c29d22a7a2c.nq.gz
│   │   ├── 73726dc606796a025971fe451f0aa6f1b9b847f6.nq.gz
│   │   ├── 84d927b8ad57ed9e1cda240b41fa2eed55066103.nq.gz
│   │   ├── b5af7796535d97d9c7af42539af01d787fcb3b4d.nq.gz
│   │   ├── b75d67cd51eb53c3c3a2fc406524c940021ffbda.nq.gz
│   │   ├── b869fe1415e4b9eb52f247441830d502aece2d4d.nq.gz
│   │   └── e2212d40c62a98b388a5eb48ecbdcf88534688ba.nq.gz
│   ├── dataflow
│   │   ├── 15ced05c5316609bce5b43389f8e3f06102a8b18.nq.gz
│   │   ├── 4ea0e648e38a63d6caff14100f5eab5c50912bcd.nq.gz
│   │   ├── 6a2a26093d046d8ea92542a0fb38721c4ee40bd5.nq.gz
│   │   ├── 6a8b8b6651a228590bbc42145483ff864f4f6e89.nq.gz
│   │   ├── 6ad6205e9c94a4b8a320219e28c37c29d22a7a2c.nq.gz
│   │   ├── 73726dc606796a025971fe451f0aa6f1b9b847f6.nq.gz
│   │   ├── 84d927b8ad57ed9e1cda240b41fa2eed55066103.nq.gz
│   │   ├── b5af7796535d97d9c7af42539af01d787fcb3b4d.nq.gz
│   │   ├── b75d67cd51eb53c3c3a2fc406524c940021ffbda.nq.gz
│   │   ├── b869fe1415e4b9eb52f247441830d502aece2d4d.nq.gz
│   │   └── e2212d40c62a98b388a5eb48ecbdcf88534688ba.nq.gz
│   ├── lsp
│   │   ├── 15ced05c5316609bce5b43389f8e3f06102a8b18.nq.gz
│   │   ├── 4ea0e648e38a63d6caff14100f5eab5c50912bcd.nq.gz
│   │   ├── 6a2a26093d046d8ea92542a0fb38721c4ee40bd5.nq.gz
│   │   ├── 6a8b8b6651a228590bbc42145483ff864f4f6e89.nq.gz
│   │   ├── 6ad6205e9c94a4b8a320219e28c37c29d22a7a2c.nq.gz
│   │   ├── 73726dc606796a025971fe451f0aa6f1b9b847f6.nq.gz
│   │   ├── 84d927b8ad57ed9e1cda240b41fa2eed55066103.nq.gz
│   │   ├── b5af7796535d97d9c7af42539af01d787fcb3b4d.nq.gz
│   │   ├── b75d67cd51eb53c3c3a2fc406524c940021ffbda.nq.gz
│   │   ├── b869fe1415e4b9eb52f247441830d502aece2d4d.nq.gz
│   │   └── e2212d40c62a98b388a5eb48ecbdcf88534688ba.nq.gz
│   └── repolex
│       ├── 15ced05c5316609bce5b43389f8e3f06102a8b18.nq.gz
│       ├── 4ea0e648e38a63d6caff14100f5eab5c50912bcd.nq.gz
│       ├── 6a2a26093d046d8ea92542a0fb38721c4ee40bd5.nq.gz
│       ├── 6a8b8b6651a228590bbc42145483ff864f4f6e89.nq.gz
│       ├── 6ad6205e9c94a4b8a320219e28c37c29d22a7a2c.nq.gz
│       ├── 73726dc606796a025971fe451f0aa6f1b9b847f6.nq.gz
│       ├── 84d927b8ad57ed9e1cda240b41fa2eed55066103.nq.gz
│       ├── b5af7796535d97d9c7af42539af01d787fcb3b4d.nq.gz
│       ├── b75d67cd51eb53c3c3a2fc406524c940021ffbda.nq.gz
│       ├── b869fe1415e4b9eb52f247441830d502aece2d4d.nq.gz
│       └── e2212d40c62a98b388a5eb48ecbdcf88534688ba.nq.gz
└── blob
    ├── 007d9b75514fd8847950e95d3bdaef29c9d25555.nq.gz
    ├── 00891e0089cd5d377f35d3d4deabe262439bfffd.nq.gz
    ├── 015c0dbb55d8e93bb632be686f304fb5a3bb10a9.nq.gz
    ├── 01718689254f4b4a659c9200b224b3b7bbfa6627.nq.gz
    ├── 0179aa0853184709cac70b0861610fedb4818312.nq.gz
    ├── 01ac4a907d1bf30fd48e4439c3b377c73c8dbb67.nq.gz
    ├── 01cb758a4f517a2523f7d06718a8ce7a809944f8.nq.gz
    ├── 01ee6b8364af06e793eedb96a60752c0fcae13ca.nq.gz
    ├── 0240b2ec75dc1cd7e037457a0cb2b7d43763490e.nq.gz
    ├── 028c4ad6d6ae329745079e3e875a09a971deae44.nq.gz
    ├── 02b96221195a28aae67e1e810d719f89ba083553.nq.gz
    ├── 02f23247d58d652d13065d031856147b67386f82.nq.gz
    ├── 03bc78dae14e73a4824d1c9e646481d6d61df8d5.nq.gz
    ├── 03c699108563cca425ed5b08ab3e4bd974cc85b6.nq.gz
    ├── 042bb821dabc5b099a92cd879761ed7a319f34e4.nq.gz
    ├── 046f284ece46346c89c3d10b8a52c1df0a576774.nq.gz
    ├── 0488a9b01c5987480793a90ee1f13f5ac688dcff.nq.gz
    ├── 04d940797109fb48c47d3714462d1a16d7003835.nq.gz
    ├── 05271b67cbbf9d18e365ac6294a5b898d27a687f.nq.gz
    ├── 053e6c5aabd4db366e565fb293d0fd35969ce0e0.nq.gz
    ├── 0550999288b359784059fa330a1efdf3ef4a250a.nq.gz
    ├── 058ddb9d7043f0fa12dd5e94b68454d17f37e654.nq.gz
    ├── 05fc0842f312a0848f72222fbc8a392c3b5f6b91.nq.gz
    ├── 0626611febce78c34d5699deb4c822b809f406b0.nq.gz
    ├── 06732e973ac683746a9f936b0081578753230a75.nq.gz
    ├── 06b53c28b367d31641642a3ed74db7022f797088.nq.gz
    ├── 07619ebf573b63a89bd6a0b1352d7a69eae598ae.nq.gz
    ├── 0767ef3f2461770a3207ea391ed92a3f78ff54d1.nq.gz
    ├── 07c837512489b40f43609d39eb547f6afe01abf6.nq.gz
    ├── 07e7859f0b53aaa4a2eebfaf7172578e4010a4bc.nq.gz
    ├── 07f0233326f267c321e34b5d68e3bf6f8bd36bc2.nq.gz
    ├── 0a91a3e6c3a7ceb7bd64205b0b46724743c9f392.nq.gz
    ├── 0b28aa8a801900d1f965bfa322edf3214eacf12e.nq.gz
    ├── 0b3f82df7d469ef79150f600857c26542c71dc1a.nq.gz
    ├── 0bb90f22409f7703215b821ce462bf205fc3555f.nq.gz
    ├── 0be59660b3d57bf79240b8f98891d8e4e696fe63.nq.gz
    ├── 0c23bb0d6baa395c947e27b1654f3b54236ea5be.nq.gz
    ├── 0c2f9a0ccfc52975fa6a4e847eb0b036f0d557a0.nq.gz
    ├── 0c654b86665f1256566ae1bc3a1a1d563e62927e.nq.gz
    ├── 0d40666ec33c99c0bb3ccf96433aabdae0ffe1df.nq.gz
    ├── 0d9d8fb13fd81be4e6ee408915f5a48f99245bf1.nq.gz
    ├── 0dd866846526003a4ba9a8274c9f2514989a5bc1.nq.gz
    ├── 0df78360893ce58968328a0cf7137c81b3c2f593.nq.gz
    ├── 0e49d65b14a6e301584067381082a3da3139cbc6.nq.gz
    ├── 0ebe2ec56096c13ce83e9e21b8f7481750f30f79.nq.gz
    ├── 0ef08f006e445adda4cc61da7bbd92dacf141956.nq.gz
    ├── 0f276c13d4c9207400989c3adcc92f518c0aa26b.nq.gz
    ├── 0fe2fe0011fae5b89b307788301b447e44d81dc0.nq.gz
    ├── 104ce809d9f968ff5649c586bd320fbc4b610c2c.nq.gz
    ├── 10b442cc368bee62f0e5cd7b8cdc555d64bdd899.nq.gz
    ├── 11561c843d48c611c353382084564ea845fc3e67.nq.gz
    ├── 11bdd79ccf94ac3ea4e255c0f851670687bbe7f6.nq.gz
    ├── 125e659f284f3990d264383ee7428b3781cbbbd1.nq.gz
    ├── 129ad3870775e4d7799495d717404cf5bec9b087.nq.gz
    ├── 143a5b87658d5c3519de970f37efd1c32a98223d.nq.gz
    ├── 145f131641ad9650e2567c7a25c9689ae4912256.nq.gz
    ├── 14dc8f20da2cc4b6de828cabfae06f5bb653cb3f.nq.gz
    ├── 1550b868d1262baca7c9350db8d814948728fc67.nq.gz
    ├── 158a3390892dfea76f6876a9c2b6b3746807bdba.nq.gz
    ├── 15aca9959cd61d5840256a6df6e5963142b3bdd4.nq.gz
    ├── 15d9930d3d14ba04d5790aa9b01d89d7c888a61e.nq.gz
    ├── 167ac1afa1c9d710c05e5fda8f475b33cc30bc3d.nq.gz
    ├── 172aeb2414c66e0a425bbed11a47b7e200b73814.nq.gz
    ├── 17336177249cc60e3fc549e7808eb581697a6ed3.nq.gz
    ├── 1761fe325e98617e9860934d864421ab78bb9fb6.nq.gz
    ├── 177c4471e8551307f704e363935327407b1c7875.nq.gz
    ├── 179ce4ea2037ae18249dacd00e9a80cdc4c6c61e.nq.gz
    ├── 17b54ab3b9cc8df227ddd3ff7fcf690c308218a2.nq.gz
    ├── 18064fb5340857005ccfdb3b68d5d47676b66183.nq.gz
    ├── 181f75b3683ba5a2211eea5f3b3764942fc0559a.nq.gz
    ├── 182c558947d6cb81324d75ca27ba08cda43ece46.nq.gz
    ├── 18f27fa9808acbbb8944524762ae7967f5efd6d5.nq.gz
    ├── 1965a429a903c06dd78a29cc8c8431ed79ecb792.nq.gz
    ├── 197e9208bfd4e1fc728915069282cf76eaf0dcad.nq.gz
    ├── 1a7de86b7172e962620fd911e708c97a0ee6e112.nq.gz
    ├── 1a8df6010b7d93ad60d542ed40bddb5720b2e328.nq.gz
    ├── 1a99193959eaf0992f92239be32f7a9776f9f521.nq.gz
    ├── 1b5fb2ff0381fbae7b3d395af62911151e338966.nq.gz
    ├── 1bd03864f17b0e951e090b73718923dd780e8f7c.nq.gz
    ├── 1bd57f03d2eedee4c1b48620b7a5372453ec7f8a.nq.gz
    ├── 1c5e995ccdf2899f08cbc7f519bc13f5b4e412ff.nq.gz
    ├── 1cae3fce54bb7a75efbb4993a435a4123ffc2979.nq.gz
    ├── 1e3be65b9df69abe9956eba3b7470978619625f3.nq.gz
    ├── 1ea0e2b9500cb46ad2b313d0ffef088a17f225b1.nq.gz
    ├── 1f113e74d68a58ad9bbd6cd55b7bc3aeff713d2e.nq.gz
    ├── 1f3c8585ff9032a8f326f365bd0528b83f60dfa4.nq.gz
    ├── 1fc0cafe109711fded349cdca14a50b7c3c95931.nq.gz
    ├── 1fc15ff07992ca25aa5d18c14ff636ed10b64f07.nq.gz
    ├── 1ff7f370605592e4c09bd16f6775c075631bd9e6.nq.gz
    ├── 2005738ec60ad397d09ae5ac2cef38241cd5602a.nq.gz
    ├── 20d200320bcc6d61e8f183ccc144464189afbe3e.nq.gz
    ├── 20d4aeaf545ea2489ef5966918a0d94ec9a47cf8.nq.gz
    ├── 219743f2a950eef1f0ab0b9b8ccd68a6703ae879.nq.gz
    ├── 21997ca1c6a293ccee04a2e2bb40033242c7fa3e.nq.gz
    ├── 21a0a48012e0bb0c3913d22a04ca0493e6b401c2.nq.gz
    ├── 21c43d15209704eb06e0c2e5cdf1fa341461feeb.nq.gz
    ├── 2203f33a3218720d92102b65018c80d75de46d43.nq.gz
    ├── 220d1bc7b4542909c63bfb212aac203cb8be5a6a.nq.gz
    ├── 2269b78ee130d46817571fa8aa5a20bb841f68f1.nq.gz
    ├── 22de9b55151288634dc68bb74e95197f198bb7c4.nq.gz
    ├── 232f8dcada12fb809ad43fc27668a8a7bda7ea6b.nq.gz
    ├── 23339af4bbb5039cedc7a94f04ebeee4f7f1a845.nq.gz
    ├── 23e749e269a0c64c7c0ab3e3ac3908fcbb085143.nq.gz
    ├── 23f717265ebf1ce2c55c2f32a41feacd24cf2fc6.nq.gz
    ├── 2407f463398336cad68fcf2cba1e73a6ce68f828.nq.gz
    ├── 2503c5156af7198bf07143ad81eba72b05d7456c.nq.gz
    ├── 2535f8c33df485eee7882bfc69f7c423bde1c5c1.nq.gz
    ├── 259ae8e7082cff8624b3fa9d16b42ebfffa8e477.nq.gz
    ├── 25d0ebd4741afca3a997f43ba6ae0c8ba288027b.nq.gz
    ├── 25e8ff60eddf898eb7ffd7282f294470f6c1f9c2.nq.gz
    ├── 25fd7c87f9b8569f2d7f5d40a178913121b9b11b.nq.gz
    ├── 2675d46ba21d7b735a72b4d95c911b034e2d9486.nq.gz
    ├── 267605072e9ca5a1d363ef669e3557baabd5b22b.nq.gz
    ├── 2681231d9d7ba3e649b2596e2ad00398b89e2348.nq.gz
    ├── 26826689a5cf5c84218662685a522ea14e5e1e28.nq.gz
    ├── 27bc3b173deab95d127f9da004e31388279257aa.nq.gz
    ├── 2853ce8ed8b160326c8a23c34c3652fba3f94285.nq.gz
    ├── 28598baf5414a97e78dda828cd39df7d6cc779ce.nq.gz
    ├── 29151064a985455f42c219ab1e933571cc8d8cc8.nq.gz
    ├── 296d3eb18c64ea2990595ab0b5830beb3059dbea.nq.gz
    ├── 2971f42fe9561b3e7770650969666e87aa3ca7ed.nq.gz
    ├── 2a23d85e94f5171e4ee9c5d91f374e705ff4b421.nq.gz
    ├── 2a442996a63ed58714a8bd1b144afea8db9a27dc.nq.gz
    ├── 2a560371ca2073529286183aaf6ed0bdce9e2c93.nq.gz
    ├── 2ad1f474b3cc22a675d9ceab61c7dd959fdaafcf.nq.gz
    ├── 2ae9e889cdfff92cd2a8d1f6a6969b420cc66260.nq.gz
    ├── 2bc0e3a47e2214a2ac0cd4904a1340b2edbf5e08.nq.gz
    ├── 2c0ad5e3e86b39442f412d85beb16da0e1e30980.nq.gz
    ├── 2c76b6d6e5ed20c24ac14879ed1a1fbf449bf925.nq.gz
    ├── 2cf2f36279ba4183847d6d84d12d734ffd46a484.nq.gz
    ├── 2d5e9a5600f07d500209bdf543bdf737a5bc40f7.nq.gz
    ├── 2e033bf3477101b55ec464a501da1cc6420b4ada.nq.gz
    ├── 2e434341b899f89c5a7c4a2356a31ffb72fe1047.nq.gz
    ├── 2e7a5b9070c331597da8f28a265ed42d60f461da.nq.gz
    ├── 2f4e45b40fcbbe022b7ee76b857ac4b1932f2227.nq.gz
    ├── 2f98676cfff579a528e8b7953f67bf694a384073.nq.gz
    ├── 2feaf467768cdbcebeb2aef57f8f9e9014b933d3.nq.gz
    ├── 2fecce464288590776bf9f786c2fa8a6f532ab7b.nq.gz
    ├── 3080fd34fba06b4ce9b6b55115e96684b57441f2.nq.gz
    ├── 3101d5231f16daeec9768b4cdcb872fcf8814569.nq.gz
    ├── 312af741d5e3b7cf44903acc45c52d84fc3d5617.nq.gz
    ├── 32c2b59e0812ee48e8c3cd229d7c99337fab9d83.nq.gz
    ├── 32e6058db6ac3a45395d39e2649ddd7cca096382.nq.gz
    ├── 32f00983552c79ceb5692586d9f7b14d18856367.nq.gz
    ├── 331949139738a64d8f179c7a3be3156d85431c13.nq.gz
    ├── 33d546a195b9686c121ddd8a7799b481e5ba7525.nq.gz
    ├── 341518520e6369770053d2dc645da73adfb509e0.nq.gz
    ├── 347917e7b581a1348f3fc284ae41aa066f403ac1.nq.gz
    ├── 353c82bbf24bd7a157441da08df9dc49ebbdc920.nq.gz
    ├── 36eb27a344dc592c44737a1d9130f287c5e07dfa.nq.gz
    ├── 376733df5fb5a721bf74effa3be2cece5b505176.nq.gz
    ├── 379ac72d645285f6d549a2fb36f880dc706122a6.nq.gz
    ├── 37e27f27a519b14acc6da28882dabed000d1965d.nq.gz
    ├── 3808666acf0fca79d1e8e4558e7fb009c5d5dc84.nq.gz
    ├── 38c189a0b858b2ccaa8079087055a74869de2294.nq.gz
    └── 391adafed0e63a5304b88e003702a6c10041f412.nq.gz

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

## Source repository

[gin-gonic/gin](https://github.com/gin-gonic/gin)

---
*Parsed on 2026-03-29 by [repolex](https://repolex.ai)*
