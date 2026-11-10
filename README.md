# Repolex Knowledge Graph of jamesmh/coravel

RDF knowledge graph data for [jamesmh/coravel](https://github.com/jamesmh/coravel), parsed by [repolex](https://repolex.ai).

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
rlex download jamesmh/coravel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4072e041820f2d14529276340abb7150a83945da
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4072e041820f2d14529276340abb7150a83945da
│           └── chunk-001.nq.gz
└── blob
    ├── 00039a19a42fd059fe2a4025b5fa57a410740fa5.nq.gz
    ├── 000e75dccb57cd6d7ffe14105e7869780ac7e8b5.nq.gz
    ├── 00bfa4e234a235ba41c9a8858858f6702320cbf3.nq.gz
    ├── 0172f582574b60d72e80d1846c10bd9ef6cddc65.nq.gz
    ├── 01f6f883f86f44702c922c5789f460e849304717.nq.gz
    ├── 028229b3687cefd06abb90e1bd9d36cb180b787d.nq.gz
    ├── 029bb7ae20913cc61449c5d8e97ab4eeb97a1b36.nq.gz
    ├── 02a38499651d2cb0b090a52254ce28d8f5738dd4.nq.gz
    ├── 0377f00081f4269245b3579b777417920482bef1.nq.gz
    ├── 0392f9a4cb47806b076be1a809b4eaeed0af5fda.nq.gz
    ├── 039e577b4da4a772224a5e64301375eec40f7a64.nq.gz
    ├── 03f7c3ef57a8c7949b39d9dea0d14658cd8a4ebd.nq.gz
    ├── 059d951a9f8383d81c84889dce01c77382d3b4a9.nq.gz
    ├── 05e7fd91fe1cc49457f2b6ec829d0fd6ba20b9cb.nq.gz
    ├── 06a351790e5591e5a405381d5c6f56c19601774d.nq.gz
    ├── 06dd84c14f07065e4992ac2f274dcb4672b0d6bf.nq.gz
    ├── 0702b580f000d05b2a8deb17e42516959d86938f.nq.gz
    ├── 09208bf229632d2f6d208c71713be9aaf146f583.nq.gz
    ├── 09cf98693fe006384118657b551a3e81fba111f5.nq.gz
    ├── 0a2d57fe24b53fc35c111019446a490e5358fd4a.nq.gz
    ├── 0b2a507af1408277ebd9d214445a28398871bd6f.nq.gz
    ├── 0bdc1962b61072fec286c90d320c47882092a5ae.nq.gz
    ├── 0e5319e034e2e87692951ceefdf58b79166f57a0.nq.gz
    ├── 0fab64fb00d0c52a513253474c2a4931f5a3abe2.nq.gz
    ├── 0fc7fe93abc99476254c3cb4795d61c845cd2436.nq.gz
    ├── 11ccbd5159a466cdffc66b709ad9bdcfb0061e63.nq.gz
    ├── 12085b0641c03ff3c5087468d8352b25a21cbdce.nq.gz
    ├── 12674b08b24c28c6e71d95c595e19c0e8a3b4224.nq.gz
    ├── 128b3df1590b3dcd8aa696f0e2b94f77cd8fa0aa.nq.gz
    ├── 13e33dbc77653d72afa363ec6475569af8e2c0be.nq.gz
    ├── 1413fc609ab6f21774de0cb7e01360095584f65b.nq.gz
    ├── 161606b8f6d7629cf594e5128772a8aaadf57e14.nq.gz
    ├── 1791cee3e0ffa9f15f8d64ee713b6f79db254e1e.nq.gz
    ├── 187048eb120f6725e46bb4a414a37e3951f0ebf6.nq.gz
    ├── 18e63aee0cc0a93c905b4a2c2d2ad9a1583d09d3.nq.gz
    ├── 1939f3dea757f0a518324ef5282c87fecefb0412.nq.gz
    ├── 19d0fbb7ffe89a40925c036c99c20588dbea43ea.nq.gz
    ├── 19f67fc586922778fa60112969518e59dbd963f6.nq.gz
    ├── 1a344dbeaab4d0be3ac16f40cbf4c90e0057bad4.nq.gz
    ├── 1aad982d0e81b486aba0845f554e607bfad83393.nq.gz
    ├── 1ab32b60b8992306ee758e39451d4db2b8bdfda3.nq.gz
    ├── 1b4d3a1e385cf03646056f3aa1c8f859a7a7fd90.nq.gz
    ├── 1bcefd0bda6fa829e0c8d57f556712bb58c8c550.nq.gz
    ├── 1c0d9be23239186c23ae9d89cef6a1baac00612f.nq.gz
    ├── 1c968d6b333e9bb48ca02ff77a75ea8951bf2f73.nq.gz
    ├── 1e6111edb1d0941dafaa9f47e35580982bddac00.nq.gz
    ├── 1e9cb78a53be732a9571eba7154b4204b991128d.nq.gz
    ├── 1f07734c34073a5e805ff9ab70244c9654d194be.nq.gz
    ├── 1fced998a9a8a31e2db043cdd6bc2188d0584340.nq.gz
    ├── 2045308919cec471c5e60e89dc91da5187e50001.nq.gz
    ├── 21f3a8a7b1a1d0f7aaebbdd1637c7194156d6bf3.nq.gz
    ├── 22868baa7983ecd63e2d6ad6f89c97058b004b15.nq.gz
    ├── 23aa96e1b4dd91af57c65361f7079bcdd4f3a07d.nq.gz
    ├── 23c4c55eaf94dc4d66bf10bd895865193f0ad4eb.nq.gz
    ├── 24997dfb94f548fb4c6cfc51472d089d05f23a46.nq.gz
    ├── 251b16ded802ec40c48e35cf3acf8a2ea7fc492a.nq.gz
    ├── 28199cd10101a770da47179214aeeb0c88cf6099.nq.gz
    ├── 2859b88de5cd46e3c1437c76507a79d65a9c4b77.nq.gz
    ├── 29f3c970c347c92c6c0e32fb438f445f5a7df281.nq.gz
    ├── 2a9241f5967e59df245c68e78cc49c04a36b44e1.nq.gz
    ├── 2e433645021b3dc589368cea40547f3334bc9353.nq.gz
    ├── 2f7a71ce582e71e47e9826f2089544239b85378e.nq.gz
    ├── 308fc97bba7a04cfdcc47a4df2fa69505738f43e.nq.gz
    ├── 31d8882661324aedb8693f8bb7322c4af8374ae0.nq.gz
    ├── 32accdc00fed4a2d6d53b749ac60e899cfd1e9cc.nq.gz
    ├── 336e30c3c2a316dfb940b8fc28e548f0f1c2267f.nq.gz
    ├── 33aa4dc30371c34c2ddd1433356c9f90de79ba26.nq.gz
    ├── 33e8539767c9649fe7eeb50d2a85b3d41a94ddab.nq.gz
    ├── 33f5c3b2633f4c2ea0380cf718da3b9b9ffdf435.nq.gz
    ├── 3480f9beff161a92aa54a09395c4bbe9cf9e7b98.nq.gz
    ├── 3484990a25cfa55bfa89443fd8c1f4bac40a289a.nq.gz
    ├── 35852fcbad5e30e598f32475523f1f47b2bdf826.nq.gz
    ├── 3674e37a86d8a3fbe68627db37e2398bbca58a7c.nq.gz
    ├── 368605c2c4de04e70deb89238f4e53000fee3265.nq.gz
    ├── 37f9c09f9a0d7e8ef8d7eb6c27bf219e9a188e64.nq.gz
    ├── 38565a4d3de65831e468e7e47d8ea1019e94bc12.nq.gz
    ├── 386fa42bb325f9dbbde49da7b4fa1bf705a3f8f7.nq.gz
    ├── 38b3d7cd1f2aacefad23632f0839eb7d14408556.nq.gz
    ├── 3932680e7e4d7f818d8bd58ff692a19d6999233b.nq.gz
    ├── 3b787a2fd59bc9c1891b7cc003a788abd3e9ea76.nq.gz
    ├── 3ba8c2e6b961f7931ec831cabb81f27d6c0e98e3.nq.gz
    ├── 3c0e07770279f2f5dfba475ecf125fdf274ef34d.nq.gz
    ├── 3c31978316cdd5fa9383652d731a8d921d1dc14f.nq.gz
    ├── 3c339b5fb84ec31312036d3b19e07e1b423bfd2f.nq.gz
    ├── 3df42375979969b45118711c254a324e92568548.nq.gz
    ├── 3ec095936fc759539a9ed44f7b013f2d52c68681.nq.gz
    ├── 3edbe9f5a37cb2df114d9d3172e94f5d0880ff01.nq.gz
    ├── 3f1a42084c1e3a19da3a0d8575c567b78610f274.nq.gz
    ├── 426c8c34b38de5efc5e167e01dafb4d434c39e4a.nq.gz
    ├── 430a001fbb667ee439f1af51b86ec5ad2398e3c0.nq.gz
    ├── 453172c8055c193f434ac326b89e7b963ba72f38.nq.gz
    ├── 458eb4405434936d943de8665e7e8fa7e41361fd.nq.gz
    ├── 459ab740af58486960be08f030cb337d2d296209.nq.gz
    ├── 45c482cc256e1cf3b94781f09d154852702f0c13.nq.gz
    ├── 45d454201b0a25f3814e202fc1cffe9e08cf5708.nq.gz
    ├── 467cd60caa78795c29e57e13d2db0b95a56f5656.nq.gz
    ├── 46ba96612ec31c6cb9534149ef06e73d1d284b81.nq.gz
    ├── 46e3e9626e950faaa611773791f3c270baf0c563.nq.gz
    ├── 4931a7acc3e94ad22126a7b3d83e4fd3a8af12c8.nq.gz
    ├── 49484670a1935a21c09eee607ad8577e52d3b373.nq.gz
    ├── 4c54871def4034911e62e24601550099afd186e1.nq.gz
    ├── 4e7c7436b981ff09c3e1f0b094049eeadd2bff02.nq.gz
    ├── 4f745dedae03f675dc6f6d21147f4f47732cb84d.nq.gz
    ├── 50937333b99a5e168ac9e8292b22edd7e96c3e6a.nq.gz
    ├── 511a412e11362b07333b1bf862332edb3d7b2e7b.nq.gz
    ├── 51c2a79838718c4e99df53bb38f7b7190a57d3b2.nq.gz
    ├── 52fc4e2caa5bda23a5f07f7abc0a1823a612aa7e.nq.gz
    ├── 53b0ab6a628c563e9325d453b213af4b260fe897.nq.gz
    ├── 5438150c63dcb98d108ad892f384c8581e5615af.nq.gz
    ├── 546e9e89eae158bcb0d37fb807d0692da580f2bd.nq.gz
    ├── 55316be8c71f767b832cf44d96a93beab7a3de30.nq.gz
    ├── 563b15ccd6009134892a651dcb1662d2d65732dd.nq.gz
    ├── 594eea83f1b5363a735700ac8d985f74cfea42b3.nq.gz
    ├── 5a16d80a9aa78592ddc961b1d48b549024a3dbbf.nq.gz
    ├── 5a47bf41a5bd57eb2ab40a373959bb870266b273.nq.gz
    ├── 5b56105937431069e3194d511222d5c9798684d4.nq.gz
    ├── 5bede243c182cdfb9c56753d6af24d41f0b4295f.nq.gz
    ├── 5d74f5a2cc47177b2fd9ed870c9db1a211d19bbd.nq.gz
    ├── 5da47bb0a8c9e14974a1f597d14e1d3924cd6eec.nq.gz
    ├── 5e39e7b53b912f0dc6d570c3edc80928f1a68324.nq.gz
    ├── 5fde8f37381b10a6e8f5cdf3c65510390c6a738c.nq.gz
    ├── 5ff621dd5473ec93b30768ee8d7737c2bb3c39c4.nq.gz
    ├── 60bce5667e6bc52bf8ab1643cda29d3d28f7915f.nq.gz
    ├── 6167622cecfb5c0f04156363565e3d4109fc55c5.nq.gz
    ├── 61da05bf07f8f814cb0f36377264c30ab00f847d.nq.gz
    ├── 631f1ec3f92a6d944aca47e7ad526cbb641e3525.nq.gz
    ├── 63de8f9061f91ba9898c634beab33303daa0078c.nq.gz
    ├── 63e859b476eff5055e0e557aaa151ca8223fbeef.nq.gz
    ├── 64539b54c3751a6d9adb44c8e3a45ba5a73b77f0.nq.gz
    ├── 66c247e067d1e818c579ae3cbea29b8bc4e1e380.nq.gz
    ├── 67331c80d57aad00ecd07c7ef593a6a6f11a9a98.nq.gz
    ├── 67685188fa1bd273566d171374a2bea86a7ff42b.nq.gz
    ├── 67e21834348ef2323c0d1d97d9544eb5bc122142.nq.gz
    ├── 68401faf0f09977e537dbd370d80014155834131.nq.gz
    ├── 68403edb130856ab80584eceaaa6b10855cebf45.nq.gz
    ├── 68b84f842afeffb95b30ec5fcbeeb23215644b08.nq.gz
    ├── 69cea4c4250193f081cdbac81ffb05a64d7bf328.nq.gz
    ├── 6af3efad07803f24e47c9255afd95ac702eebe37.nq.gz
    ├── 6b28dead47dc2cf20d4cc4b8b6a97840ede80976.nq.gz
    ├── 6b89c0fc318311ee54b54dba50748abcba63688d.nq.gz
    ├── 6c7fa40b98db056a6d36faf96c77ef85d4a68bba.nq.gz
    ├── 6d32d11d1cf9dad25bc2304855b91b7a84349129.nq.gz
    ├── 6e83ec0869fe524bcfd162ce9304cc7b50f62b05.nq.gz
    ├── 6e9aa04111ba8091724fa00f0770e7e42dc2aea6.nq.gz
    ├── 6ec1bb1894109926a80a7c999d9d0b8dc3852833.nq.gz
    ├── 6f92b9565570463a840d01c6ca4f29519392b455.nq.gz
    ├── 6ff9227922122b6dfe5dc988c9487e173b1cfe5b.nq.gz
    ├── 70b358f2d396116f05dda0b28e0f24791c6b1748.nq.gz
    ├── 70da22624051d3a3bbc3479520a7038a9dbb109a.nq.gz
    ├── 71580383e599ac30599b07696cfb50a8649e59f0.nq.gz
    ├── 724e84809e3ee4137a85d2ad3deefd82f2398733.nq.gz
    ├── 729b7d6c0ca7005576a4ef03a925f570e0cd0b1a.nq.gz
    ├── 72b8ef3b62db6f873f4205fc637386a08a39ca5d.nq.gz
    ├── 72dda234edaa4d2b0e9e2c5420d8685e920ec3e5.nq.gz
    ├── 73f4a1928ee1f9fc5cd56138b62d3be419edafce.nq.gz
    ├── 73f5298394483947e1ce966c01630a32de962f4b.nq.gz
    ├── 74845e88a3f6bc18091f893b59c40963b4cb00c6.nq.gz
    ├── 750da4e19b9a8713ad898b0b015d9ada7db62348.nq.gz
    ├── 75d817a3d3b5d447fbe9cc53f24a34398c7df0aa.nq.gz
    ├── 75f0d4e4e1164a6d6226b6b8ff3bea121d43fa12.nq.gz
    ├── 777af62ba279222cced9628ec3ea998f67a12eb0.nq.gz
    ├── 787196c4233f4575dd13072c74a529b7e8c0aec7.nq.gz
    ├── 7929766971b748e40e362565c76b69c879b3a3cd.nq.gz
    ├── 796cebb3fd044b31cfa4b19cfce105b06db4d4c1.nq.gz
    ├── 7a300022c3efb0f791687a0d58460d80182303e2.nq.gz
    ├── 7a47e6f6476dbde937aadba8f7e5979c7cc2ed56.nq.gz
    ├── 7adc34682846b73ac0cf58cb7278d9c57bd4600b.nq.gz
    ├── 7b3c914b6ba5aa489f6ee8600e60c0e7817c33d8.nq.gz
    ├── 7b563709902921cdf12abc8f751eaf290a052a3b.nq.gz
    ├── 7b9ac2a4f981207e7b45febfa00f5f0e9977fb69.nq.gz
    ├── 7bd38619c6fb3e7a110fa21ac086b4c3cbf144d2.nq.gz
    ├── 7d129f5de523cf3d85376c4527de23d384523b46.nq.gz
    ├── 7e79592a570af446f3b7618939b9c98b2725e474.nq.gz
    ├── 7eb158168fad673f9d7c4472e261a7fbd27a7d22.nq.gz
    ├── 7f980c6c7452b646aad977a6dc54862f99cf01e8.nq.gz
    ├── 7ff3b40c2bdae3f5ec83e659680b22de885f674c.nq.gz
    ├── 81689026f67e9ea0f5399dd7d8ba54721eb1c816.nq.gz
    ├── 82401d2715321cfea7c8e82ab9c66fd6ab4d0f18.nq.gz
    ├── 82ea5980d9f3a7b3ee5a32399402eaf6030cce28.nq.gz
    ├── 838b864f95347a8237e7fc632b6ef067b1958a8b.nq.gz
    ├── 8430f2ec2fc92c40d1619b70104662844a025f95.nq.gz
    ├── 844ba5b1cffa6d21d35e35a20ac013ae0fb29100.nq.gz
    ├── 84ef0d3251fccdce881cd76f08a9134a4dd37baf.nq.gz
    ├── 85e13e222b8525f5686192ebebb42e00f7418b0c.nq.gz
    ├── 8629fbc8a3672ea408dc4f092fac7a81df287415.nq.gz
    ├── 8657be59d7933b9ac23fa2e271bad54b8d3e924a.nq.gz
    ├── 86d302aa91468c4216bb5fa2b614db2a779820b8.nq.gz
    ├── 86f4b8ca04f8d10574f189b8f73bdf0d575675e3.nq.gz
    ├── 871d6d18816f4749034e3fa3735edef569e70812.nq.gz
    ├── 88bcf89348a32fc4b2cd98b57913bffd033c770a.nq.gz
    ├── 88f7095c926cc3a796fe2db241321462056067c8.nq.gz
    ├── 897ab0c4a827884b076eeb2320f521e947fe532e.nq.gz
    ├── 89a16b6ce4b8c2c0e21f07691e971ff0ada39f53.nq.gz
    ├── 89dc472c163864dcc324de61018f7940b7dd3bfe.nq.gz
    ├── 8a2e99a535d47e5798b167d1074ae2c77cab21e7.nq.gz
    ├── 8a60bd18748e28a0a4b031dda89bed54bbff7b3a.nq.gz
    ├── 8a822124b545ef530c133d44bbdc02a3b311e2a5.nq.gz
    └── 8aea2299b9a85e3b69a887fa9d202d15d3184c6c.nq.gz

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

[jamesmh/coravel](https://github.com/jamesmh/coravel)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
