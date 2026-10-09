# Repolex Knowledge Graph of modelcontextprotocol/inspector

RDF knowledge graph data for [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/inspector
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0d2bc1d91ce177ea8d497ee3efe91bcc59e40a1c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0d2bc1d91ce177ea8d497ee3efe91bcc59e40a1c
│           └── chunk-001.nq.gz
└── blob
    ├── 006b5711ca7cee251eb8eb27e1a7a8d3a6aa286e.nq.gz
    ├── 0089ef98b693228ab6265ec3e0a7cfbace5d97fd.nq.gz
    ├── 00ace5fccd2b96093472698a253e30d7ea4a383b.nq.gz
    ├── 0149d7ea96ae7f73f9c32a84de745b2205981bab.nq.gz
    ├── 01da48db9b37278e6a43155fb3acf2e5be08914a.nq.gz
    ├── 024cd490d7a44a6e13cfaa772239360e32fab795.nq.gz
    ├── 026effe0bb9d51a73e5ac1e6c1c8196867642656.nq.gz
    ├── 03f6b0b4caac19e86ab308c4439b68e9d39e32ef.nq.gz
    ├── 04357ec4865e54c6d54c94453196bca4c8989f8d.nq.gz
    ├── 045523dfc2396a44618756d1634831d31478421c.nq.gz
    ├── 05651a943860988324a8e06307422f9bc0a3b389.nq.gz
    ├── 056e3cb90a9fe0fb6b9cce71144c86c8eb3ff0ee.nq.gz
    ├── 0608328b2323e0f9748f99a446e997d70bc49d39.nq.gz
    ├── 0658aa527ae8fdeb7a7c175572388d9d76470e45.nq.gz
    ├── 06743379e93d669051c34df7136fa5a5b0985212.nq.gz
    ├── 07235c89258fe902b7e3c9df7ec488dc35ec6de3.nq.gz
    ├── 0727cf83f6d8875edbf5cbbec15110971cb6bdfd.nq.gz
    ├── 073779a8677d347bafa5ee59bc2c1f667ff1baa6.nq.gz
    ├── 0738f3328bfad7a6d82db437ac98d9a7c1fa1793.nq.gz
    ├── 077fdc700e45ee526c3137670b04f41b215024af.nq.gz
    ├── 078ec9b3717dc4fbcb53cca820521757929c5b48.nq.gz
    ├── 0888d887f6af91e053f04410d38e69888840fe5b.nq.gz
    ├── 08b46c19d2cdb73a7cf27c49378cf147b1ab81c5.nq.gz
    ├── 09988c1fd0400f28256a17d33307948f04a9202e.nq.gz
    ├── 09ca1a2a78679956ec5f7f0eab1c82c19a15e163.nq.gz
    ├── 0a504105b50c63a17af92f17fee999bdcc4d40d7.nq.gz
    ├── 0aab3c9dab95c553f8d9a1525dfb481f15a0d68b.nq.gz
    ├── 0b8da4a8997cfd002aaf51c12b3e255397a68df9.nq.gz
    ├── 0b9aaa3474b2d7e2db15d2111a103f71977e22bf.nq.gz
    ├── 0c472f8a555927692ba23a383a99b6a9df02f68d.nq.gz
    ├── 0d32d264ef7208c28d0ebfa2ecfb234a2b673459.nq.gz
    ├── 0d37624f22844e28a6b3b01e35170277ac0e68f7.nq.gz
    ├── 0dbe6e4895060fc10e8eb7510e5636025b06c7e5.nq.gz
    ├── 0dc410ecc6b82161680edd0a230ec0e4283e8973.nq.gz
    ├── 0f8f919ae71dc53b0cec28b78551b3c7cde5378e.nq.gz
    ├── 0f9633b177ad7f8ae92f5efa26b878814e7a9aed.nq.gz
    ├── 122aea452bb2acc0dee630e0658274f09d14254e.nq.gz
    ├── 131e374238737006a21a34323cf1ffc4da4c9863.nq.gz
    ├── 13f7bf94f084cacff475031fc416dc93a856e7c4.nq.gz
    ├── 1407dc6334945eda1d629976aa8394fd75e75332.nq.gz
    ├── 145e4424b48b987b8af0e7de8dd510599b9e2a81.nq.gz
    ├── 153874944bbe0a7d94cbcf5c802a0872e3c1ab64.nq.gz
    ├── 1542ab1e8de388a479cc659893b5197471631edf.nq.gz
    ├── 15ea143b2133d6bf0484e47c03a98d8d322fc850.nq.gz
    ├── 160aa2db641767f87b98892effbbbe518d962cde.nq.gz
    ├── 16e932605ed70998c2ca6b62569a0d03456f0028.nq.gz
    ├── 1796811c5123bc4b9a83e2fedc8353ee3c32060e.nq.gz
    ├── 18299b1977238ed168f3dc1717641b6020e56718.nq.gz
    ├── 1849c2ff4ecb41e2fd8950e9ff4ef9e639d87da7.nq.gz
    ├── 187ca849e3e2442deba6815b3b310eb2f9e4255a.nq.gz
    ├── 1920267d3d669c8e1ab20e5a86eeda98e2aa207e.nq.gz
    ├── 19a44293ef0e0102e53acce63e82b966428cbda4.nq.gz
    ├── 1a8e0020bd522bd807fa267ff558c86f38db325f.nq.gz
    ├── 1af189df3115aa27ae834fd2006e91756019c00f.nq.gz
    ├── 1b9b707c66cb5f28659500e952e327e509eee9f4.nq.gz
    ├── 1c07c91b33b7eac28ba86c83aab76956e80b1afb.nq.gz
    ├── 1c5c0f87ba98dc49eda3778eef177b777509cc7c.nq.gz
    ├── 1c84c32503ed58f1296392bdb1fdae8f6e2db87c.nq.gz
    ├── 1d0717f9b7199806b62aaa842ce83002f91d6b51.nq.gz
    ├── 1dd1660e4f799088422f9bcb5c31c84eb48319eb.nq.gz
    ├── 1e7e30db2b6517cdcca9f68b2d885fcde8e67dcb.nq.gz
    ├── 1eeae574580aaccfe6fe7a9129f9fb369db68d82.nq.gz
    ├── 1fa97188b2fd630aee086cd53a308299168848b7.nq.gz
    ├── 1fdaef402d9a58bb61e905d3c8f3ab4dedb4870a.nq.gz
    ├── 1fdb18623b464d96a90526e8b990444e67ce11f4.nq.gz
    ├── 1fddc9eb207e383b495752bd6f83978afee19959.nq.gz
    ├── 1fed79a4ac01ed57d1e3f65bc2dc8e0e1c915f53.nq.gz
    ├── 20b703257967cd0c816971fdb7508261c56bcb2a.nq.gz
    ├── 2109fbf4aabdffed8355a18116182ef0a6eb8c6c.nq.gz
    ├── 213e967736a2898da16b98874fc285faa2a3ce40.nq.gz
    ├── 217e0b5dc5847067644a40819b5228d5420f926b.nq.gz
    ├── 230413327b13e60bd508f784dc291374e0516341.nq.gz
    ├── 231cbb5a9acd3a227e7e6f81cf63c744e88c60aa.nq.gz
    ├── 233d8295aace13a3a70f64ee1be7910114822176.nq.gz
    ├── 235840f0fe019dc242552c4fb076f10074e42cec.nq.gz
    ├── 236551a8750de2a684ac07c84902295157527d44.nq.gz
    ├── 247854679e833afb97f25b72fe868087ce2a320e.nq.gz
    ├── 2590b075853cdb75b0c42da1a3a2666c7b2dda59.nq.gz
    ├── 25d5b1d3a9c687f847507172f57eb8e8db9c3b3a.nq.gz
    ├── 2670ae0fcc04d772573944d69b1a7875b16b560c.nq.gz
    ├── 26d6540de951dfd61977d76582b416652d2e906f.nq.gz
    ├── 26e138b141947251787349c9b7f196e772416fb3.nq.gz
    ├── 2790c295b979953c9a1415cf4192e6a431f41457.nq.gz
    ├── 27a42d61994c36e735339c337965d427be2dfac3.nq.gz
    ├── 28a02ba77fd451b53e87d7b62b4a0fe80eeff5e5.nq.gz
    ├── 28db4f32e13d1645ee73331cfb72438215c78c4d.nq.gz
    ├── 28fecc3b48cde63ca8b6d064dbc986d395b1a4d3.nq.gz
    ├── 29d63df22aa8be4ab004ac709b183ab482b23118.nq.gz
    ├── 29e07b8f235818ade1f46f77f4dd6a67d2db6b39.nq.gz
    ├── 2a6f9f06a8e2fd832fc755e4909b6f47bc6db04b.nq.gz
    ├── 2aeb86063169c867fe62c2b678b13133209b7b71.nq.gz
    ├── 2b5471130bb86697e08a2cf7818cc7d3f6719261.nq.gz
    ├── 2c18f0e4776dbc0103f9256a007c3b712c61648e.nq.gz
    ├── 2c2749935acc0d0436b591295077e16fba64b32f.nq.gz
    ├── 2cae9cd888b609aec85213bf55d3ebd1e13c6589.nq.gz
    ├── 2cbee7f51e048dcbaad59742a5461a0226d3bb8f.nq.gz
    ├── 2d8acb7f05f5716819ef375a66c51a3b08e5346f.nq.gz
    ├── 2e3b405b3523e85b4ced1be8c39755f7538f6ef9.nq.gz
    ├── 2ec2d509982b8307a025846faf8317f2be8ee2a8.nq.gz
    ├── 2ed0b159e186f4f173a6acb1f8e5ee98370ba6fc.nq.gz
    ├── 2f160335e8195af0883167c3e6c0c64329953e4b.nq.gz
    ├── 2f1ba5bf9dd49da245d02baf5884041a5ee63fbe.nq.gz
    ├── 2f8b86afeea42d87aee8f409c30e7f2db16892d9.nq.gz
    ├── 30e09093aca40f02a82b13d19a315ec45b23f12c.nq.gz
    ├── 31537192ae1f17a63febb3725a11a142c63d00b6.nq.gz
    ├── 31e268fdbafffa1dc12f14775cdbd978fc64c64e.nq.gz
    ├── 32bf76b21d4c4312ac2eb08a22a45e021c21ead4.nq.gz
    ├── 32d06bd143e6b5d5a51b976b8d9a03735353e551.nq.gz
    ├── 33a994220e2582ec69bb14de3a3d92c3c9107042.nq.gz
    ├── 33b7f61d7c417bfc3a9e346e59c8fe289d5ba8c9.nq.gz
    ├── 342bf6705f199b50e3daa387245e511d6b86e945.nq.gz
    ├── 34653b7f1eaffadf026a1680e9da52919b23c72c.nq.gz
    ├── 3465eef74e6f8d45f5fc66388e055f22c8a0c08e.nq.gz
    ├── 347773c8a4faaa3732837443c37319077c7f2490.nq.gz
    ├── 34808428cea9d026eb16cf014e6a4230b0568753.nq.gz
    ├── 35053e0379927fbf6d67f89d5e0cf95c70364696.nq.gz
    ├── 35bf7da60b132243776e1a2f0bab1ce52d627467.nq.gz
    ├── 3656172d098659fe842f6bb7f9a70dcb3dcbd2d3.nq.gz
    ├── 367f8cef99ba8d38ac90aa451a77f2f819380569.nq.gz
    ├── 36b293db5ce65860461edeca6c551a0767384c05.nq.gz
    ├── 36d416d5c8fab119d8d734c1a62bd3e1e96c86f4.nq.gz
    ├── 37ebff2bae9eec4180d3a79b5a9d8d014e0da444.nq.gz
    ├── 38294391b6532b071b1901d479e29c309176d980.nq.gz
    ├── 3849e11ea28a7cf4ffad798c3f11c39c87f5b4db.nq.gz
    ├── 399360d724a55abc2b6aa17fa08146f62b84b6b8.nq.gz
    ├── 39d455cd05326cdbe2574c6ff8e5685c5aa5b961.nq.gz
    ├── 3a5574abedca0c2ee6469f45ad8d1e179e231714.nq.gz
    ├── 3b40bab0fb941ecd903e0ed0bf24404b71acc226.nq.gz
    ├── 3b570bc24b3d3dd7d5423ad0992e561de71d523e.nq.gz
    ├── 3b97479277571165e415c6db882b65639c54c507.nq.gz
    ├── 3c2d5c0234d904e67e5e72c0293b058fe1817cba.nq.gz
    ├── 3c93335d06698dc3aa74c819e01c73546806ac46.nq.gz
    ├── 3d4e40eb4a526f31b655e342b10bafe91d2e9651.nq.gz
    ├── 3dd7b2c07ecd4934ad9bfe9b37fc990f87ce024c.nq.gz
    ├── 3dda230dbeeaadd2812b83a1beac08724630b7e7.nq.gz
    ├── 3e83e7edfbdb9dcd18191b963f2ce0c9d1cb98aa.nq.gz
    ├── 3efbc0e5e5e4530ed3cd80043be55f5f02840289.nq.gz
    ├── 4054435216f04bcbbd6a4e2629fe7c2490a769b6.nq.gz
    ├── 4084f3b9e942984dceb3bab1ab36efa350e96b7d.nq.gz
    ├── 4126264f0851279ff65aac9629287b6870bdeabb.nq.gz
    ├── 4186bc2b131580c5c2d4809aa31f33e81875ce8c.nq.gz
    ├── 42331d91e307b83f2e217ce924881ed6ced8e830.nq.gz
    ├── 4253bb29c96dec72dc962ad471961a832f18210f.nq.gz
    ├── 42bc7e363c423369ecfaf2843024fce88a5dc7e8.nq.gz
    ├── 42f8bf35262c8ada0234c766ca50968e2861a417.nq.gz
    ├── 4352d9092e7d9549461fa81e8bee6f535ebf9e9d.nq.gz
    ├── 43c2affdf96ea761bcfcf18670f75c3ab3d302d4.nq.gz
    ├── 445966accf9b163d4ffb4cf0ea0bd32f78513ea9.nq.gz
    ├── 44b5c4099601db54b6c9cd14c118efc6d04a7c82.nq.gz
    ├── 45df1ddc6ea781aa9b2921e5f6c13fab0d1a4145.nq.gz
    ├── 46a19f4a47dd91c1a49596cfd24913e9498662ad.nq.gz
    ├── 46a8a008377dfe5db85741d8715dabaa7bed9446.nq.gz
    ├── 46e7237d0db42b7cc550a0b97fadd850689cc944.nq.gz
    ├── 477d428fd0fd6176db02904fcf6d16b6f6bb1c9c.nq.gz
    ├── 478453bbfb71c066e3d1e19816b35884ae908504.nq.gz
    ├── 484b32f50d48859afbdb9ead25f831d75c781a55.nq.gz
    ├── 48f762d4d99d172419e28f42d3a4ab7b748aa449.nq.gz
    ├── 49322c00335cd6149a25fd4db8501d375dd098fa.nq.gz
    ├── 49bf278c84b996bec205420aaa4a7c5ec950458d.nq.gz
    ├── 49e2c8ec5779b84a5fc97a3a36c4d1aa2370bf3c.nq.gz
    ├── 4a440c8a6beb6eb0284324d1bb0b7d1ba719b942.nq.gz
    ├── 4a554b7af686fde1f1c073ec61673099f64c77b6.nq.gz
    ├── 4ae95d4b812d812bcb40b2571264651f7239966b.nq.gz
    ├── 4b1db1687600c9f1dc6933d6cf0e1cd553758de4.nq.gz
    ├── 4c7043428d8f7d96f264df321dcde009b8d78707.nq.gz
    ├── 4d3d604fc0096cdc873d73cc58e8f0b42b6cbf11.nq.gz
    ├── 4d7c34c151bc8a1126dc48f7c19e69461e5e98f7.nq.gz
    ├── 4dbfc46c37d36be87eec1a269cfe6a8ef18252d3.nq.gz
    ├── 4de2adea3c3894c3fe6499420c5190f9bb71d42c.nq.gz
    ├── 4e5fae1d9826fbad6a82e9181d84b9d5520de86e.nq.gz
    ├── 4f0f6ed3c566631080d4380136fff22f1ea504aa.nq.gz
    ├── 4f1596ef5dd2e306932779efe3d475c79a552487.nq.gz
    ├── 4fb64087a8ebfdbd4b382f0a581019deb30a3ab3.nq.gz
    ├── 50df39a47d0c6741c422f5d26bd8d737fc294fc1.nq.gz
    ├── 510b5e885187541a99ccf99910c88a1465c76f85.nq.gz
    ├── 5110bd1d321e7a98137df432c00ed09a8211a61a.nq.gz
    ├── 514c558e2f6e766ee822c3cec5ebde85c48aa4d3.nq.gz
    ├── 5159b16c1115bbd9cd9a583b62b35e553efcd13c.nq.gz
    ├── 5214a61e691aaddf64657364adebf8de6687ea6b.nq.gz
    ├── 53939e5c4dc622f148831de1ed940842f07a74c8.nq.gz
    ├── 53e5b5c6c03c39de0dcd32a392f0ecabb3f9eaad.nq.gz
    ├── 54331e894735ee06eaa7bfccbe91c2e0d2f9ebd8.nq.gz
    ├── 545ff329bed5080f3e60e8805f32194384b4fd4b.nq.gz
    ├── 570a1fbdde0afd74b3c50b787393946372e360d0.nq.gz
    ├── 587a4648e41d729ff8186b3e5c2f475c480d14d5.nq.gz
    ├── 593e7b1783335c4822b8739ec640b335737ecbd2.nq.gz
    ├── 5a6fcd2fbe3e72e7356834b73c3481c3c433104a.nq.gz
    ├── 5af72c1c6e9ac206185909e3660fa71de883c9ad.nq.gz
    ├── 5b19b0eed8b93d576920c3c8cd2a8cd52ec11f19.nq.gz
    ├── 5bb34c5c76f2c2d745dd83a2042af6ce8eba6a22.nq.gz
    ├── 5c2836cd21473d8b244a8bd8e6f5e321d3eab64b.nq.gz
    ├── 5c2b4cf4490236dc69b9ec7c56e94f9243d435ad.nq.gz
    ├── 5c848244a7c60a0acfd83cf2671a6bd58901d461.nq.gz
    ├── 5cd2ad1fca61219a00fcdba454b71590732721c0.nq.gz
    ├── 5d4addfbd3b6960e04595c67dc37c32cf3ea2710.nq.gz
    ├── 5d664d369b9f23e010e6664649aa28f5ba007a10.nq.gz
    ├── 5d8d9ccd792384abe4005046898050bbf519d23f.nq.gz
    └── 5e7488c6c349dcb8a2f611d6eaa62e99afae85ac.nq.gz

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

[modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
