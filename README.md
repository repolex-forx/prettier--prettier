# Repolex Knowledge Graph of prettier/prettier

RDF knowledge graph data for [prettier/prettier](https://github.com/prettier/prettier), parsed by [repolex](https://repolex.ai).

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
lexq download prettier/prettier
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5b62d401414b0e180005604dde7d360b7cee06f4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5b62d401414b0e180005604dde7d360b7cee06f4.nq.gz
│   └── repolex
│       └── 5b62d401414b0e180005604dde7d360b7cee06f4
│           └── chunk-001.nq.gz
└── blob
    ├── 000606eecbb26db4057db4f3ecd67410f9f03bb0.nq.gz
    ├── 003137d834a67440b2acf6571ed8b87521d31d19.nq.gz
    ├── 003700429d8d66e0bf1694a43be110eda4dcc0bb.nq.gz
    ├── 00388851ce7b30d29bd81e460c5b1ab528a1da48.nq.gz
    ├── 0065c134cd6c5a9b52ab1a5eaca2683aea1a28c0.nq.gz
    ├── 006fbe0594c5745315b5e0501da724b51ed3e003.nq.gz
    ├── 0076d3e7af4cc10120d1b72705bc9c07d241057a.nq.gz
    ├── 0078e30572e1dc735523be4cba4311545b04a578.nq.gz
    ├── 00854190f167cd77f988a22f04dddfdb3ac70bee.nq.gz
    ├── 008a44d84463c384aca7751824ec58094bbde76f.nq.gz
    ├── 008c3952f34b37bd137b72162076e681a97eb21a.nq.gz
    ├── 008cab9b1dbe712862ce526525af5d559e875c79.nq.gz
    ├── 009cede7eec5a76c1c87ddca579984165f23736a.nq.gz
    ├── 00b9a996621e4ab33e0cfcb34650d3450b3563e2.nq.gz
    ├── 010c74d7e8ec3d3b31545b01139d83b0f004b02f.nq.gz
    ├── 010ca4c71a779fc9e65c66da2dc41a6674202015.nq.gz
    ├── 010dbabfebbbf842aa9fa1edf4a1962e2a7ee89e.nq.gz
    ├── 01244cfa4c11a7db6857e6247ebd8a4258899e2b.nq.gz
    ├── 013e7b4cae35cccc6b26d68e38c4d9527b9bd59a.nq.gz
    ├── 01423c209574fe54a67a7743d0ec25b909714b4d.nq.gz
    ├── 015199f368dca3256ddef4cec9943a289a81b505.nq.gz
    ├── 01828ebbfa3962b692717847ff838bf0a7c64a19.nq.gz
    ├── 0182a7629ff38fd98bac03af98c27b63f8a31635.nq.gz
    ├── 01900f6a68e24fdd008e2a83b5cc3afe0bc0f87d.nq.gz
    ├── 0192fd19e855a3fa373ce3542d86b166419220de.nq.gz
    ├── 01a3acc7f21ef82077dbea61f5710b95f4800218.nq.gz
    ├── 01ae012a0286f1f0c7b40ea8f50ddf7c7bdd7965.nq.gz
    ├── 01af5d6b0a19cf69b18e6a04fe378ae7a7c47309.nq.gz
    ├── 01b30b6e6cfedc4d524657a9bc599cc013c7a9f7.nq.gz
    ├── 01b72bf4898609f49e4fd3e76bb1078181089829.nq.gz
    ├── 01b86e701744f859363759b28ef9a2cbbc46b50a.nq.gz
    ├── 01bb486ef1614bcb4c7ef0920997db324cbfeb8c.nq.gz
    ├── 01dede051e30a04fd56737bda4fc1cc984e7e781.nq.gz
    ├── 01e4503a740cc8058412a05b223301fed0ed90be.nq.gz
    ├── 01fb5d7dee97c4738534d45348ceebe1f47524cc.nq.gz
    ├── 01fecee662ffddd22e5dba24308835e6c3df1f90.nq.gz
    ├── 02082bbc2c67e3d4c1d1b20cb931efc77dc0b7cb.nq.gz
    ├── 021c3eddef179e93ea36c3340f1310347dd48478.nq.gz
    ├── 0222e8f934fc37d3a1d7fc26fbbbe6fca74a7d59.nq.gz
    ├── 02251ef9cd67ddd38df4b4f9b3f605e6e94580d1.nq.gz
    ├── 022a1edc92508522990426293f190aa476e7ec97.nq.gz
    ├── 022a9f97fb294c6c49eb54d42303824e040d1503.nq.gz
    ├── 0232f42fd99e73c209828689e3e5a4d0a6d88a74.nq.gz
    ├── 023fa834ca6b7f06483609da46fd376bc9a88b1b.nq.gz
    ├── 0241a308e196403a5989b92f068cd4bb6aa457a8.nq.gz
    ├── 025fa5dc89db1ba0a6b65ab0f260d7c9b8306784.nq.gz
    ├── 02734f737bc86c0cc460da64a66722c43d844db1.nq.gz
    ├── 02b13db03fe5719b2f9e64acd52af4705225a6dd.nq.gz
    ├── 02b47f2182c09c054cf19d52ee9c2fc43ba98695.nq.gz
    ├── 02b558c4ef25b191c16f946d1920fb898a3f3762.nq.gz
    ├── 02c2e4ace9857a070ab006aa9e86c1290a9c88b7.nq.gz
    ├── 02d08fc99ae4db862fc5817e609d547fdaec7bf4.nq.gz
    ├── 02d17ef14d4d19d80b0ff5ed2cdd973111a317cc.nq.gz
    ├── 02d38813a01f9e487cc77759270a7dc9c08e7f96.nq.gz
    ├── 02e7eb11ba2d03a731554a2471151e69abe63731.nq.gz
    ├── 02e89d4de3aebf4cd58694295e3b86f81f33263f.nq.gz
    ├── 02ef81a82995f784269961982d941c9c4f520aa5.nq.gz
    ├── 02f05991d5eddb801f2147e59d96792a91512acb.nq.gz
    ├── 02fb90253a175bef7df790c7960a11f242378273.nq.gz
    ├── 02fe672e2b8c73e26f747214c212fa36a64dc846.nq.gz
    ├── 030bb78d188a0f136fb6f04b4536328afd4d8cf3.nq.gz
    ├── 033b1abf322926a90ad0d83ba5eeffd05903e4df.nq.gz
    ├── 0349470c8dbd598411aedc262f4ce0fd625d65a5.nq.gz
    ├── 0350329082bdc09360bb34886524876886fc0978.nq.gz
    ├── 037795ff2e1aa4fdac17e11b2f9f0d0ea719133d.nq.gz
    ├── 03804e377d07c1cae459926f850d7fc8dfeb70c8.nq.gz
    ├── 039a04b2ce5bd83eb572d646bacf297281dfded7.nq.gz
    ├── 039a8b561fca5ec0c6891837cdc0afc5f90a1d2f.nq.gz
    ├── 03ba3d37e1c6de09314f916f1ec0636bb803b2c9.nq.gz
    ├── 03c8b59180fcbb23d3dbff0a185bec7cbb4fb9de.nq.gz
    ├── 03ce578f62fc74563d38471e819881bf8f6f6dbc.nq.gz
    ├── 03e129c35393cd2dd97958d507356987273a574a.nq.gz
    ├── 040786f5bb67be72676072551199a1f66f9ac0a3.nq.gz
    ├── 0407c8397d803ab3ce7e3fd6bb59f543f2b044b1.nq.gz
    ├── 040d6ee9d2a5612fd5f239922b4d425cde1ab4a7.nq.gz
    ├── 04289c8762bb38d40d7a207ed029b69321488587.nq.gz
    ├── 04328a60a4d31675ca30fd8e163318d5594b8081.nq.gz
    ├── 044a1da4e7e04115e15adfd57c90511f15471efe.nq.gz
    ├── 044e72e56a5b9fcfa4c527938e8a29ccfe43418c.nq.gz
    ├── 0450ae3f5805074b2cff2e1cbd7abc42e94e5298.nq.gz
    ├── 046279e56bf2cea0bc583a6fb8e0fcd769af0a08.nq.gz
    ├── 04649182f4a1993d5d91cb592d39dcf24d03f5fe.nq.gz
    ├── 04777aa3fa285a8ac3f2944282583e45f135ed58.nq.gz
    ├── 0478a8e81f5c644caefd7f5eada9793b7b06a20b.nq.gz
    ├── 047ca6ac71e6c91d14f14d8d491b6c25523a1bc1.nq.gz
    ├── 047f469293e27d36fe4d987c715008948b28df9f.nq.gz
    ├── 04871ce2a640d9936cbed9f20ad2183730f1388d.nq.gz
    ├── 049164cc96d81f8fa12daddf87dd52da6d928b3f.nq.gz
    ├── 0499250b931fa780f44372648d593cb899b30092.nq.gz
    ├── 049b3a38d856d5f3be39bb3fb071bde1eca1167c.nq.gz
    ├── 04a06a6ab3a30431b251ea7a01835ab104a91db3.nq.gz
    ├── 04c90513a21d10c9645c5853025050111d618cc3.nq.gz
    ├── 04cafe5e5a8b19b72ef906af7d71217293af3fa7.nq.gz
    ├── 04d5727be9ef900f8a12fdeb4767ce0fb6a1fa33.nq.gz
    ├── 04d6d8a905c7899d6eec25957c7c5b79e0aed2e4.nq.gz
    ├── 04e631bbb0b2b64a41ce81e425a751ae659cd3eb.nq.gz
    ├── 04ebf691b566df202dd2315dacf7a014410f86bf.nq.gz
    ├── 04fdd85598e87016249bba409ea91d656d656711.nq.gz
    ├── 050183323549a5efcd827133aaba348015ba77f5.nq.gz
    ├── 0506623812923ac958ecec6ddcee5e221564ae37.nq.gz
    ├── 0514ed85ae1f9645a6ee050e7433b8169b053a5d.nq.gz
    ├── 053ba6313b69d3c93364f5a0ab84bc444cf1491c.nq.gz
    ├── 055bea79cf8552537a1cd38f5d22c3a45612dc5f.nq.gz
    ├── 055d608ef2f36aec0974fd2c71863cf328b37be3.nq.gz
    ├── 056b790b8ba8161037b695d30fa94b2c7f29a683.nq.gz
    ├── 05725ec7afbd73b2821b81a2d6b5785276ff974e.nq.gz
    ├── 0578483ce510fd731df98312942a2e1f262a5661.nq.gz
    ├── 057b8ff97fd552751d24d7d75d0ece5c3b3821bf.nq.gz
    ├── 058077f216b257899d13d4b3a9b9c7882a01f23f.nq.gz
    ├── 0581c7965daba299fbdf11e0b8405276783a6a2c.nq.gz
    ├── 058f62477b38e65f66d5130edab7e173574bf7f9.nq.gz
    ├── 059c3e6d352b419f30d89f1a6e6a52ea24bfb7df.nq.gz
    ├── 05ba4185030cb56fbb9079cd12990860cc6282aa.nq.gz
    ├── 05de901579b37467f053a3499581a5a45daf8376.nq.gz
    ├── 05e102d8ebd4dc9febdfcdd8b8ae0a626909a7ad.nq.gz
    ├── 05e5c54ec9c61b5ed43058a07613c76df1b4fff5.nq.gz
    ├── 05f7047fe1b3f7c1699eec0b20aadcd9c2d52824.nq.gz
    ├── 0601a35766870f3412d534eef405a109b1fa2b7f.nq.gz
    ├── 06086355d8cf630e038d06c15165aacfc7273596.nq.gz
    ├── 06126f9f004ac6182da586ccb3f8b88eef466952.nq.gz
    ├── 0614e335ff014b21a25b6f16887caabee1d10a86.nq.gz
    ├── 0636bba6e72589527c1b52e02b7db55032e1229d.nq.gz
    ├── 06454bf053a7bf6849f8baf99989576ea5064c80.nq.gz
    ├── 064d192a7916ba046cce0ba9aebdac98b0ea680e.nq.gz
    ├── 0664b4d707f79750b7e4d8026ccccebed4e785d8.nq.gz
    ├── 06886cef53123cfab22fee1b40cef68582a0f4f7.nq.gz
    ├── 068903216067d7540d9be6deb8be73514d2867d5.nq.gz
    ├── 068c116c02d085432a30d6de8a578cb9a6f032d8.nq.gz
    ├── 068d63a1e770d0a0e7356237960eaafcb649062f.nq.gz
    ├── 06a49ad997da3e6c0ef847e781e434327cec4f62.nq.gz
    ├── 06abcbf1ddd4719ed927d322416555fc08ebcd2c.nq.gz
    ├── 06adadff2c85de9327756f436fb12d448591d673.nq.gz
    ├── 06ade40adb2c4facbfedeb4c2075b73fe7342449.nq.gz
    ├── 06b0cc251561c5cbb80071ce4e53fe6b37265d52.nq.gz
    ├── 06b24ab578759034db02609692e26a44a3268251.nq.gz
    ├── 06d867ab01f1b925ca649e03a408b88e8a9af0f6.nq.gz
    ├── 06e43577eb22dfd709d3842fb1c27431f307011a.nq.gz
    ├── 070fb50db011cf1cf60243595b05ca886d4d1d3f.nq.gz
    ├── 070fcfdf9eff57d627619b25ef986dffd8688df2.nq.gz
    ├── 07140ba95bd34dd0aad22230904674aab2c0b6b0.nq.gz
    ├── 071653cd3db7442894423efbd9862126cf2aa791.nq.gz
    ├── 07186437a5ca2d2fa69ec0f4a99ba8184249de4f.nq.gz
    ├── 071b896c0f0e142178afcb5ee55cdbdef87d95f1.nq.gz
    ├── 0733b8ba96387fa872046fd2a59fcfcabde16047.nq.gz
    ├── 07512d5f8a3320e32a87cbe9435fe7e8bd6eeb17.nq.gz
    ├── 07571eddba43dd9fba6af0e29e1d34a31119812c.nq.gz
    ├── 07615d04ff360cc256e6c8445109daf028423b4f.nq.gz
    ├── 076901bc07b687f40d1fbc9a9320c6e41a27de13.nq.gz
    ├── 0774f78ac52dd5ca9360c3afff5f0b11472e07fe.nq.gz
    ├── 078fbc89b486a443fa004944533a3f7855dae153.nq.gz
    ├── 07b40ab927ec966277c6640e39a97efe2a134cb4.nq.gz
    ├── 07c209250125d5ca9446c7f21644c7c45977baf5.nq.gz
    ├── 07c5be28d2dd39e8b193781e99b0f54a658a7ec4.nq.gz
    ├── 07d0f1c9face0094e5a3d0d258a1bd4c3e5f7123.nq.gz
    ├── 07f081fec69e7dce3a89a7ad0e12b8bd1e181e1f.nq.gz
    ├── 07f7f953defdd09272dd23509946d0b1d7d3d765.nq.gz
    ├── 08085dbe10d06842c00e11c62279a30a1f450c72.nq.gz
    ├── 080ccbc8d19fa5cc32dec1838807c530af54beee.nq.gz
    ├── 080eaed23afc705327b7d6fb850bc3a17ed75702.nq.gz
    ├── 081cd6ebc1613130e27ff552eab6d6be96167014.nq.gz
    ├── 0829a33c778bcb20b286b78b4dadd32bd9a6113e.nq.gz
    ├── 0850fdc123249bcbd7cc2ddb3193a1f1026aec86.nq.gz
    ├── 0860e8094ac2826727169af0a3b15ec7da298870.nq.gz
    ├── 0864b1410526fa815c0b5445abf922cbcb78444a.nq.gz
    ├── 08787f38394cb0c8d6511cc413569265c6418a77.nq.gz
    ├── 0896cc6f40d6f54553c4cb9dcca219cb7fccd18f.nq.gz
    ├── 089e6e45fba72db1beb647de23602e65203fa28f.nq.gz
    ├── 08b6c18fc361e302d59e76a0278e9bfe3e477730.nq.gz
    ├── 08cc3a0fd6a3ccec093d4591a5471faa06a1a13e.nq.gz
    ├── 08d96a50c73ee3feae6e10b26ed7855c11e2f1a1.nq.gz
    ├── 08ef177f446d05f7ababa4c7f8737c09441c7f13.nq.gz
    ├── 08f150b95c56a9fca845864a1c6b63cb3b930258.nq.gz
    ├── 08f46a918f97a0928fcb09473eb2a159e4d92963.nq.gz
    ├── 08f7a4c0a972eaf09eae17fa2b421102a8150469.nq.gz
    ├── 08fc212e6ff43138b309009ab94690942f222f13.nq.gz
    ├── 0905eb25ac2d51a04a0b1ba213f07af58d9386bd.nq.gz
    ├── 091b4fa2692cb57db3f412958f96e54215acf571.nq.gz
    ├── 0921cb49617146d381e4ff3eff6a24afc3da4d09.nq.gz
    ├── 092959b395895425cbdd6eafbe290e479ac547dc.nq.gz
    ├── 0929d36bbcdb73e7f7293ed1b8a2f052435189a0.nq.gz
    ├── 092bc2b04126100878530888e6b1b30602dce213.nq.gz
    ├── 092e61791a722d108346ae68982f2aa7d6dc152f.nq.gz
    ├── 0939fa59f936d1a10167c9e6d821146d026f20d2.nq.gz
    ├── 093d2d63a2ce79d57fe86fb4f4821f609fb906ed.nq.gz
    ├── 093db38ac69a964fb7584eaa5545fe9aab10f7e5.nq.gz
    ├── 094a85853d989b927cc5ac7a1d499215d7cec51b.nq.gz
    ├── 096fcfc97f6ad4c256b6b4d157a3bce02fa573b7.nq.gz
    ├── 09937e354ab3059af5a5a9f73036c69c4b3fddf9.nq.gz
    ├── 099d2bbad6513e0100b35ecb7ecfe8761a1e06be.nq.gz
    ├── 09a639b7b7f23b413f06391466b9e4069043321d.nq.gz
    ├── 09a7605884693a4cbad7ea615ed9290ee6b607c8.nq.gz
    ├── 09a8bb5162f213fc138133c0691957c0c8a52f05.nq.gz
    ├── 09d3e26abbd1d95f7c4f0258595dc279aea4c37a.nq.gz
    ├── 09d8140920aff80be38d88cda6794e8076f1c9c7.nq.gz
    ├── 09df48fca73b4234bb4139d11285fdd1320284c4.nq.gz
    ├── 09e9b610dac59756ef3b266eea591cb2614214e7.nq.gz
    └── 09f1808b9c3b19a58ce15a2012b058489fe28a1e.nq.gz

8 directories, 200 files
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

[prettier/prettier](https://github.com/prettier/prettier)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
