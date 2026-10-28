# Repolex Knowledge Graph of databrickslabs/dbx

RDF knowledge graph data for [databrickslabs/dbx](https://github.com/databrickslabs/dbx), parsed by [repolex](https://repolex.ai).

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
rlex download databrickslabs/dbx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 07a236890434608beb48e31be1e1da919157facc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 07a236890434608beb48e31be1e1da919157facc
│           └── chunk-001.nq.gz
└── blob
    ├── 04bffb108caf2c999b3a346c6b6125cfe5c38f95.nq.gz
    ├── 05af9c8ab2bfcc28918e2929800ce6f31a9a8b16.nq.gz
    ├── 0697865c6cb0c1bc7162165f9f517e7e03c0f626.nq.gz
    ├── 06c823086c1bbb1d83a83e249a5f51c7f5e99773.nq.gz
    ├── 07505196b8b41f2aa19fac4c356e13153f92f693.nq.gz
    ├── 07d8728a474a4648d1c7efaab74aff9fdf3283fb.nq.gz
    ├── 07efd8b591ecf883e95885047c14c42ec83c3b6c.nq.gz
    ├── 08b09425545a8d501f0b026edd82d8ae8e094da4.nq.gz
    ├── 08ef16162088898a0cd6ce03e8b328ef452634fa.nq.gz
    ├── 0925eed302ba85ba25322299780c32e3d5340c7a.nq.gz
    ├── 094bf5e2f76e968fbcba05fcb1e60751f8eaa356.nq.gz
    ├── 0d5bffe64dde24f94d264c3d280ead1e6f760257.nq.gz
    ├── 0e1b37e84e9be0910642e3d1d309c9e64b067afd.nq.gz
    ├── 0f9345424273594865ce1833052070bca0512e31.nq.gz
    ├── 1046b9081daa89c836909cc603c05b7e0a4b1040.nq.gz
    ├── 11b15b1a4584b08fa423a57964bdbf018b0da0d5.nq.gz
    ├── 1250c3f2d2383dd1a84b60455d7755556bec7ace.nq.gz
    ├── 13bf493691a58f703d1f37df6b2f2f5f734d0422.nq.gz
    ├── 1541691fa12e1ee858b9cda1563834fba360357e.nq.gz
    ├── 15747e77340a53f124945152d14d183c94d1568c.nq.gz
    ├── 1ad27a93994c3d30501635efe6e8b401f7386e3b.nq.gz
    ├── 1af6fdad2052addeb7a4f0a82f628879691ebc57.nq.gz
    ├── 1b28a1f5fc8b408fe6d03f78220a4e17580f9898.nq.gz
    ├── 1e0edee72c19eb9a11a010a7a9d0aa254fd55676.nq.gz
    ├── 1e5abd4f3f8f368a56b61c681ccc5a5be4adee2a.nq.gz
    ├── 1ff7cda6d9e61be36db36ad425575d6eecd8e0c2.nq.gz
    ├── 1ffc4dd0a524310bb7774c9fdd17e89bfb88fdc3.nq.gz
    ├── 23db371f8f87b0ea2277e69d2375538472ecccd6.nq.gz
    ├── 2454d4ec001beae94294e299157ad65a3ee115ab.nq.gz
    ├── 24f1c5176e58c261d3c6f4effb2307a421ccd925.nq.gz
    ├── 26649f4a9f53a7e24cd658f7dc490cda60e98ca1.nq.gz
    ├── 2665acf2b1c8e21762b2ab20e6cee54b1b71b2db.nq.gz
    ├── 26aa874170875a7145023b8e0956bbd748640fa2.nq.gz
    ├── 2719d5586d3b534e6ffcf10cbf6956e0121d637d.nq.gz
    ├── 277e37358bd503d3c85eefcf424de13c3cc1e677.nq.gz
    ├── 27d01ea162190c02031228bbc53bcf454f0e1741.nq.gz
    ├── 27d11503f4a5240a10c3f13a04e0816a4aedf971.nq.gz
    ├── 27fddab0f6d31969d06c865d2aa85927947df103.nq.gz
    ├── 280f45d2fdf272f047fa80c8aad5960c8c3c2a3c.nq.gz
    ├── 299f37ba51e7daf871b1fbfbca2e59d14e6cfce0.nq.gz
    ├── 2b66b37ced16ee4abe68b45c380f8b79c72009ff.nq.gz
    ├── 2f67c12f35cac92733c81d47baa57714a457930a.nq.gz
    ├── 2ffa09b1a8a804eef895b91f392f585a6ca44328.nq.gz
    ├── 30432d7a9c847029d31708bdd21f34742047259a.nq.gz
    ├── 3085635f412a4993cd5df9f9959781c1b5c4dc9f.nq.gz
    ├── 30a2df91ed63c9945a238d25ca1914a993da904e.nq.gz
    ├── 30a6033814c6658d65a146a93f2627f8b98bbe15.nq.gz
    ├── 312ba3bb4e1334e6d29c1218f49eeafd19673c9c.nq.gz
    ├── 31ca684ee725fdf4e46bf7356b7dc44d9f36cfa5.nq.gz
    ├── 32481c4fbf5864b1757c94bd5034cc62bebc15ca.nq.gz
    ├── 32da5d72e2bb8262dc8a1c4bd1a7b79fb8467cbd.nq.gz
    ├── 32eb9886ab5464e03ff67f83ff266a5fa91411f9.nq.gz
    ├── 3314794e4354510941620cc4152c7c2489538239.nq.gz
    ├── 344740a89f2208c69efbad6e1b0166fe025ef2a6.nq.gz
    ├── 3553e4e291f64b461b9ffcf2a2aaf97ddf3d999a.nq.gz
    ├── 362ba28b72161c10ad0702b2e204ace6aef8b9f5.nq.gz
    ├── 37bffad55aff20d0abf6f9efa87cb3d3642d8994.nq.gz
    ├── 3841ccdfd57f5deb7d3389d56c178003af50e70b.nq.gz
    ├── 399c01a3c01c10615073343f254d2fc01a3126f2.nq.gz
    ├── 3aa9dd113eb8b611605b7441642e20b04a5b66ac.nq.gz
    ├── 3c77c701fa2186ac956736fab5dab9bb0629851f.nq.gz
    ├── 3d02e0e55e9a19bef80880f86c91a31fdbd7a8ff.nq.gz
    ├── 3d055311e805b67dabde0eb8c87a62fcc1543a61.nq.gz
    ├── 3d2f4146e28e49fc0c99b1cfe29ec086647b34d3.nq.gz
    ├── 3da8deb4b4397dd2459522bc16272081f240bce5.nq.gz
    ├── 3f5ef97ce5f51ddd4a30373df3afb5141dcc196a.nq.gz
    ├── 3fde51b81a8875c34916c705ebf1600207c70eee.nq.gz
    ├── 407874de237708373c904d9d8a778767c7fd617a.nq.gz
    ├── 41a5f6831d919d65b467c4c9b485f32c9d617004.nq.gz
    ├── 42bf9cb5c14baa85fb0c0b90fd14084251fb40d5.nq.gz
    ├── 431c0543301ea23b544828888f46ae7419b066d4.nq.gz
    ├── 439d6846c45d992edac88150af808326126ac7df.nq.gz
    ├── 449a4351b02fab3283e3be38b9d2cd9dbbcdfedd.nq.gz
    ├── 44b766a838d66e049a20d0c10f1caf0626604770.nq.gz
    ├── 46d34e015de6dbffa7a871fd18ffdd7c9ce0bdd8.nq.gz
    ├── 474140aae32d78093b0522f38daec8482df5fd5b.nq.gz
    ├── 4ae4301c3fa6b0695fa68dbae05081f1aeea3fa5.nq.gz
    ├── 4b14bbf2a3decdfb69ba23fdc591016e5c9af3c9.nq.gz
    ├── 4bdf158f8d8c68016fa420f74c429b89709a3372.nq.gz
    ├── 4ca9a31d77b72c7f5b12bd4a9a259f541fc83a5e.nq.gz
    ├── 4cfd910d02f9ba7abb5612355b9bf618817c2788.nq.gz
    ├── 4e6290d3bc10a7fd21a4c32d37436cdc651d37c3.nq.gz
    ├── 4f21f21ac73c93d1fd43d37a0c9779b98e0f2311.nq.gz
    ├── 51036a6ed56fb518c8ec69babd10105fffa95261.nq.gz
    ├── 51051425a6147bc4553e8bbf171f8a9a6ddded96.nq.gz
    ├── 51b727b6ed808a715bfe48f8ca4c5e906e96bdbd.nq.gz
    ├── 5322173cde1cc05f9b6939cd926cf8432605c5ca.nq.gz
    ├── 5398c6482bf041e8c27ddfd7c2bb923fd09e7f40.nq.gz
    ├── 53d1cdd4718ca70ff540a46d748fb19214f507fa.nq.gz
    ├── 5826efd1f96e24650909a67c4bd452a234d8233e.nq.gz
    ├── 597ee9c904aac0630363269d4171fbe2b791651f.nq.gz
    ├── 59d2496b55def9adf827721c0b38a1a6e174518c.nq.gz
    ├── 5b815ca88005a983043d990fceb84e3d53720c6a.nq.gz
    ├── 5b92ba96daab910bc80d80356163a3887f221365.nq.gz
    ├── 5bbcd74ab58285e448f2d76cc2955bae6d5bb1e4.nq.gz
    ├── 5c7fc45f0c51ee2a95e442e0475ecd57386ea9e8.nq.gz
    ├── 5d2cbac44463e60a2ddb87a1b178c8b5ddd8861d.nq.gz
    ├── 5eb4a2147642a7c67cc129b757e3dfaf0789f1d1.nq.gz
    ├── 5eff250cd75030e7175ad8c0911ab8514811f18c.nq.gz
    ├── 5f1de647bc8580d4ad95e3f3d228ee420d1af51e.nq.gz
    ├── 5fe267178d11b507b6c2ae8f48036a233ddb7407.nq.gz
    ├── 600a9e96b5d6608f2ccdd800a7f97d72b8d0f9fd.nq.gz
    ├── 62167a45eb4b52aa16b5467c38fdac5689fe92fe.nq.gz
    ├── 627fc288d694ba84189647e0da3eff1c3c87b5bd.nq.gz
    ├── 64217882fc29dcec0105db4d016514f75ef05ec2.nq.gz
    ├── 64bb9bad994df3b9049f141e22ba73e1764d6b8b.nq.gz
    ├── 654c5bb14991ac87e206536609e4cadffe05f54d.nq.gz
    ├── 66af06e3b962be9aa1048e308b0fa76d88b3c738.nq.gz
    ├── 670ad187509022fbd95e609424f03e36336cfb6c.nq.gz
    ├── 68c36c64d75e80b7d736057035ac681e4ceead79.nq.gz
    ├── 6947975af30c25e3ad0ae122bfb998353abcc10e.nq.gz
    ├── 69c2958763ecb695b56a80dbdf215ae43fc55b75.nq.gz
    ├── 6a7695c06688c158d8c96ebe353806ef94fd3343.nq.gz
    ├── 6afea9e66731b8713e21b7788cc359e5c22fc9ee.nq.gz
    ├── 6b4ec9167b5475284d961bad8e31ee97d1c76891.nq.gz
    ├── 6bc862a7ddd2d31f7c93d287e00a49dd719adeae.nq.gz
    ├── 6d9eac2b3213cb5fe994a8fc01565bdaa1e57a16.nq.gz
    ├── 6da7f0304ff9891ae74e59188c7c72546abfdf3a.nq.gz
    ├── 6e970904ee66cb16013df8dce9883f0aa325ae92.nq.gz
    ├── 709135c84554aa1fc812b9ebb06552fd14b206a8.nq.gz
    ├── 7339158b80dfbcc6bb9c5955b323dd56aea03b12.nq.gz
    ├── 740c973de2153aa435e7014ca10231176e9cc464.nq.gz
    ├── 75907c3412e45b9d2dae9f647fbf12cca8cb4910.nq.gz
    ├── 75a89f9dbf7f4fb8e716dcaf423e2ec60c64f37b.nq.gz
    ├── 76c7945420a692b661460111011b5ff04b509cff.nq.gz
    ├── 780197ca09dadf26b44b5b2378e4ddb1632c74b6.nq.gz
    ├── 7803777b2795ca906080f5f9c8f1f741e28c58eb.nq.gz
    ├── 785aea476d5502e8289df2ac1667da62a3ff1120.nq.gz
    ├── 78d40a60376d49070d6ae4cf9423b93398664917.nq.gz
    ├── 78e72d7507a96ed937be239467bcb777a350e6ff.nq.gz
    ├── 7923024ec67bc43323accf4e910c49d6cdf59b66.nq.gz
    ├── 7986a3ae9b16b0d70db250092a68f49fb05309bf.nq.gz
    ├── 7af742a88b27986d479c229bccfd2c1e1c21e564.nq.gz
    ├── 7b13c52eeb96d9876dadd57dc933273ea400cec3.nq.gz
    ├── 7c57471512997782b350f261ee2c7c432147746d.nq.gz
    ├── 7c68744fe09012aff3d7159159f2c611e385e7e4.nq.gz
    ├── 7c6fa8c2e8ea5e163a69133d4c3f0fe15de180b3.nq.gz
    ├── 7dab2324651231d2bf19ecc3015feed4aedcf2cb.nq.gz
    ├── 7efba3d5ed3dc4cf0b5d0f9ae71d8ff4e826468a.nq.gz
    ├── 8219be88060b0fab4c23f665adaac2714efdf923.nq.gz
    ├── 86d49f785f0519fc40f8a1c06bbdb7607a448575.nq.gz
    ├── 87d806724d4fdc8989b5f78fc0cf882109679719.nq.gz
    ├── 8838d3e3c97351db7f98396b1ea894d3b8ce5781.nq.gz
    ├── 8933edc8b9d4906b48ab69303071f6ad393aed17.nq.gz
    ├── 8a20b2f8932ec7d9d0f2acf2840296a928033d55.nq.gz
    ├── 8a3d72e9aeeb51c54a5c54fce8e2adada496e710.nq.gz
    ├── 8a4678190c313f7316d83e107b48e6686dd35f4c.nq.gz
    ├── 8b222a3a86c3ce162adaa7b5f23d1cd6c303a8e5.nq.gz
    ├── 8c9df37d29f592c2d657134502faa56cf0c21525.nq.gz
    ├── 8d6c7ec68fb9f7cacce53b8bfb28397c9764f04b.nq.gz
    ├── 8de24460d1230ef5e74e6c2bfa285b8866781752.nq.gz
    ├── 8e168bd04a449b15ff36d5fb7bf4342d61be6f64.nq.gz
    ├── 8f2bb4480273ce1def6705041271bdf83dcd31cb.nq.gz
    ├── 8fbf8aa25d5f1cd3a16251d72b4fd6e146aef5b0.nq.gz
    ├── 8fc93e3edb61e11e4d1a3cf7d010497a1f212733.nq.gz
    ├── 8ffb566d100751d54db65600a4e2dffccb613a23.nq.gz
    ├── 90bbe3eabfabf92b9ea40199f0dacf0773c58d86.nq.gz
    ├── 910246cc0fa23e544ff604e4b33a5595f48b100f.nq.gz
    ├── 911d6c9fc60e14369056d4df463560b9777f0043.nq.gz
    ├── 922e1de9acf67416d63fc127e5272bde9db5ef0e.nq.gz
    ├── 92f720f2559440493d4fdaf226f954174ff32026.nq.gz
    ├── 9411d473fabd2f2360ca38dc4105909cf6234917.nq.gz
    ├── 942eeaa1932d8f0289f5d428430df32ce4d5c5de.nq.gz
    ├── 94fa86d64e3fac82c1e292ed75dec3c0e3553bef.nq.gz
    ├── 965032390f882ceab0c96830ac40da52b588c2e0.nq.gz
    ├── 9681be1c0453c101e1d289e8bc981524f5b9bc60.nq.gz
    ├── 999b56de48e2eea155740e4b0019ebfc29f6ad89.nq.gz
    ├── 99db6d1052f1296945e9f577e3d02ddc86c39c3d.nq.gz
    ├── 99f7d86a682117ea4ab4f5bc5fc1b0e56984c525.nq.gz
    ├── 9af1415ce85e690255a959799887f10d52022dae.nq.gz
    ├── 9b750b98a7206acd1963502b3da4e2b98c6f8ca3.nq.gz
    ├── 9cc9fbf7beba857dd3665aea675de365d3e095ef.nq.gz
    ├── 9d06b969fdc881ca95b58390496e86538fcf50ba.nq.gz
    ├── 9d18dab3c83ecfc93f68cb754814fea12f15ca2c.nq.gz
    ├── 9d34a2036722e21c2df632bcf05589265b393be3.nq.gz
    ├── 9e6d6391cbc6465668ea9c58e2c623ec1c60ea0e.nq.gz
    ├── 9f1cd9600a9965ae2d1dd1d95f948c7c7332f2cb.nq.gz
    ├── 9f6ac59cb4849ba9179b602cfdf2427f34a1e4bb.nq.gz
    ├── 9fa7e846a4deb5a727f50827f0ad1160ce52dabc.nq.gz
    ├── a0938988708091ea4950517c56ce8c5deba34e19.nq.gz
    ├── a0b632f1a3fa2c7b6d8529651f3aebeb3780116a.nq.gz
    ├── a18ea8ac30ca651078a5259505deb4f304c61b2b.nq.gz
    ├── a1d96cbc26256917b8abecdf0c0d9e5d5f6469bd.nq.gz
    ├── a25eb0742708db0ee35e5d19d60b1f28c5b3e944.nq.gz
    ├── a28536412ecbe65319b685111c16ee1934b2a26c.nq.gz
    ├── a3d76bd3f9fb274c9dbde5b925b9ab3b973fbb05.nq.gz
    ├── a55fa0f76d38571641b60cce0af2949fc43763ea.nq.gz
    ├── a5bc58a4bbf36c4c475496e4bfa8ec38da488698.nq.gz
    ├── a65f5517e782b2b9146eb6e8c1092dae0749e8bf.nq.gz
    ├── a78bb3681e9f90fdcbcaac16753f63ac15999f46.nq.gz
    ├── a7c7c08f23415bb895876521ec8d827ba1f9217f.nq.gz
    ├── a7cf545ee30c84ab5673bcea137287092fc26034.nq.gz
    ├── a906605117118e2346ba758feeea9f4132db8c3d.nq.gz
    ├── a97c102e7761f67dce3fd1703dfdd2de277e89d9.nq.gz
    ├── aaf3e0782719e739fdc9ac46b650f460cb770adf.nq.gz
    ├── abd0da4dbddf983066ddc5eeb587cfcb89d5c5cb.nq.gz
    ├── abd79aa7ef682ef9cdb42552ba5833471b053285.nq.gz
    └── ac74ba2c82b4177dca9e795cb636daeb883ee966.nq.gz

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

[databrickslabs/dbx](https://github.com/databrickslabs/dbx)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
