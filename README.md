# Repolex Knowledge Graph of run-llama/ParseBench

RDF knowledge graph data for [run-llama/ParseBench](https://github.com/run-llama/ParseBench), parsed by [repolex](https://repolex.ai).

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
rlex download run-llama/ParseBench
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f9e58e74de783f4f9743b9daae44c226b0256b7b
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── f9e58e74de783f4f9743b9daae44c226b0256b7b
│           └── chunk-001.nq.gz
└── blob
    ├── 005b2ba5190dd1e16d5f91d3f3a642b042fb6947.nq.gz
    ├── 00bf3acca11419ea918cd509078aaa9cfbb404be.nq.gz
    ├── 015d157b41f95a81b546a012c80ade06b753d0b0.nq.gz
    ├── 01c1e8afe22fa5c3930645fed6f80c678387ea54.nq.gz
    ├── 01ffd9123da6834dee68f1679517fc3531508109.nq.gz
    ├── 020cc37f5aa480aed94715e2d0143e6c2728f9d3.nq.gz
    ├── 02e0a711f733c2e1542f091b2577106414e3eeb3.nq.gz
    ├── 032b1fa97302d8330911912491a4964540b34a11.nq.gz
    ├── 0348f80999b6f1c0aaa941c89f0508c371379ac7.nq.gz
    ├── 0418c127a6f5eb9ff54ee985107c56abdc86d5b8.nq.gz
    ├── 04c7377d1c474a5c695517ae008d2f185b6c5523.nq.gz
    ├── 05adc95720e7b33e7ce8e42906fb6f38a7d88e61.nq.gz
    ├── 05aeacf8621e801604bcedef40d439f118b03855.nq.gz
    ├── 06a9165d36a257a5158955fcb30aec7f75e11d76.nq.gz
    ├── 07394fb70064ca3fd78cccacb44e6e22e685e485.nq.gz
    ├── 07e603bc13f8ad5097250ee110908abc4611ff7a.nq.gz
    ├── 082cac08ae6a8fd881ec581d70c023f490adcd05.nq.gz
    ├── 09df8ef6f8baf5fe30c4fd08f83bd08ea7b13c29.nq.gz
    ├── 0a9fea9e49f2ebb124e8bb57f60dd0580595c87e.nq.gz
    ├── 0bbba19743b3b188685cdbde387c1e95a67b1fbf.nq.gz
    ├── 0bfbdacd78d021081e5a0a505873ea1f5713f8b3.nq.gz
    ├── 0c05d4f2f3c3c522151d72d5b080f9bb5a70f722.nq.gz
    ├── 0c4f12e42c54e0273753e1d55e566d1d23b5bb8d.nq.gz
    ├── 0cb957e10f8903ee1ca4fe3500a84b251e565b0b.nq.gz
    ├── 0cc753aafb1f390afb204f017ca717a92fcdb545.nq.gz
    ├── 0cc8de1bc8bdc12dfa27496e04a6b6c52bee6381.nq.gz
    ├── 0d1502ece440d73e2a5a0d1e3f3e4c4cc92cebfc.nq.gz
    ├── 0d6d64bfa1bbad2f1b49caaaa135fc5fedd32f57.nq.gz
    ├── 0e41b949364d3c77fae1d69846ed7678dced6f5a.nq.gz
    ├── 0e6ebafcc8dc36bc94d07fa5fdddbee96aebff4a.nq.gz
    ├── 0e9d2fd59089281e60c230158301070f6adf2161.nq.gz
    ├── 0ec0893e6e6afd47fd129196fa42f30688079fdc.nq.gz
    ├── 0f58bdc1d7ddd0333d6d19e62fb603539e6217a9.nq.gz
    ├── 0f94ce0a2622a9e3db49496a21a08304f8080bb3.nq.gz
    ├── 10042c97bcda93bb549be07c23f00c2e7d1aafa0.nq.gz
    ├── 103ff828350e8ac900c67a9c7c7ae07d9c907985.nq.gz
    ├── 10cbaa8d434075d0db286456946e263e7248201d.nq.gz
    ├── 113de89df94ab710e1e644683c9ffb7196909ea0.nq.gz
    ├── 115c578b216cec0201cd64fbec5673a9b485c082.nq.gz
    ├── 127a3fb24aba4d42bc92ea9090884676a170e5c4.nq.gz
    ├── 13234e638d589facd44010470af841f4d3ccfd3e.nq.gz
    ├── 13c33a3f9a5beec51b2737b790410f55e6415c0d.nq.gz
    ├── 14cadcf5aa91aeee98f4d6e2bb05860b0f1ec9d7.nq.gz
    ├── 155df4a411780dcd0b10cbab6e4331d83f266f83.nq.gz
    ├── 15f3a5d2385a2df84ea4f3362810a03ff0dc4623.nq.gz
    ├── 1649d5eb5c2135874d98c7bc286d911428c40b19.nq.gz
    ├── 16bec2a384d91577ab677620094010a7e838b85e.nq.gz
    ├── 1752961e6c05d68879a667e4efddf7f42dd1258a.nq.gz
    ├── 17e22c07728e61901a76c97d6df26164d57f5e10.nq.gz
    ├── 18a89d9dee32d6f1a2747423d47bde9b1da6850f.nq.gz
    ├── 1966907d38918508751cdb64f77c6adac690a3ca.nq.gz
    ├── 1a54891b169070d3f671e4e50c3c920f7493ffc4.nq.gz
    ├── 1ae27f6f7d3888f8b5b91c160d27138d12208c37.nq.gz
    ├── 1c47356c42b37833435b41d50fe6a2a936a0d17b.nq.gz
    ├── 1cfc25aa156db25ed28589c304d58a72e5363fae.nq.gz
    ├── 1d1eb97216029a5ca2c9c8eabb0731642a74d865.nq.gz
    ├── 1dca1c17c038159a2edced7f87c2b9ad158de340.nq.gz
    ├── 1ed04bb5037e6c7aa5294375b92df7b6938cef46.nq.gz
    ├── 1f406152b2d08b010a00dd6785544e520f250074.nq.gz
    ├── 208e16ed9dea973329854ae6a56ff10f6e7b072c.nq.gz
    ├── 20f7807c485eeb6d61fe5afb8fa190f80c35cb60.nq.gz
    ├── 2116fd76d849082146863313df715b1c4da5a65b.nq.gz
    ├── 2130558420a13d92d92287b4320fcff4b9efd98a.nq.gz
    ├── 21f6d96b197650e2b986d6bfcbd9c0b18f280968.nq.gz
    ├── 226e26d5fc5dd529b2b05cbaed2d2e244d3794b2.nq.gz
    ├── 2276b0cae6dd09103c65f6cd720a870212432c02.nq.gz
    ├── 22b45f75e7e69fecd7f7b386101912bc4dfb39fe.nq.gz
    ├── 237bac1ad1a49971ef92430f7b5eb01973d2b4ac.nq.gz
    ├── 2399f1a444d170760993d7a4d8edf9be9e18b625.nq.gz
    ├── 23cff13e1fbfadd6b334e09b1ab55a924830082a.nq.gz
    ├── 245f469cd9745a08b14877860980cfe87543a7b4.nq.gz
    ├── 254c2190a81d37f6b243fba2a222961e993d04e1.nq.gz
    ├── 25f8d17e1f477e889d4f51e07de365920d319cfb.nq.gz
    ├── 2615c56ebb47bae46aaad1afebaada713392aa36.nq.gz
    ├── 2666f74c23393ae5f8677ff5a0550d0a0d806979.nq.gz
    ├── 2679c345d732a8a6186585ee3e6d5d771c023d50.nq.gz
    ├── 2782ba5930516ed82e1f2b9782aefe382b5e916b.nq.gz
    ├── 28053fdc4094822302bae995dae2bc508decc0a4.nq.gz
    ├── 283e72df21fee288ee885e2ec3e8b5476f69077d.nq.gz
    ├── 2a0b14b088db1a828b795b35cc6680aa513ebd24.nq.gz
    ├── 2af62fb94061191bd67b64a87f57fdb67d45bfe2.nq.gz
    ├── 2b8d4c51af914f51da5f21b3bde142750e9d7a65.nq.gz
    ├── 2be24e2bbf5380b47175f868c250d13ae5c934bc.nq.gz
    ├── 2c38f64a03e9fbfdc921c4dd9d806346837f3d62.nq.gz
    ├── 2ca1a1499f3bb872a0dd7c34ac918e4501f63e11.nq.gz
    ├── 2d97975b17e9ff7e0028f2f12e9f44bbd8292de5.nq.gz
    ├── 2db9e28f143ebc2eef0dcc9484e65a2a88b8e227.nq.gz
    ├── 2df50658788ae570e0a4904c0b01ba2db92166ce.nq.gz
    ├── 2e5f1c084fbe16403581e2ea75bbb60cfd34a301.nq.gz
    ├── 2fb2b654452900d95d5f8aca699eb5386e16cd04.nq.gz
    ├── 3277c733285a64ff0206cdd781f4669901224b37.nq.gz
    ├── 32c14098ed6c2457e6dff0a83c6fe4402ff9f1ce.nq.gz
    ├── 330ce95b6ead697a0024fc97721c6efdaff3bb26.nq.gz
    ├── 353086eed1e33eed544c771318aa8ba4dc03980a.nq.gz
    ├── 353b0af003e2f59b048ba1bc50f43ec17173bde5.nq.gz
    ├── 35d3e7d51d19d5462722efb61e406309f9c563c6.nq.gz
    ├── 3715686922c1afe38a69581ee096ff6c358a901e.nq.gz
    ├── 37742b8dac16e3960957466ce2a36cdcbb99b349.nq.gz
    ├── 3774c4774d7eae9b2432716623f28b14dd4223e2.nq.gz
    ├── 37b5c2ffa0d29019017092753091763cd7ccefd7.nq.gz
    ├── 38c1442ee2dcd07bba28de12cba880ddd843ec43.nq.gz
    ├── 39545db3cc57e8d411147de4ae04e3e13c74e5eb.nq.gz
    ├── 396f8815660f940d36f05aa26285ce60af8353dd.nq.gz
    ├── 3a5c6a767dc24328730319669f8f98ae8c894c07.nq.gz
    ├── 3aeef0ce6370e3af77f17f9741857b453118589b.nq.gz
    ├── 3b7dda97d30bc75e4950ad677df866a54be66247.nq.gz
    ├── 3b90af913d2c19c2ae4ab99e4a8cde230209df92.nq.gz
    ├── 3be625c80499807b507b7fae0b0c0962a14953fe.nq.gz
    ├── 3d50ac0eb1162719ea70e724ed836d4598685ae4.nq.gz
    ├── 3e64a83bbda8359726f073f49deb75aafd82e7c6.nq.gz
    ├── 3f4b2f921fe6d00d3384e9593feb18d9fbd00696.nq.gz
    ├── 3f9d5e5baef624cc90de209958c69b3913812cb7.nq.gz
    ├── 400626887ed6c48f23ece9a4e5cce11151081e9d.nq.gz
    ├── 40095a38bc354edad5ed2a34c9855ff8d5699063.nq.gz
    ├── 410c4636495119fc16eda47ff1e9c656e1410224.nq.gz
    ├── 42033260cad4e3f1dd5df60dbb07e1618cdf4c6b.nq.gz
    ├── 42721211321a9388ffa7175beacb9ebd04626e42.nq.gz
    ├── 42b972767e6e2d5487167ee36841455bb2ebedb6.nq.gz
    ├── 42f542b5f4091e62e6494484c9c0949d190eb068.nq.gz
    ├── 444c7539069d8773f54cab3170cd1f5e9411edab.nq.gz
    ├── 44a96e47ba71c354c32e4f06d6917573030015f2.nq.gz
    ├── 458bea504c092bbb652101d67233b83b7ad41ec6.nq.gz
    ├── 462252daf51a1987099e7de84de17ee5113a965a.nq.gz
    ├── 46472750e52ca3c6637e241b61af05b868133551.nq.gz
    ├── 464e7ca9e8f8c3423f5e4097a1734ad18a784abb.nq.gz
    ├── 46533dbc30c03d9b07ec2de8f4a361b8e49ed590.nq.gz
    ├── 469b0501a35b838baef522628e8454fb0b5e7f7e.nq.gz
    ├── 469ea729390357198e484e3f89e8414ac0a3849f.nq.gz
    ├── 476673563013d3a96a16e91012afa2f386c1e4dd.nq.gz
    ├── 4845b11b273255584daab3f2466eeedd655f6c67.nq.gz
    ├── 48b771e57c1c0600976a274b59f076d86c54cbd3.nq.gz
    ├── 4a0bf48f700b43dc74455e2c2a59ce461e62b109.nq.gz
    ├── 4be5bfbe798e2c7440060ede71527da0566728b1.nq.gz
    ├── 4c3e0a60617099f6c1ffc52fe5851fe86a0399fd.nq.gz
    ├── 4d89c85b756ad278328eb00037b5428732b69be5.nq.gz
    ├── 4dc6dc9b9cd14483ddb96d291a442715ff42799e.nq.gz
    ├── 4e2e97cd6f299d3daba482cea4de2a6fdda5ab58.nq.gz
    ├── 4ecfe1e34ef9605f55c10bceef9a020685495cfe.nq.gz
    ├── 4edcd544b810d850b408a705c686ee9f08052491.nq.gz
    ├── 4f3faea1033a594657317b0b89575c88ffcb098f.nq.gz
    ├── 4fa03a423b38e19a3861cac7cb3818559f360a8c.nq.gz
    ├── 5059a98ad2b0faf6b794ea7baa70636e54ab419a.nq.gz
    ├── 51f06f807c6b2fef3e04ea487ab5a94f3055fb33.nq.gz
    ├── 5237a172875101ef46b7fa5338245272ab16b1b7.nq.gz
    ├── 525bdce11e6b0bf189ebf60a54e017d0ad720efc.nq.gz
    ├── 525ec1c64cd6478b19c8047057245fb3a6e1d470.nq.gz
    ├── 52672f6794a597181740b3eab2247641845b3651.nq.gz
    ├── 5371536ccafaf4ec5d90126c6731573a4288fe2a.nq.gz
    ├── 54e73b29da97dbae39771bccef15e1b055e0f979.nq.gz
    ├── 56e70f756c1fb35c3f7ba44bf05b8c9c43428401.nq.gz
    ├── 572ce53949cb1a7a838319555a23d37eb2691fd8.nq.gz
    ├── 577a759e73126f1dcb6faf4c6dc8fafdaf26a55c.nq.gz
    ├── 5815ada5150853e6171ca2235f9d963f81390aa1.nq.gz
    ├── 5a4e5d15ff8c7d090641f292dc4961c6e48e7960.nq.gz
    ├── 5ab1d0614b17fba24e8b0912da8952e485ace98d.nq.gz
    ├── 5b426c78e5e40c94fbf498eb25285332b596a746.nq.gz
    ├── 5d00db9871c107b442b0ea24f883f70a21117ab3.nq.gz
    ├── 5d6ea7281c6476314cc103216c83d0b7b857436e.nq.gz
    ├── 5db3bb75415113969791256d242b5785437878c7.nq.gz
    ├── 5dc60e0864ebe76983104dab916cbd277000f761.nq.gz
    ├── 5e0638c76b77b02f786af44988742d6345cdf712.nq.gz
    ├── 5e4cc4cd53367c0c87f132b6907f934ad3f2b148.nq.gz
    ├── 5e6b472f583e34a1cca751440d4f241495475723.nq.gz
    ├── 5e8e92c60d21603c2007a778bcbdd1bb95431e95.nq.gz
    ├── 60a48117551993dc6337a46fef61da85f5c5bf5f.nq.gz
    ├── 60bb82174f76c0d497402777665822c8e8841956.nq.gz
    ├── 60d207a65e7da72b83544154891175947a993ad7.nq.gz
    ├── 61270b0b827236da847b15ff44dfbfc7317f7d1b.nq.gz
    ├── 6195e6cd8c617aa9b10a7597c093bdb8444e3933.nq.gz
    ├── 61f872ba1ca38d13725c8d7dcda5c1470fcc0148.nq.gz
    ├── 61fda82316c322a0494e6410a304e6f783803980.nq.gz
    ├── 6224dddd700fee9763a04c3c0d31a91e526e03e1.nq.gz
    ├── 623c54e3a5a5895a91cc0c860179fdad72f9e77e.nq.gz
    ├── 62730a183060d99636d1d16176af4f8959f1ac44.nq.gz
    ├── 632a794066fbda73eefb2743d12a27b38e73c690.nq.gz
    ├── 65ed8e0214e7ba8c92ceb37fde0a6c806adf10ea.nq.gz
    ├── 666ffe087f744859e2698c1c69cf65db118702cd.nq.gz
    ├── 679e795c09e7adb3fcd3ab02077abaa935a208cd.nq.gz
    ├── 67abf8c65a61a5a62b585571682c5626e6c61270.nq.gz
    ├── 69946e0305888c44bc9ccfb11b9d379d353721db.nq.gz
    ├── 6a27a1399e0ccce4db16abd222791b91fa2abe77.nq.gz
    ├── 6a66932a1a19380592bbade022b9c1c21c127bb5.nq.gz
    ├── 6b0ce917d799ef8cdda6e4d21cbad40b766c51af.nq.gz
    ├── 6b7145448d683ae83fa0b6b50a2cb23c2be7f480.nq.gz
    ├── 6c18d14eb45043bb00c3f19c7a1c8d6b830a2f45.nq.gz
    ├── 6c59dcf7c82e7d63917e40331372d9bbfd642a23.nq.gz
    ├── 6d1259639cb6896891aedd4d289cb5d07ad38ab3.nq.gz
    ├── 6dc81154e8641ab49318c2fbd286a7494854926e.nq.gz
    ├── 6dfd4b8f53fc828eb5f7f3a0dbb620e0d04de81c.nq.gz
    ├── 6ed2b77ba061926726fb19a661cd51d6fb727174.nq.gz
    ├── 6f55515ef25eac846dbca77445021d0b6d88c6b5.nq.gz
    ├── 6f67a41d337f4cb0d557ef3ce43c6f8c4d5cb1c9.nq.gz
    ├── 6ff35129dec5b94796b0850195923e21512ef991.nq.gz
    ├── 70000ac732658dc077cc90964e79497c91cfdef3.nq.gz
    ├── 70a10813c7dc2c89c12dd0348baac5fcdec7219e.nq.gz
    ├── 71465c7b6d16af325af50574cd3fbfbde763cce1.nq.gz
    └── 719a94d21db1356534294c760962683b41d8c7af.nq.gz

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

[run-llama/ParseBench](https://github.com/run-llama/ParseBench)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
