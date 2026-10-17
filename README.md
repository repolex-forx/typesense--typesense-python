# Repolex Knowledge Graph of typesense/typesense-python

RDF knowledge graph data for [typesense/typesense-python](https://github.com/typesense/typesense-python), parsed by [repolex](https://repolex.ai).

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
rlex download typesense/typesense-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8727d2ba58c0024f6a7dcf0957ddaff354df62be
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8727d2ba58c0024f6a7dcf0957ddaff354df62be
│           └── chunk-001.nq.gz
└── blob
    ├── 02c9e14284ce0bc66e4509df0b8ea6e4e0175537.nq.gz
    ├── 034bdec11373346a42640ba6ad0fa39982e81740.nq.gz
    ├── 03df911012a6115138c26f8cd4190d13772dbd09.nq.gz
    ├── 04f3646ae232df5b65a74d859da8d6d85a036c6d.nq.gz
    ├── 058d1ed9cfa956a6b2c4ae29d04a676606eb20c6.nq.gz
    ├── 071d8c379ca578967455fc356b105f29151c0b62.nq.gz
    ├── 072d367c080b19a238d4718351317c615fa8ef18.nq.gz
    ├── 07da9310f35ea4ff553aa12fd65cb6e76f4e4455.nq.gz
    ├── 099caeb8b9a4feccd03ef89fa46af7bcff02c54a.nq.gz
    ├── 0daf2b64b0171c6e5ccab9788d386a17ec0638eb.nq.gz
    ├── 11f8586736a527aba1666b9071928529e6629a19.nq.gz
    ├── 127d58c3212a6a2a2cfa9b816ee74f0bb730dc8d.nq.gz
    ├── 134716cd39086c373df5b391e3f478e84fd3983f.nq.gz
    ├── 13be8cfdd86e38703dd60e2b4d0a8a70b2dd90c0.nq.gz
    ├── 13f504c00bda7d5acf2ec5f029fa8e97079d2776.nq.gz
    ├── 144ebe6656d49e494f52d0bd38b9cc7b6f7aa082.nq.gz
    ├── 15e13d7162daa2f68d7a57a782639c171a6aa699.nq.gz
    ├── 16692fbc2fe007abd3b2308b08884f3fc9254bf1.nq.gz
    ├── 189c01461a187e9d78156a034edac55c1b48146f.nq.gz
    ├── 1bb6de15505058047a671d481d4dc06df8136ef6.nq.gz
    ├── 1c14a1e71c017198d79e1b449c949373f0fb8dff.nq.gz
    ├── 201c2c5876a47e806c50f29632680b8ce16d306c.nq.gz
    ├── 212912e54b8b5716227a910fcd325498d0b24c9a.nq.gz
    ├── 219c0a08a3d6927580f25f443166d8cea71e73c3.nq.gz
    ├── 23ab20d4f9de6efe5b9f1576262bdb364ed15f41.nq.gz
    ├── 25a54ba55bcbeb8bb94c4434e0a39c9118fc3d39.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26c11d529550d913e384905cbaf36f50a3964177.nq.gz
    ├── 273adb4c4a8164bfccf0888b4ee9fbccdc2e0b1b.nq.gz
    ├── 27ff6cf29950470a0fca01dfb522f209603da9aa.nq.gz
    ├── 2834e2810f8938ea7384b70fb4e22341b80ebcda.nq.gz
    ├── 2844004df0315792a232a51b746c9fd9c9dfe641.nq.gz
    ├── 2a0a9246bdc4eb63b69b4dc63db37b72d4a2a5dd.nq.gz
    ├── 2b91cd58ffe05c5a0582656bf6712c5f73963184.nq.gz
    ├── 2cc3dd94b5da5fa769ac3390ddaababde92625be.nq.gz
    ├── 2e905e4731e11ffb122761f1377ad5d382ccecd0.nq.gz
    ├── 30093d181cedfdc4a375864fb5f25ebe30c734f4.nq.gz
    ├── 30780409d58fcf984890ccb059cdca945ca86f65.nq.gz
    ├── 30edf75048860ddc4cc429ddc06af67f627339c2.nq.gz
    ├── 31cfbb1ab3077818cc7d5c551ba950e701852339.nq.gz
    ├── 326ddb87cc7681d569d96c966b25f262e347b548.nq.gz
    ├── 337eed425e281b387b43c681db4c0d9ce87d2996.nq.gz
    ├── 34df66243b0cdfb1046a7c84ac07223342777a4d.nq.gz
    ├── 383ec983256fea939423ca58562ecbcbc7c9092f.nq.gz
    ├── 3be47f41f6ea0f4678d089dcf69a5fc0a5f04c18.nq.gz
    ├── 3c252af829ba119ddabd47e6cd4c932cee0437f1.nq.gz
    ├── 3cacda35d45b4c97d75ac7d766362dc262f10bdc.nq.gz
    ├── 3e3e0f883491411d5dedee1b0f9446ed4615a831.nq.gz
    ├── 3f09d8e4b5b488b87dfe4631402931c29db61622.nq.gz
    ├── 4050ed3ddaf869d2d09511d1792a52de86d0a833.nq.gz
    ├── 4394896e175ab421e7dbd531fcf2633867a070a3.nq.gz
    ├── 43dde26089372e92465024614d2f326d5075abc7.nq.gz
    ├── 450c3458dc100a940224d3ac967fd6d139394bb5.nq.gz
    ├── 4639113c11dc15c91a9ec7f43f465f73d5417549.nq.gz
    ├── 466c0a297b69579f79dab1afb1cde6d958299ebe.nq.gz
    ├── 47fc81bddcd2a8b494d2219ae9d18a90289bbf91.nq.gz
    ├── 48f0ea0d5c69877b92845ff200b8264ec9020a3c.nq.gz
    ├── 49338b61c2b04bcd8b01178785546e51dbbc7f17.nq.gz
    ├── 49f11a36c281921c3aa2d48ebf83308edcc1edba.nq.gz
    ├── 4a36608206ae18166b09db9733fd72b8b626007a.nq.gz
    ├── 4d3db4b013f72aca130ddbdcf5c505c64d42d821.nq.gz
    ├── 4e081ad8cfab5c3955a764ff30ec3c73d70b96f3.nq.gz
    ├── 4e2aab272ae46678b1234727d3116f8a6ceba16c.nq.gz
    ├── 4e3172a68608b3aa7699e7d9d66e2e3cec1693a6.nq.gz
    ├── 4ffd73fd820e14fceca89d7dc5c0ed470df9903d.nq.gz
    ├── 519a1308bfe6a4cb23a1066914efbcd3eab45cc7.nq.gz
    ├── 51b9a1ac16d45d5313c398708f60e436b2e14ec3.nq.gz
    ├── 51cb2a0f0264e9b02b9362e6ba4fc70ffbd9a072.nq.gz
    ├── 55846238e173a1c3efc9ac1324ac6d9a987c8fb4.nq.gz
    ├── 58515735c8376c52729644565a7af3094be53dd4.nq.gz
    ├── 595a742943924c4b24266d571c02263a8ea5c86a.nq.gz
    ├── 5ad457051b7da5bc9c0088db08b55410463d771c.nq.gz
    ├── 5b49bae76948c8f27a79bd1559d48d943eae2d39.nq.gz
    ├── 5b907c30412e0cfe3f81a33e2105c505813aaac7.nq.gz
    ├── 5fb06ecbaa9b558a6e303fb600871b4494f830d8.nq.gz
    ├── 5fd6e370699441890066f8cd61071072b9e0cbe3.nq.gz
    ├── 6165de612ed19cf2dbfe76588486223c977657f6.nq.gz
    ├── 6233b7cc8d163326f9a9b9652aabb76de564bcdd.nq.gz
    ├── 6343904caaeac985b5f82ef0cdbaa5962f49ce09.nq.gz
    ├── 6577777d9366f75e5a6a889e02d251ccfd59e1cc.nq.gz
    ├── 6593baf3a9a934f0c018ad9bc0da2378a6693063.nq.gz
    ├── 6631f3559361695660a14ccdcd23ca2b2f702ad9.nq.gz
    ├── 66a551930e44da334d85ad7dad83eefcf469a0fa.nq.gz
    ├── 690ffc3da93fd0d57b43ad6625ec101258581bd1.nq.gz
    ├── 69cabdf0e96c80464df9f99037bd392b9a380cf2.nq.gz
    ├── 6b5a3f21fda610c5adec698b6089fa54803465f8.nq.gz
    ├── 6c1b60aa94d35e431fff77e6c6791eea675b507f.nq.gz
    ├── 6c1e2dd5f0503327437f679e4cf81e08ed11042f.nq.gz
    ├── 6c9771e2880fab5c8123cdc23d7e581b4d1022ae.nq.gz
    ├── 6d36296808b729c3411abe7f783b56e7cb861746.nq.gz
    ├── 6d7f9417e4e753a5a48f98ea9b06708c1565871a.nq.gz
    ├── 6f2295dbad78ab185bd593dc52ecdd3ab8ad0aa2.nq.gz
    ├── 6f905500cff822d61a3a7039328c73f13f5e3e4e.nq.gz
    ├── 6fb496a3bcc43329efd09b4c50240f0897b89534.nq.gz
    ├── 70ba25184a090c1df5529c3960e19f2df9d38a82.nq.gz
    ├── 713f403f585a32a918a965b051459ee173cb8964.nq.gz
    ├── 718df5ce9243c2f77e85ef8c1d4fd706c7dd8458.nq.gz
    ├── 71c134e67ff5c38549509e2d4c70a83d2c7c35b2.nq.gz
    ├── 72beb40b0e8af67a0b11f873ab305158fea1efa1.nq.gz
    ├── 73b7c3fe0684507153db858d9bf2b538264a826b.nq.gz
    ├── 73cd46cc4dd7b1d5867bcc332a610622c5247296.nq.gz
    ├── 74a6dbdb9b7ff2147d27c0a2348711757a2d7b11.nq.gz
    ├── 75408731d965781c106ff122e78b33fae0b05d39.nq.gz
    ├── 76a115c567ba00f98a4b686e6ea8cdccc15c9ff1.nq.gz
    ├── 784ea2d8b9355f18c4b0804d5aa5db7f0274a947.nq.gz
    ├── 78aff10e769b66ac85e113b348d964b2f7815e31.nq.gz
    ├── 796944bc69e722b9241bff9cd8cd6b1e5f1722fc.nq.gz
    ├── 79bd3ba9d4603f96a4512c62fc076b2087f549e1.nq.gz
    ├── 7edebb46179b667c1577b5d44a452e11ed9b98a6.nq.gz
    ├── 813539dc423da3725f25f4eafc3053daacb716de.nq.gz
    ├── 817c578bc475238354b9767a4be8711936364d39.nq.gz
    ├── 838400d57567de2bd4376056f5cfefa997bdae3c.nq.gz
    ├── 8514bb9bf4d2e50550c9188332945140209a8c07.nq.gz
    ├── 88bac30d5d347f43d45d4c17497ca737a855e783.nq.gz
    ├── 88ffd00ff3fbc28b16f8d419f2ab88b1f45f48bf.nq.gz
    ├── 897c2c38fabbaad0d5a34b519e946c33bfc03a1c.nq.gz
    ├── 8dedbb6770535bcb82c2734e40502bbb33403598.nq.gz
    ├── 90821ced678b3582a76d73d567338bd0e591e59f.nq.gz
    ├── 91a7023fa2d018f3120c54da4609e3e6174743c5.nq.gz
    ├── 9287dbe9f5bdf71cd23d0edfb7da4b8c239d1e18.nq.gz
    ├── 94e3c60992417845119af5e15a0f1dbf66648379.nq.gz
    ├── 95009ceda2572e8815555b10a398126c1feb450f.nq.gz
    ├── 9653364ba883b5928b2af5a7829c9e29dded5e0e.nq.gz
    ├── 97964d8254b385c3f03bc3b0c2a2c3ec420c55b4.nq.gz
    ├── 99c46673d0f518c4ba81eb19f0e39ec610120394.nq.gz
    ├── 99d11907ca902e039b7c6b505cd186fa22e5af26.nq.gz
    ├── 9b53da90d9b4cae850f3ae72b5740b5afb7970a9.nq.gz
    ├── 9bd494ead5fc518ad8c9498347a246fa4adee8d4.nq.gz
    ├── 9cfc8f8f84176054e5320aeba8d60a3bde1569b0.nq.gz
    ├── 9eec6624bcb2b73acb2e015fad5f55c0d9b0d9b0.nq.gz
    ├── a0dd1f6eb4aa99e984852206508a6f1eb84bd0f1.nq.gz
    ├── a192be6dfcd082fc8d424bbe812bb94f4271ff0f.nq.gz
    ├── a31ca32e2779d364b66de69c3b1bc8822aa2e3fe.nq.gz
    ├── a3a22d2f17476ede57c91d859419471a53d6a713.nq.gz
    ├── a6fade98008a0fc2c3bc242c39e548f3a5a0d1e1.nq.gz
    ├── aa32048d617055cbd634b897b4a57f3b4b5b07fc.nq.gz
    ├── ab1418796d1fea612f9dd21575945a74429d4be6.nq.gz
    ├── ab2f8a90c06071d547809006a2f771d7151f1071.nq.gz
    ├── ac3742826886b6deb2b542bf98a3d9580c243070.nq.gz
    ├── ad7ba49e32fdbee1630dc23576120d59c4a09a99.nq.gz
    ├── af682df05d4bc82cd5caea50f6a8f35b72bb525a.nq.gz
    ├── afe8638d4694c9f090d1eba350b7aaa13383076f.nq.gz
    ├── b0641eb008860fd8a8a2200f8ed00bc0f214d06f.nq.gz
    ├── b11347fb5a814aedd463dd37f6ac95779f7c2785.nq.gz
    ├── b12da74258b46f3b37cb849d51a08755ce77bb98.nq.gz
    ├── b2ce06952753b4e91f41e127f068ff71faff42d0.nq.gz
    ├── b442f7edddd3ace99b225da83a297fbec5156ced.nq.gz
    ├── b491150513d5b2a266c8e15e902873aabaa73b1c.nq.gz
    ├── b5cf565c1454db8b2ac9704944ebe60f81ef3a3f.nq.gz
    ├── b5ead2168a39b53d37a42f263dbe8bea719128a9.nq.gz
    ├── b64b8e477b4e44c8850583cb6ae7a11d5a3fb02b.nq.gz
    ├── badd5277c95dfb372158327ec873477da2868972.nq.gz
    ├── bbe6f5a571729c2b28cb07955a1307012f51d3dc.nq.gz
    ├── bf741a37a2d16b943274e065ba2e5b1de274e892.nq.gz
    ├── c4d863510a5d3c657fc8c1eb7bde200400f7bfed.nq.gz
    ├── c55d5f07d09c758dc2fe0e5858b0e163970fe2f2.nq.gz
    ├── c5d2c17f3acdc93f84b45d270f353a7edd882106.nq.gz
    ├── c6a0fd0d3af93089aa15ccfd6ce6fe71607ca4a3.nq.gz
    ├── c6fda6774b4e0993278902852a3b740415b4f305.nq.gz
    ├── c7983e1db531626546525e1a32d90ab6e026e94c.nq.gz
    ├── c7da18ed585fb63e64068025198a17a438c759f5.nq.gz
    ├── c7fa9331e0387a1164d9c8dc0bdf3920c2b510d8.nq.gz
    ├── ca5d28a9d5cec61bc380407164a767dfe5b2b653.nq.gz
    ├── d03641113416aaf05980069699e6536d6a74ba19.nq.gz
    ├── d0c03eb76d2ad05adc674b0db657f9b06fda11ad.nq.gz
    ├── d1021d8b0b61c2c2ecd95cb4999353f7f5fe4002.nq.gz
    ├── d18b8a612d1dbac462c7958b0f3df31efc4f3a31.nq.gz
    ├── d25f6fd626f586cf49a9e9c9aac7a950714deabd.nq.gz
    ├── d4684d2aecf75ec0ed381eac7ae207320beb0c7c.nq.gz
    ├── d5beae014baf6c3cceaa00807cfc50b7e7a69997.nq.gz
    ├── d71c4484e58c5d4b3d295b83642963c50d6effe4.nq.gz
    ├── d7bf1ebe3cb2d552c21d553b7e664aa33a2a3c0b.nq.gz
    ├── d96fccbca255828acffa44aa20044a9d144f55f6.nq.gz
    ├── d9affd901c19b0219a993be478464fe271456e0e.nq.gz
    ├── dc11d0b4dec6d5547bd2870e68125078b3fbacba.nq.gz
    ├── de4de73050bbaec94e3cbce010a67244f746d27e.nq.gz
    ├── def715e24af5aff39e547c99ce1cf455d3eae2da.nq.gz
    ├── e2a03a328950cebd3cc8d3bbe03e45cc46da60db.nq.gz
    ├── e2b00acb77cbb9ebac65e22b8d946f00c057a3c1.nq.gz
    ├── e3303193ddee5bca8b16b18582c837dcdc5d4066.nq.gz
    ├── e4a635aa8d6b63bfe6da455edbd1c45d247c2caa.nq.gz
    ├── e5bb7831639886ba882dd5037cfa3f8cce384ba4.nq.gz
    ├── e671c8d600cb085b199656602e03b02e3a2e7dd0.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e82cc93c62644466189b5f3e252f473877a1b67a.nq.gz
    ├── e8f868d3681eceeea917b7230f977495639ca20a.nq.gz
    ├── e8fa9c2ba1a7c8bc27453b32eb34f851d8a6288c.nq.gz
    ├── e90ec3dd73856ff16145774badf1603e2979ae03.nq.gz
    ├── e91be1a801c646f38464c1fd26170df3d54e8143.nq.gz
    ├── ea2b3aabead5f0416604af4d6465b09aca507f36.nq.gz
    ├── ea6b674b9d826a83d5df0b3ad03e257ba5fcb24f.nq.gz
    ├── eaa277d6f94b4d5f8268a899cf00734fc96320de.nq.gz
    ├── eb1780b7fd33debfd1162fbbf842295aeabdfc7e.nq.gz
    ├── ebdd485f014178514a620a85c8f6cfff5075e6c0.nq.gz
    ├── eccf42c5c40f7e2ddf775488b0fea9e7a38854c8.nq.gz
    ├── ecf49cc7bb3eda468e86c8b236be92bf69eba74a.nq.gz
    ├── ed18837814a6bb767596b25116b9d93d84977da2.nq.gz
    └── f1af51864c1768aacc42b8e24eb3ea3b87fce4b2.nq.gz

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

[typesense/typesense-python](https://github.com/typesense/typesense-python)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
