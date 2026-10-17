# Repolex Knowledge Graph of pypa/pip

RDF knowledge graph data for [pypa/pip](https://github.com/pypa/pip), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/pip
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 41ce840487b477bcddf5be3025d947760940eec5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 41ce840487b477bcddf5be3025d947760940eec5
│           └── chunk-001.nq.gz
└── blob
    ├── 011c780230b95eaf72fb5e1b30d696df8b1f7ba3.nq.gz
    ├── 01b2f5023bb9b904cd2d1ca8ab569ce6df13df32.nq.gz
    ├── 026d3a215e6d2077f41e283c16016a532a70ee66.nq.gz
    ├── 02ce1f7ac5e984eb9b21d1a968497ee3ee14254d.nq.gz
    ├── 031718f9c373b794d07e67dbc50d3ce6c8f31a51.nq.gz
    ├── 0459c7bbb5cd226b959d45a15c3c47ac21e51f8e.nq.gz
    ├── 0491586efab46959b708ce001815362694422a68.nq.gz
    ├── 04bb4e75f39d9b3fba7b89b4f6fc4fd71dae13cb.nq.gz
    ├── 050c2fc45ebd1c7e9c2d6a9de9c1ef3f32ad76b9.nq.gz
    ├── 0535f217587d813079082fd356585e2fa5bac6b9.nq.gz
    ├── 055dd525312e9b68d73377beddcc7f24cac349c4.nq.gz
    ├── 05bd5b6ff2104d093fb5ebbab1a9c5e02f1e9c20.nq.gz
    ├── 067ebfa9c65a9ea3b3ac3e1d4cf815eee2f1f32b.nq.gz
    ├── 06861f60763a584717c3989a73c7d9161d7813be.nq.gz
    ├── 06cb79b829ccb0b7d789f4f674d8a0cf62d814a5.nq.gz
    ├── 07587e3b3388b61e79591637f08fab3499af80a4.nq.gz
    ├── 07c5e54dc26958137d0c7d175579e63ed290ea8a.nq.gz
    ├── 08645e8bd5b03bb60d2f30409887333ced328957.nq.gz
    ├── 089d19bf53c24943463de73ef37961987555cee5.nq.gz
    ├── 08a97f63f4328b8bb0730672eb997efb34fc72e8.nq.gz
    ├── 08f34c70b376784474a3045fa4400eaf3c978500.nq.gz
    ├── 094361cd1aa963d4b7e13ed0d22484390970d5f3.nq.gz
    ├── 0a23c510d6ff773aa123b7a70e54992946f8648e.nq.gz
    ├── 0a7532ee79dfc7054bd68bbc3540262e7e605d45.nq.gz
    ├── 0bcbe53ef59373c608e62ea285536f8b22b47ecb.nq.gz
    ├── 0bf380136aea0e32c90fe5a07c8f4991d3ba990f.nq.gz
    ├── 0c01d5b08b6b44379b931d54d7fcf5221fdc9fde.nq.gz
    ├── 0cbeae64fe0a1dc069fb3ba8db538d32f5194d29.nq.gz
    ├── 0d6377f769cf68505f6c3ff5495fe01effb31d38.nq.gz
    ├── 0d71b39f36d80e7a3eca2aa27640314930b9b282.nq.gz
    ├── 0d9efd07ac42e7b6f0d8406615dedd6d30088125.nq.gz
    ├── 0e35020e38926daeca0b9efca044c31afd3a2063.nq.gz
    ├── 0f4578696fa2e17a900c6890ec26d65e860b0b72.nq.gz
    ├── 11d009c417543e2c1622bb23754db4235791d97d.nq.gz
    ├── 11ff9e9f27e76f5ef6b9b609e88c2f418d655e16.nq.gz
    ├── 122060b3d32e2607b3f1a881e1aaaa91f348eb2e.nq.gz
    ├── 123fd553acacd4cefa231f2a40c3a813c5ea1783.nq.gz
    ├── 129843a9e37f8e084d4891136f03dec518cceb6c.nq.gz
    ├── 1392c8fbbc7054f2169c9d370ca94770821fe0e9.nq.gz
    ├── 14dd84e32bfabe91ac253909ea147144d0878af7.nq.gz
    ├── 14f70b05b4778f91137e4a9e7059d7514aa44d28.nq.gz
    ├── 151edbedf257448972f794530d677d76a4d4fa42.nq.gz
    ├── 165ad757f8fab7b1c6fc704e98561bfa93f8cf1f.nq.gz
    ├── 1660ce364383f9bc6bd79c539cc2bfbff71d16ca.nq.gz
    ├── 1676d936db7c0a1e912bbece4fd98d28dce26828.nq.gz
    ├── 181fb4216b1cc4659cb8684d8823c6b6ed916213.nq.gz
    ├── 187b6faafa0b245f42b05b04465afad16fcadb2b.nq.gz
    ├── 190a31aa249e13b65f22fbf3cd0de18bef950022.nq.gz
    ├── 194564e761ddae165b39ef6598877e2e3820af0a.nq.gz
    ├── 194e2742aeb5babdf13e400ce380ad76c0a20369.nq.gz
    ├── 197dd757de979bf116810a678a9c07baeaa7dba1.nq.gz
    ├── 19a8aa88286c0245933a15ed768b99b5dd2da6c0.nq.gz
    ├── 19c2b9a979d614ea0e98baf7b02bdda6be2bcd0f.nq.gz
    ├── 19d77810caf332a1f310bd3b734dab7bbd82f64c.nq.gz
    ├── 1aa53c8c2447a9179a83d1589369ff7ebf8cced9.nq.gz
    ├── 1bb5a44356f00884a71ceeefd24ded6caaba2418.nq.gz
    ├── 1bbd55808d45816cf9c9f4c8289f781d612c3859.nq.gz
    ├── 1cf233e023424d91ec7cc135ffe8ed34023b48ea.nq.gz
    ├── 1cf31d5d7081ae155d75142050dc00616803eae2.nq.gz
    ├── 1d01e3d9750860e6ec87fb7c0955cee6bcd9fcc1.nq.gz
    ├── 1eb0b0a274328c5987b46e66f8f56fb9cc752fc6.nq.gz
    ├── 20bfbca6b00ee4cb9975346d6d6dcd79a3a63d9e.nq.gz
    ├── 216b9e03e5b6fe14346456b060f4869292091aee.nq.gz
    ├── 218215442e91301a72bd0f1e8fb26646c5e4a476.nq.gz
    ├── 21e578d91131c79519554a928e41646babc16346.nq.gz
    ├── 22bb90e55c7cb57cb0980473cc1d3d877dcb5358.nq.gz
    ├── 22f4d716ac9764ee18005b9b852946d614152375.nq.gz
    ├── 230028dd1cc5c4a3340bd2b64dedfa69966ca54f.nq.gz
    ├── 2388c362a5c20363947bb59a530c14848b6a56de.nq.gz
    ├── 2418ffe40bb012057b081b957cbcf532f5c95d0f.nq.gz
    ├── 2458fc798a2243cfb48ceceffff4f41b5232a128.nq.gz
    ├── 24d0baf0c31c2902e45623a29aea8d7ede8c0dee.nq.gz
    ├── 24ff469ff98baf5a4457ba6a34330be310058cb4.nq.gz
    ├── 251a4bf341e8b841614fdef98ac38ad0e80b746f.nq.gz
    ├── 25fa4afdba4c28b0291fc71d0dee07f3ed9b8449.nq.gz
    ├── 263ba19880e6675a6575c4bf5a6f01f9ec8f303a.nq.gz
    ├── 27c5cf7b2390b43c1b24541ba967777d43c893b7.nq.gz
    ├── 27d65cec93bda5c7a97c2bb2117938dc0142ff8b.nq.gz
    ├── 27eeddb9dbd41af11b4f7d716a8d9cca60df4bac.nq.gz
    ├── 287704f8628eeb1318b4f361dd774294ce6f6ba5.nq.gz
    ├── 28d46241a7b380a29959c2af01402a121748a784.nq.gz
    ├── 28ee850cd48231232e9f13d029af430df25ac06e.nq.gz
    ├── 28f8df1c9f31fed58fb9a17ba520d0bf39390102.nq.gz
    ├── 299c09afae1ef88abaffdbe5a1b12dfb5b784e3a.nq.gz
    ├── 2a326dff8d7c3594b83b17b8a7705a6ddf2f13fa.nq.gz
    ├── 2ae658ff5eb6951ea30948ab425e6125dc41fa34.nq.gz
    ├── 2af481dbf59e31965bde74c2e27d73517a39d7ac.nq.gz
    ├── 2b2ecabc327fa09fd64dfda96e69a68c355978c2.nq.gz
    ├── 2b8baad7cd61cb508087ef4e16202ea54dad1601.nq.gz
    ├── 2c84208a5d87511cc4a63dcd9c647ac75c6f4475.nq.gz
    ├── 2cb3013c7d9e364beb99fb2c9b461e697dbf20f3.nq.gz
    ├── 2df515d4ae4bb5a956d92ce78f45ec88439f7d6a.nq.gz
    ├── 2e3fc215095fad13817562bbaee871cba57eec08.nq.gz
    ├── 2e82475c930ae5f7c7b4cbebca584545a84e9aee.nq.gz
    ├── 2e966a53fad78fcb54322a9c27f1b911d461b219.nq.gz
    ├── 2f3e2339c4ed099d0ff9b9fe9daa94724ea0c510.nq.gz
    ├── 2fb3e043134701ac036ab4663927ed7c36250e52.nq.gz
    ├── 2fc33f232491f2c7e0c54731d98e3ac24d2a8a5b.nq.gz
    ├── 30b0298ff1e30440811cf1996ab9dd59eca42d9c.nq.gz
    ├── 3298fce4e02f29bdfa28fed577be86c49e859bec.nq.gz
    ├── 331a2e65750551922a054ee78a10f2d301fd4641.nq.gz
    ├── 33c6b7f3f06d14199a20de59787faa34da0a27dd.nq.gz
    ├── 33f2d57b4e6077289c89d1a11acd58d56a35ba3d.nq.gz
    ├── 349c5a083d0008c6ae071e1d536635f18b575027.nq.gz
    ├── 34ccb99079139bf230b91f4f7b9303a34de6b717.nq.gz
    ├── 35c77e4025842f548565334a3c04cba90f9283d6.nq.gz
    ├── 35e275576f78dc786f6ffe89c4d877830e2fc814.nq.gz
    ├── 36689ec8d072927d698107da882c5f211e2796ec.nq.gz
    ├── 3768baf60d637866837b2b6e53b4e109857c9df7.nq.gz
    ├── 389640db6ed4fa0342f1b5ed0512080cc3d67188.nq.gz
    ├── 38da7ef288196fa9ea11642e9a487f51d9cb61c7.nq.gz
    ├── 3a4e8f0d05c2c889f55816983b16292c952af67f.nq.gz
    ├── 3a8a21e62518768e3476452c554a8f9d2546f43c.nq.gz
    ├── 3ae77cf03f9e678a8af738328bb82c3e302eac8d.nq.gz
    ├── 3b71b86f23909bdd732d676bedb5f499ced2f77b.nq.gz
    ├── 3c2fdf511448030f6e6eaee6371765f2cb8f5653.nq.gz
    ├── 3c6e79cf31da1c0433d2fa666bf50b53f6359f26.nq.gz
    ├── 3c748d33e45bfcdc690ceee490cbb50b516cd2b3.nq.gz
    ├── 3d31707d312c915a80b05933b70adb34401f1faf.nq.gz
    ├── 3d82d07781ea79d5f633206a8e1e402faf9b226f.nq.gz
    ├── 3dd628a16d79577b4c869ec2c7cf80200d320517.nq.gz
    ├── 3e35de77b8cdadd89eca78417c4bb999bda589f0.nq.gz
    ├── 3f053ebb7ad29e93c2818f5135232fff9a1270f7.nq.gz
    ├── 3f8c36f67b39fc2bd4828a107090e9e1a9ae76a7.nq.gz
    ├── 400bb86644244695c6dbf0c5c80f8315e12125e7.nq.gz
    ├── 4023533c90583346ac98ec00e5bef76b15f2d09c.nq.gz
    ├── 40601a2b9d98434e96e5f251642137852848f6d4.nq.gz
    ├── 4087c79bb32dac587fd4ffeb3b880a619cb08c80.nq.gz
    ├── 41794f767877ad6330541c076801c8e76e324bbe.nq.gz
    ├── 41b06418805bdfe2b5fba390566aaa4d274f829e.nq.gz
    ├── 424f2d7a4f3ebadee0a2b6fa4e1505631f06c95c.nq.gz
    ├── 42ce7b75c92fb01a3f6ed17eea363f756b7da582.nq.gz
    ├── 4306784d9a26466aa0a210cb2f262903c67d46ca.nq.gz
    ├── 43f14cf2a3be082846e02186a851580f6b0c6d21.nq.gz
    ├── 4415505566f261c802b671426be529a31f914137.nq.gz
    ├── 446a1a805c8a949579fb8a9799f2bec7777349dc.nq.gz
    ├── 456a8ff06085495868c8562043794ac190be0fae.nq.gz
    ├── 457657073c4f5e8f9b3ab3f955cab7a31dafa68c.nq.gz
    ├── 486a833212f2cf220b6c9e0a918c05f913509750.nq.gz
    ├── 48984e11613e1b6c9c2e85531cd3943a81e998dd.nq.gz
    ├── 493b53e4e7a3984ddd49780313bf3bd9901dc1e0.nq.gz
    ├── 494a71c7225f59284e99c4f87152077e6672ad4e.nq.gz
    ├── 49a7fae92dc4d9ed6bcdb735f346b79c476f49ad.nq.gz
    ├── 4a813c46b5fa4002656f22b522ec3be7094bf247.nq.gz
    ├── 4ac3366fb169727379b15dbea4add3d2645e1dff.nq.gz
    ├── 4be0a2b8c9ed4bd0a86a4be861aaddee66462c40.nq.gz
    ├── 4d62ef58d5a1c24faee12d6d62a942679bad2c31.nq.gz
    ├── 4e0d0250c08a0682693a86921726127d72711173.nq.gz
    ├── 4e204a3864ed46bc869c6bfba4d1e9d1f27716ab.nq.gz
    ├── 4e69b8867904c4f38abbafd939d072da1abbce70.nq.gz
    ├── 4e909c874063f929e068eca5b56041a4f3777c41.nq.gz
    ├── 4ee2d3a31b59e8b50f433ecdf0be9e496e8cc3b8.nq.gz
    ├── 4f6d8b2d79406012c5f8bae9c289ed5bf4d179cc.nq.gz
    ├── 505d8b24731fbad1795715a9602c698c5018904b.nq.gz
    ├── 50daab7657d854e47c8db371bee5b74415158b9e.nq.gz
    ├── 524e3d83272b4a4df7850a4d8980cda4610894ee.nq.gz
    ├── 534126033c083203649022fa9b753a433f005556.nq.gz
    ├── 534a70e43a4f8114b865fa91963bc67c0e33444c.nq.gz
    ├── 53b4f006408afc0ebfc5f990f213410302d9ddc2.nq.gz
    ├── 548d9d7af2865b23cf59369d25b98221daf34b95.nq.gz
    ├── 5562ebc9541e8077c990f4e895e80122c3166651.nq.gz
    ├── 55b196e6338f54f6f56f8120581586883f85fc68.nq.gz
    ├── 565e9d960f8604c487e063ad9ed3f6f63027f3b4.nq.gz
    ├── 566eaff369be165e46a923592877f77ed380a728.nq.gz
    ├── 5754b5afb0e22a7109579734c156a36074434169.nq.gz
    ├── 579f428c8ca63a99949f659ceb664dda4b881f32.nq.gz
    ├── 57cfe7af055f3215b5b4b9664810f53cfac6baa7.nq.gz
    ├── 580900cfb9370c5d0fa642c3b7ba39c563efa5a8.nq.gz
    ├── 58182befe111fa283d9a100366664b9732dd732e.nq.gz
    ├── 583130948313e3d4e86d333337014b7c136b046d.nq.gz
    ├── 587c04fc07dced22009c372517e4fcc724d200ba.nq.gz
    ├── 5993b53f607fd52fb9d2eee438214acbfd4110f0.nq.gz
    ├── 59bd0717f0c0b7292558d803a4bad2ae69188960.nq.gz
    ├── 5a0c6b142b82ea440b37bc4253063a45e19512bf.nq.gz
    ├── 5a352c4fe466189eb781cc2f9f12a64647076547.nq.gz
    ├── 5a561e833175a3c0791355e88db0221042c78bda.nq.gz
    ├── 5ad46e7af9c99055e1f6c8075f92577e9580450e.nq.gz
    ├── 5bb4a11237b44f3726a770f4db283dc70bdb4816.nq.gz
    ├── 5cb35269ebdb6c292645ae683b2b11803d6a6b69.nq.gz
    ├── 5cc272f2c1ba8d69241f8f65f1296fb2246d4112.nq.gz
    ├── 5cc393f92bf177b84bf3953713360d3c533a571f.nq.gz
    ├── 5d559b5e1f3a099ee558a4fb6e1040b24ecb63f6.nq.gz
    ├── 5d735a821881100bca2b3f8bdc87c9c195f73bc3.nq.gz
    ├── 5e7e80fc740378c02e44fa8d7e5fb1269340f126.nq.gz
    ├── 5ece05649e7268a75c82de6ced552619ffc093ab.nq.gz
    ├── 5f3ea3d919363f08ab03edbc85b6099bc4df5647.nq.gz
    ├── 5ffff662c78947c89167e1842faefd28eb56654f.nq.gz
    ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
    ├── 60b69cea16a194a5867d2373b44532f6488df397.nq.gz
    ├── 6112bec5fa3360f778dccaba6019bee14e3271fd.nq.gz
    ├── 612cfddc4c28d2f0edf47522278fa6d9b7906623.nq.gz
    ├── 61797bf312c5498dd077a90e72f191eb4cd112ca.nq.gz
    ├── 61d5c1121e151ccf1c18993302359a4f02959df2.nq.gz
    ├── 62b076cdee58ec8f34034141ba0befd9015b0c7e.nq.gz
    ├── 63f79dd3be803db09671c909f79316c3f65d6916.nq.gz
    ├── 646b858b361ed3363f12604bba5541e5c8b2a7ac.nq.gz
    ├── 6569fb5cd88d922c67acc18bd8b32275f8ad2645.nq.gz
    └── 65744838e3fcd7365ce6f268fe511d75d55e6a07.nq.gz

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

[pypa/pip](https://github.com/pypa/pip)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
