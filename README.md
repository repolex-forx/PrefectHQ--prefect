# Repolex Knowledge Graph of PrefectHQ/prefect

RDF knowledge graph data for [PrefectHQ/prefect](https://github.com/PrefectHQ/prefect), parsed by [repolex](https://repolex.ai).

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
rlex download PrefectHQ/prefect
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0338db3960aa578ce7e49e1db23d79af4baefd70
│   │   │   ├── chunk-001.nq.gz
│   │   │   ├── chunk-002.nq.gz
│   │   │   └── chunk-003.nq.gz
│   │   ├── 17a1b1d83fed3bd1084c7cd5b2a7cf543370459f
│   │   │   ├── chunk-001.nq.gz
│   │   │   ├── chunk-002.nq.gz
│   │   │   └── chunk-003.nq.gz
│   │   ├── d7791414195869baa6ebb423c3b0e4477c6abf89
│   │   │   ├── chunk-001.nq.gz
│   │   │   ├── chunk-002.nq.gz
│   │   │   ├── chunk-003.nq.gz
│   │   │   ├── chunk-004.nq.gz
│   │   │   └── chunk-005.nq.gz
│   │   ├── eb0e40c29398e8705ce7a2286828945fe488fa8d
│   │   │   ├── chunk-001.nq.gz
│   │   │   ├── chunk-002.nq.gz
│   │   │   └── chunk-003.nq.gz
│   │   └── ee531648b970b255057701acb167c2882c297ea1
│   │       ├── chunk-001.nq.gz
│   │       ├── chunk-002.nq.gz
│   │       ├── chunk-003.nq.gz
│   │       ├── chunk-004.nq.gz
│   │       └── chunk-005.nq.gz
│   ├── lsp
│   │   ├── 0338db3960aa578ce7e49e1db23d79af4baefd70.nq.gz
│   │   ├── 17a1b1d83fed3bd1084c7cd5b2a7cf543370459f.nq.gz
│   │   ├── eb0e40c29398e8705ce7a2286828945fe488fa8d.nq.gz
│   │   └── ee531648b970b255057701acb167c2882c297ea1.nq.gz
│   └── repolex
│       └── 0338db3960aa578ce7e49e1db23d79af4baefd70
│           └── chunk-001.nq.gz
└── blob
    ├── 00006e8cecbda9994ee8fafdc38a041eb9ebf619.nq.gz
    ├── 000112dcb07719dabca027d250c6afcef159409d.nq.gz
    ├── 0006d6a64dbea763e43dfbd4eccd2a0db2833ea9.nq.gz
    ├── 0009929868d60103104ec29b2dda5de147a733a1.nq.gz
    ├── 000eb00769aec07e5e1d9aa316eaed51755c5b36.nq.gz
    ├── 00175b3f6f5293da66f5b935be5bf980a1a3eb27.nq.gz
    ├── 00197bea0cfa159492e04640d4e5f9484bb60a64.nq.gz
    ├── 002350df97fbf463932203257648ec044f83973c.nq.gz
    ├── 00350669fffa0cdc90f989b53fff722cb89c694d.nq.gz
    ├── 003d3fc514378c2214143bac756deb55cbbe4d67.nq.gz
    ├── 003d596791d6e349f47c198c91d42619fd4cec1d.nq.gz
    ├── 0043d5b507d33f8a643c31f8fa5d1d2987c2709e.nq.gz
    ├── 0045cb5a4643ccefe43f83576e5179ca264640d1.nq.gz
    ├── 0047dd5d1db41a6e161a34b2772bfd3211ee3ffd.nq.gz
    ├── 004bdad1412d31a4a387bdb53282045d5289bb8d.nq.gz
    ├── 0059e17d578093e382a962051d65fdd6a095a853.nq.gz
    ├── 00679571003878db33ceeec2abedbdf3a8be5e3e.nq.gz
    ├── 0067ce682400f7aa1bf9443b3fc640b4480740bb.nq.gz
    ├── 0074a4d337aea16035bffc39d006328c79e28a94.nq.gz
    ├── 00757e1764b50d17b88450e8d31bfec1d817f0dd.nq.gz
    ├── 007fe776a97fdcfaf4255e1fa7cd57c9bbfe41f8.nq.gz
    ├── 0090797b3d46675c47f7020243e4ef8c80fd6ded.nq.gz
    ├── 00a12051f57cbc2ea31ce4e30a351555ad7a1a2c.nq.gz
    ├── 00aa80b9a1aaf7f8635db9310191cb490b88c0c2.nq.gz
    ├── 00b7af4b93650363dc5f38d383172d1f0a9dd460.nq.gz
    ├── 00c1707cd1f98a855e35882eacafb8e2acd348e6.nq.gz
    ├── 00c3fb383a5fc03066b48154591a41929dbc201a.nq.gz
    ├── 00c5f08036fb6f95ffbe315299c504a5196f8577.nq.gz
    ├── 00d15bf8c09a3b967caabe68e013e5b127d38e2e.nq.gz
    ├── 00d3c3b256d164fa7f1d8761ffdbf7bd9895e08d.nq.gz
    ├── 00d843c4638111ce0bb74beee5db22013f695936.nq.gz
    ├── 00d864f07b8d6f128a458a39b921245d58d80dae.nq.gz
    ├── 00eab98de2838d5da1bd64d5b8f865e49a2e0d90.nq.gz
    ├── 00ee4df98b855329459d402465095d961751d65a.nq.gz
    ├── 0104c189baa2c89d4923f6ade07fb6ab8c3b7926.nq.gz
    ├── 010dd94adae902a5d30ce8e3dc12e65fad21c162.nq.gz
    ├── 0115017b606dd6b3aef9bfe427e1485570d5e2c1.nq.gz
    ├── 01213061fe5905e1225de0441d3f5dca34251f93.nq.gz
    ├── 0121d9f83a1000cfc10aa81fc8bd5545b974e6b7.nq.gz
    ├── 012b8c11ae7e76d727e93b415b8e91160ce4be6a.nq.gz
    ├── 013025063d2acfd89acd23d71d3e21f3ca9e50e1.nq.gz
    ├── 0132e3d042201b2cfba03d8e1bf5b8d6955a445e.nq.gz
    ├── 0133da72ce25c836de85eb3276b529b9e6318887.nq.gz
    ├── 0142ede269dd15324eeb6a3054b6315c6f3ae58f.nq.gz
    ├── 01449514845f9793bd26274617582f4cb82a1f5a.nq.gz
    ├── 014887780e85dde25f17b1adc7fda53a633f195c.nq.gz
    ├── 014b757e11eb7c8c67104effc2031266f2e88050.nq.gz
    ├── 014be7adbe801be3f853fb259ee122699f49379f.nq.gz
    ├── 014c77d3ad89680240df73fc43a87189b513348b.nq.gz
    ├── 014e5edb01af22f19f2f19e3a72dc6df032da4bb.nq.gz
    ├── 0151b673eb6d4f8b7d20f8e0ee2ab83732e16c59.nq.gz
    ├── 01551f87c52a710df5586e681b05a11bfd53a046.nq.gz
    ├── 015cd3d9114c429f0010cb233ee200b556bf2aa9.nq.gz
    ├── 015e3496f3a30ef82d8c2ab56c94037b88e5e5ba.nq.gz
    ├── 016c7a4b5cd2cd57d061d0b42d6a255ef69fc20b.nq.gz
    ├── 017b34b9cb30a05454c552feb323c441ee1d0744.nq.gz
    ├── 0181ee9aaadf142ff3828abf178074a1ad7dfb90.nq.gz
    ├── 018fc339eec99b44ef2b325160a62e8de3e7cd3c.nq.gz
    ├── 01932b4e6745f7d4bc7cdcfcdcc6a5c099100e14.nq.gz
    ├── 01937428b5b91c63b703f6d5c0896a6bd56cabd3.nq.gz
    ├── 019edc350f4b5b7e2dd20c81461de5d4193e9033.nq.gz
    ├── 01a239e88629c51c94c1686d121a4e52827eb277.nq.gz
    ├── 01a2ff8add33e260c603a0b6ae0e0f3aec6b1c6b.nq.gz
    ├── 01aafc7d3c10a58cd94a48a3f0e3cff221dd5014.nq.gz
    ├── 01aec70af030b0b5e148d2a8f653353e4d794b3f.nq.gz
    ├── 01bd8cd240e4afbffff840bfc089f070470ece1a.nq.gz
    ├── 01bfe863995e9aa55a00799f0906346149ac3e11.nq.gz
    ├── 01c0e391f2ca935e35df2c5fd1f8b915d59953ae.nq.gz
    ├── 01cc4e0f49cfa77608fee92d71a3d9a3950e9c79.nq.gz
    ├── 01d65d28286321ad3cf80dbccf5b1a6547bcd84f.nq.gz
    ├── 01db1c34375db2996ef20f7a54b819864e83f368.nq.gz
    ├── 01dd440dec09eda5c4d0d84c1f4a8da0453ddf3b.nq.gz
    ├── 01df40270af305b2870d31ff0174838dcf9ece95.nq.gz
    ├── 01e2bd2726f3f56d22abcd77abe52727f2607f42.nq.gz
    ├── 01ed9ed6b697eb499ab242b6d3980e1a16b2a23c.nq.gz
    ├── 01f040bbfa07fe940f9e9d48e1dbcc2020d3ffa5.nq.gz
    ├── 01fdf376bfcdaa75a061c87d50df966263e79e2e.nq.gz
    ├── 01ff5ab26eb109df73b00742194b6246a3fd6753.nq.gz
    ├── 0200596945db2a9a512b5f689f04566ca4881ae7.nq.gz
    ├── 02096b58fbdc44b4899ff68ff724977714089868.nq.gz
    ├── 020c03c204c0e1235b80a38cbeedd7a7c544a503.nq.gz
    ├── 021465375286f9d4a758e3e8cd7789034f4fc738.nq.gz
    ├── 0218ae5226268365d87514e90cda97e25758b0be.nq.gz
    ├── 021911fe0248fbfc2ea0de5c718a199ef67be6ea.nq.gz
    ├── 021c7ccf3fe2052d5af6432cdedd74b55fc65ebe.nq.gz
    ├── 0223e90e2a78c2c2885674910937247c5a5a91d7.nq.gz
    ├── 022d6c322c9d6b294a5dda23350a94953049a2d3.nq.gz
    ├── 022d9776a578ed85a59c82ab6989a77c18e0eb95.nq.gz
    ├── 023130a0cd2d8974a3808fa17976bbc7ea47e435.nq.gz
    ├── 024bcb44a5209a6e50c79533a9c474a8460f0b75.nq.gz
    ├── 024e24a6679ab5a1ee9508f43ccf03abf5ecff7d.nq.gz
    ├── 024fe877173a900ed9fb54510c9b73875c3e78ab.nq.gz
    ├── 0254c528be12d16a67aa465b7f585ff8a12f2e21.nq.gz
    ├── 02567155e22a97db859b1ed337ac442dd641a6e7.nq.gz
    ├── 0258d0ab604b6f760998b5a9355ae7c16c825f94.nq.gz
    ├── 025ea4c6898167e7371b3f47af0cc913a61eb349.nq.gz
    ├── 026adbe078a8f2db319a393b6d3073910986a050.nq.gz
    ├── 027a395870c3817f3c187c2f4120d6f0a46894ca.nq.gz
    ├── 028107e45f15a97ff209e2f95003f30501c7460c.nq.gz
    ├── 028621d78ba4a5ecb5e36f5762b9c6d3905f1851.nq.gz
    ├── 0286a3c67fc127faf2344fd8276757ecca983fee.nq.gz
    ├── 0292025c3ed7761a1477039642ac4e3e341502ef.nq.gz
    ├── 0292660a80b97eb500a05f87db3de358ab1477ab.nq.gz
    ├── 02a830c8dd94391fa785dc3131a1d1fe2ffc7d59.nq.gz
    ├── 02ae6c13b353854fb9ed49743289d3a129efd9e1.nq.gz
    ├── 02b2f078c40baf225514199d76a98ef192f5e56d.nq.gz
    ├── 02b76aac24ff40374cccf1b68fc96417b2d1483c.nq.gz
    ├── 02b9faf26025723234ca8f2a34ebbca87832feff.nq.gz
    ├── 02bd160b21c99df35f66bbb1e5d5fa8494111110.nq.gz
    ├── 02be9268937d461fae75ad988e3f2c52259bda91.nq.gz
    ├── 02c8567d46b5b8a77c698d89a24de777a48d21d8.nq.gz
    ├── 02c8b485edb59f33b87925eb10034e2e07bf4af2.nq.gz
    ├── 02c9bd3318be948f0cb97a2e888d9ec3e635bd46.nq.gz
    ├── 02cc6632863a480b6481dc536dcea2867c8236bf.nq.gz
    ├── 02d696395b1fc2ed655a757364a22e5451fe46c5.nq.gz
    ├── 02d767528d7582444f9ce0eadd6eb47ee70e3080.nq.gz
    ├── 02da7c6ada6d0990bec3e65196638b93af7b4200.nq.gz
    ├── 02dc3f629c37b23b06d98aceb8995b4b80cc44a3.nq.gz
    ├── 02eca35f6a18f76b6d72a9ef265f967c387e2ee0.nq.gz
    ├── 02f8ab156a055c86d510a05de41c1c09629718cb.nq.gz
    ├── 02fb55fc526aab8dc39fc8e9fde22a5e158bae82.nq.gz
    ├── 0319a376d62024b40a5cbb0959bc841a495999c5.nq.gz
    ├── 031f77bfa1a0504632f37c024e86b9d0f1726393.nq.gz
    ├── 033c582b75f85c65abe80b2f54af6975134f3643.nq.gz
    ├── 033cd431da039cb831abfd50688aae5f45944ce3.nq.gz
    ├── 033f7e343a10c4048f99583c594287b126a54714.nq.gz
    ├── 034588a78113f86d090747b7265eaef0eead0aec.nq.gz
    ├── 0346903d112548bc39fdc0c366bf97602629479f.nq.gz
    ├── 03515d99694ea912e7df7be87f88c3e2e7e2573e.nq.gz
    ├── 03557ad6db4a701536a78959396a61b35c3ff69d.nq.gz
    ├── 035951677b395987a7b271f648aa6d1f0c835092.nq.gz
    ├── 036bdf9685600b28b689f97a9e845d47564767c3.nq.gz
    ├── 0375edf5a819b085bc0dcf2df6655a2e1df57207.nq.gz
    ├── 038c7c8c3746e1da435bc4973523549b182ce2a6.nq.gz
    ├── 03968866569e13bf04e7e8756f9c0928c822de0c.nq.gz
    ├── 0397d403b3bf2356700b76a636ddd9028cc01461.nq.gz
    ├── 0398ec523ce0ac559438d220befcd433c1f414ff.nq.gz
    ├── 039efdbc8b85272d96e370b3e516d28fd142d071.nq.gz
    ├── 03a6b12b895d15e6fad933b6be75e65a1b75c58f.nq.gz
    ├── 03afe49caefa2cf8fc6e6f6bf3279f23be405ceb.nq.gz
    ├── 03b5186cae74b218203b11951ce008358f330c2e.nq.gz
    ├── 03bf0e0bb67b85b79126224d3599789d47418a5d.nq.gz
    ├── 03bf81c82f8fdb59c007eb93efd5328fbabc8e16.nq.gz
    ├── 03c1c01bce492f834e62c35618cc3f78d9cbaf5d.nq.gz
    ├── 03c48d7803b40e56444d074bc525cd34d6e0ae0f.nq.gz
    ├── 03c4cb472071c809b4d9d98817ff993c466f041b.nq.gz
    ├── 03c79388f98f7ab54ae28b514934c5409c41ce18.nq.gz
    ├── 03d668ece965fd7d92aa993161dac9b705460513.nq.gz
    ├── 03d9ebe0ec8e7b9ef774f10ed2e49899e5589e7e.nq.gz
    ├── 03de35154d7088843554478b669ce051ead195b4.nq.gz
    ├── 03dfb67271ef80dd98be82fd4ff836eaef4c3735.nq.gz
    ├── 03e0e05b47cbeb5a55acb9eb398d79ccc98f7863.nq.gz
    ├── 03eb0d031b79b2e311d334fa333b39fbd7a9f4ac.nq.gz
    ├── 03eba03a3a3e01879ea8a8f57d928b96475e8f90.nq.gz
    ├── 03f9fb2c58e4c5e05fb851e7854941737dc7c2a0.nq.gz
    ├── 0401755ee708dfb059d41b6f760eb696e96830a1.nq.gz
    ├── 0404818930adc9a9795e6c28d020cbb2d5805ede.nq.gz
    ├── 04082c961665e568666e642f984fe2fa54300949.nq.gz
    ├── 040a49013b38999d0b701d792bb2ce8d184b65b6.nq.gz
    ├── 040b9b6db7021898a265a26f04123871d651a779.nq.gz
    ├── 040c3950facd1bbe40236ffe1a697aa764cc7846.nq.gz
    ├── 041158451680f3424df304e7d923409d1f48ef14.nq.gz
    ├── 04142110b728e73b923998b7c0f6970cc877655f.nq.gz
    ├── 04169a4125ebb8c65b1448580e447ecce9053e3d.nq.gz
    ├── 041a133d2abb2c7d416492b6f9a7711050c610d4.nq.gz
    ├── 0443c0009832bc1b2e15da3b885fb9c39eccbdb9.nq.gz
    ├── 04503af4fa36dc07c2fa5483d2a58f273834e207.nq.gz
    ├── 0453e416ae3151b6d5ed3380c1af1433be6dfa52.nq.gz
    ├── 0454730c7b3eedd6354dd79911376df6ddf5fa5e.nq.gz
    ├── 045a5e869745d387d33cca280c0a47c783efc630.nq.gz
    ├── 045e591f2241a1ff51c0cc80450321f4d4bcb142.nq.gz
    ├── 045ea7b45465370efe604c7e85fa6b56ac50e5fd.nq.gz
    ├── 047cd8b00e031f439ae0a15c822528eafeb898d4.nq.gz
    ├── 049314a73a20f1fb671fb007f9a013ddd54e9183.nq.gz
    ├── 04937d887124fa19e70e1e4df44e91569c49edd9.nq.gz
    └── 04a00f97dc1f953cc74923923f73d316d88b6a4a.nq.gz

12 directories, 200 files
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

[PrefectHQ/prefect](https://github.com/PrefectHQ/prefect)

---
*Parsed on 2026-09-28 by [repolex](https://repolex.ai)*
