# Repolex Knowledge Graph of nltk/nltk

RDF knowledge graph data for [nltk/nltk](https://github.com/nltk/nltk), parsed by [repolex](https://repolex.ai).

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
rlex download nltk/nltk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 05a0ea399697a3531bffc22a3d03edc3d3b6afec
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 05a0ea399697a3531bffc22a3d03edc3d3b6afec
│           └── chunk-001.nq.gz
└── blob
    ├── 01098e671f303132490bb35fb0234b6e1e2a37d2.nq.gz
    ├── 017a393dc763c0aefb0c9563d6f66cefe81cf36c.nq.gz
    ├── 0180477821f92e1516918038cb025afe8633d56b.nq.gz
    ├── 01d55e607f24e4a3e962f3db264d87e8052e9fd6.nq.gz
    ├── 024caa38a12ddfb04fb9991aae1b490bc920347e.nq.gz
    ├── 028791405a6d9cbf5e93338f57a50ad8b22162f5.nq.gz
    ├── 032ad86cbef687a3b6b6a956880c26506e98d26f.nq.gz
    ├── 03967e0e7381100e699268ce0254a47e176db51e.nq.gz
    ├── 04bde7238666d17a7a747dad1821537ce13a870a.nq.gz
    ├── 056bd73b1e85dcf26b230b3bf17f5c0f358c34ef.nq.gz
    ├── 05aea3493bc3c38052d201943c146349bfaa4f3b.nq.gz
    ├── 0869bf663ffeda90ea2698a0a2f4e047bcc85aaa.nq.gz
    ├── 09d992b9b2ff9bf3a3e9c1fec989e5e9e46b1286.nq.gz
    ├── 0a0b85ad4733ef0ee9d264c0ef18e04afe3dc170.nq.gz
    ├── 0aa16103d6dd3c8e7f7c196b3c9e5653cac11287.nq.gz
    ├── 0b7495faa6416c7e7a165548cf33a0e797d79ba9.nq.gz
    ├── 0dc66ab77f9f1ce64bee5be980e3a25bce142ba8.nq.gz
    ├── 0f6c39a1f255b0d1c4180f55d1e081b3789df429.nq.gz
    ├── 0fd219d8a0657ae910f60bc0255fe068bc0ea65c.nq.gz
    ├── 0ff5edcc6e8ee606e356548b1c7f1baf22486b03.nq.gz
    ├── 1032d7c1a538ee1d415af03019e2de8c0516986d.nq.gz
    ├── 106115fff6a326c1d8da783406f16eb5468b8e61.nq.gz
    ├── 1108bdc15dbaa2b4a4ebae06528b53cb6db7f3e9.nq.gz
    ├── 1289fb0d407e4a1d922c4394f0a1119edb1a577d.nq.gz
    ├── 12ba3ca25a7d0526f2f6e13a332c69d780ab1224.nq.gz
    ├── 13a17f0309fb2fdb89d46aa85f73cca256230534.nq.gz
    ├── 14359f25cf41849deb262568f466fb651d9f18ad.nq.gz
    ├── 147be06c73845c5032ada78cc5724e8679ba0d96.nq.gz
    ├── 15149aa3056f8013b2e6e198061b22badd44b30c.nq.gz
    ├── 1592184f40e300c0c27c083b17c446abd9dfe9d1.nq.gz
    ├── 1626160de154c96499cf04c9a088a268b3f033bb.nq.gz
    ├── 176a458f94e0ea5272ce67c36bf30b6be9caf623.nq.gz
    ├── 1810a4243e008a8c0c3bcf5b3e6a07e821db27ee.nq.gz
    ├── 1825d850b9e8a48a61ce6051f75b1bad1c018511.nq.gz
    ├── 1886d88e30fe2639a7ef5627404ddaca0f970d6e.nq.gz
    ├── 188d6d22be9d107e9a95126895f0819992a8189e.nq.gz
    ├── 18e5bb5eb55ef23cfe098750e01d2ed37c427dd5.nq.gz
    ├── 18e9779b0b14c1e3ef783340f72259ee291bbe21.nq.gz
    ├── 1945cfbfb7c8eefe10498449c32a39236a646d3b.nq.gz
    ├── 1987d5f90385d36dbfed731ee60df9f6a34dab92.nq.gz
    ├── 1a1fdc98067802e009033e9d13be105800720bb7.nq.gz
    ├── 1ae2c3cacf7196c812f05081ac412f32afa3d42f.nq.gz
    ├── 1af72560ddceb6d0817f1d77a93244c5eadfa381.nq.gz
    ├── 1b8c9aee90f0b842e4d235649c1f61d0a3c7bfd2.nq.gz
    ├── 1b9367f4270ade64f69d06c9b41d98448b4b221d.nq.gz
    ├── 1bd98b7c1b715bbd9e523f332d2df2e722b49485.nq.gz
    ├── 1d0ece1dd056194b6d7e36647eb9864489b729e7.nq.gz
    ├── 1d23a2dba2659f855cb3aa0807c57d6b862d9150.nq.gz
    ├── 1d771bc99a60868edd17650ffe63f0eba030deaa.nq.gz
    ├── 1d946cc7b71a37fd443a933ec5ce7f640a9a5b47.nq.gz
    ├── 1e3a65cea5d9705d48d45de01721812ee3435d9c.nq.gz
    ├── 1f1187b6780eef77b54965c609a90e9b9eeedd18.nq.gz
    ├── 203b44b1f3d49475b835a7b1e5405efa90b2fefd.nq.gz
    ├── 213367300bc247baa4af68a75f14f815c45e4077.nq.gz
    ├── 219d85386db23cb0aed4438024aa398ae10a59fc.nq.gz
    ├── 21c6002e9b00923a3d2124d96335abee44680c87.nq.gz
    ├── 21ea509a8cf5d0cb3b834c1a83b9bebdfbc0279f.nq.gz
    ├── 220d66313f1e0c8ad5b572ff25056e3d3339e045.nq.gz
    ├── 228d9c0fa85454787caa7dca725d5466532de3ac.nq.gz
    ├── 23115bfac4bb7f661551f192d9e0ec6ce5fc699f.nq.gz
    ├── 2370594df8557172e3f84ed42883395bb08535ae.nq.gz
    ├── 239d0182a92ba0c3c198c976767935ce64a35723.nq.gz
    ├── 241f0a48110dd2959ce7e3b0329f1d24ec5628fe.nq.gz
    ├── 246078e65aa7fbc64a302221f4651977a1905cd5.nq.gz
    ├── 24973110ab63425644a3d67eca9ef5971f9def0a.nq.gz
    ├── 251c97425de8de0ef7641d3d9026cbd4c0c13925.nq.gz
    ├── 2568111bc8aac669317557d816aea14a1c6bdc9d.nq.gz
    ├── 25b3eb8e1757ffa870bb9d50c106b814c30d1899.nq.gz
    ├── 2688081abcc4ad188b8f0b6b2514bee785b29fd5.nq.gz
    ├── 27e1c3714f06f7a723f5d15ebda9cd6bba01a62a.nq.gz
    ├── 281fcbc4b6ee9f8b1cf4698ccf11f9ad93867a3e.nq.gz
    ├── 285fc27e40afe827ec6b392c92e938ef601d9eb2.nq.gz
    ├── 28a7405ff482211f2006dcb23035a4b6da446212.nq.gz
    ├── 28a7bbd35cb0c1c9a91b165835675f8136f41d6e.nq.gz
    ├── 2933793a1fabdbc9e9f7c21c5d6feb6aec80bac5.nq.gz
    ├── 2a03a995c0f4cac3933cecb25ef9b805152fd25e.nq.gz
    ├── 2a51d4f97147337472072df316cf1e5f9466309f.nq.gz
    ├── 2a59ce07c03a24f36e77174de1dc6b6833055d27.nq.gz
    ├── 2a87779dd46567162dbc0ca509d65fcd798e5923.nq.gz
    ├── 2ace4b911cba79682430ff2507f30740fb8d3cfa.nq.gz
    ├── 2b3574ffe0227876e32d45fb65309de76d47b2cf.nq.gz
    ├── 2b930c26ba0b7daa4574b4306be17c70726e5181.nq.gz
    ├── 2bf7b9f8d39439179b21fe059eae325b5ca17a6e.nq.gz
    ├── 2bf7d9a7f84057579ab2309b34f186a78511d906.nq.gz
    ├── 2c19b1c211b31a4998c4af3051bea11d2a2bb8e5.nq.gz
    ├── 2c2efa8aedfe8bab1f570df00323cc31ce621777.nq.gz
    ├── 2c77ed7d59d68a3ac42221a4ef922fd8b1a5090f.nq.gz
    ├── 2ccd4078217656a12fded4627b6ca00df571dac5.nq.gz
    ├── 2d4594bec1571ef21aa91a43d40a32071baa5ea0.nq.gz
    ├── 2d559d7b03e4b42a87d9cff94b3004d7ecd6df66.nq.gz
    ├── 2d58f295c868af9c25f92b62000e0656aa72ded4.nq.gz
    ├── 2da751f455141386a32e7e24c9ded6e84e1700d8.nq.gz
    ├── 2e05cdd0421d78ff4b5b4d768ef24346309161ea.nq.gz
    ├── 2e4c8675057c9ee0e112531baadc0409592a73ad.nq.gz
    ├── 2eb8b383cee1b4c4ddd0484919bea13400a1ba88.nq.gz
    ├── 2ed3c83a89c5dc6cf43002ddb9c6d70faeee4bf4.nq.gz
    ├── 2f73f33aeeb7d3491ce636943450b1e39fce3013.nq.gz
    ├── 2f9146ab4e0572d50a36a8e7ecdbdf2df5ad821b.nq.gz
    ├── 2fec251fdd4a6ff23d462110c0f67f74c9aabde4.nq.gz
    ├── 3022ebdbe40937f9ac8bc1b2f57360d3cc9d6c59.nq.gz
    ├── 304a3139b6f9b68cc5d380fc7ff4a4bb4ff3752f.nq.gz
    ├── 31143deaf8a32c351722cd6aba2a3f9535971b86.nq.gz
    ├── 3190e1c6a03312e8b4bf91dac9bbc78cac21f970.nq.gz
    ├── 31db09a2d53a15e808e59c5ab456ac5a4a2be1f1.nq.gz
    ├── 324b870144ac22efd1cc669372d335dc2c39e4ee.nq.gz
    ├── 325441dec042251b5c21b6446fb46b075f8ff649.nq.gz
    ├── 338b8fd131b4d7598c17b503ade8d1c878997ce6.nq.gz
    ├── 34064284495e1a65e71ac623865083769462cea0.nq.gz
    ├── 3596887e137f2f3dbf9f133b5b2f4d07e4e0598b.nq.gz
    ├── 364deb60a0444956d6467a93f4f65e43235c7a84.nq.gz
    ├── 36dca02aa964605e9802dd37a8cbea875d6d72a0.nq.gz
    ├── 3790d9b3bae400bc13a1e16257c1563f74de2102.nq.gz
    ├── 37af2ed6dc0c982349e45d0c6d4187fd538c996f.nq.gz
    ├── 386c2d27cdb005a40ec0c7a1afc913decb221f3d.nq.gz
    ├── 387fc8f4b6c13376830685be31c281f1bd6af534.nq.gz
    ├── 38f22ce6811b760b5b1b29b0c36856290d4884d4.nq.gz
    ├── 39076cb5d7a3d208d0cd135baf97b514aa6f6f09.nq.gz
    ├── 3a04d54b65f841dab66b893ddeb78055ee38274a.nq.gz
    ├── 3a04dd9e8a3840b2cbf3dca72ce563d40285b6be.nq.gz
    ├── 3a2fecf8d7573c2827d4905bb356e7871aeafd97.nq.gz
    ├── 3aff971990d9ece28af96878b4916ee69956845b.nq.gz
    ├── 3b3dd066742da5d9744f8985b83a61fbd0577a51.nq.gz
    ├── 3b43474856ff537a751cf4efed38feabcb814191.nq.gz
    ├── 3b9bef970f570de87e714d2349af72ea12f406da.nq.gz
    ├── 3bbde91c40845603418e6e6a2d550ae2cf1b03af.nq.gz
    ├── 3c0a90b33b214ba1fc58a4a33c3bccc12a61ce94.nq.gz
    ├── 3ce56a876b3c7f56633ddfeb251d7f237fc4d6f8.nq.gz
    ├── 3e640420240e7c3c31cd69608b7bf4177e6bdcd4.nq.gz
    ├── 3fafbf2b386f13c0bd2ca447b58e35966ea8525f.nq.gz
    ├── 40254ec8a5927ba0deebf6d7ccc835486d30956e.nq.gz
    ├── 407f1d3022a947908dafbd2039a22f657a97b584.nq.gz
    ├── 40adc03e876462128318820ec9cdda27ff90aeb4.nq.gz
    ├── 4127f7127c2517a20306e99cd8b88796e12a2247.nq.gz
    ├── 41e04d1d5a0c418cabd77268f949e3ee90f9ec53.nq.gz
    ├── 4237899316fb39cdf97b4e7b8ee67d9ad6d729d1.nq.gz
    ├── 4256136ea1b2db69279e542f91809d5eaa10f31c.nq.gz
    ├── 44a241cf475af5c0030740f805f8d08b366910d8.nq.gz
    ├── 44d6328d4fa44fe9d60d5a88f344fe4b21fb98c0.nq.gz
    ├── 4517651fbe885d0e0ce6a58bdd51d24758208061.nq.gz
    ├── 4680ff1e8b0a771555a11566adede4f6c8dfdff4.nq.gz
    ├── 474e720507948634af10f6eebc76d681f3a429bf.nq.gz
    ├── 478d50a6d4d4c4c1a343943d174445f871034a66.nq.gz
    ├── 478ea860ee7f044f473497c88abac0167ef1f597.nq.gz
    ├── 47ec95b1f834827de9e404aa8f5db43033203653.nq.gz
    ├── 4821c0b16ed3d52d1b14f5225749084b5eb4a695.nq.gz
    ├── 483949ae277edab6f85a128975e2985f44ec38b2.nq.gz
    ├── 48ba8ad07c50b18db6a2a30bd66112c7c1eca7ef.nq.gz
    ├── 4905e44c6bca2327f09fa794d8ddde8152ac5e06.nq.gz
    ├── 4961fb32ada8ceb5e3657080d16e5ced53bc42cd.nq.gz
    ├── 4a8a3b36049421d853f0a74c0f496a3695e5a349.nq.gz
    ├── 4b6e400bc1bc62e29e1d215438e2e36c52babf3c.nq.gz
    ├── 4bafaba8e93e777a76b0e8c84b8b8b7e7bf276c2.nq.gz
    ├── 4bedac67b343678fe35dfed333d7af296c2833d0.nq.gz
    ├── 4cc9b01a075c542c62a5ed86dd0e84c5841a5dd7.nq.gz
    ├── 4cf737e0ca3512e1febb6f0971c9c88eb0bc6e2b.nq.gz
    ├── 4d25f18c33ac0304314571d23c16c8b1a20f190b.nq.gz
    ├── 4e87d95e9bd93adf37dcf6847c2273d6c5d2dbbd.nq.gz
    ├── 4ea6b8ac9c83e316facfe252ece13d1f3f30d867.nq.gz
    ├── 4f0b5ecdb77be691ec940e97175bfa33293892df.nq.gz
    ├── 508f87e2fbb4444d2c748f647315c0b909edee57.nq.gz
    ├── 509a3ef1a0334fd40ac02aef040dee4c235eb78f.nq.gz
    ├── 50cabc34a76e563dd845e190a9e1d52e5e4a36ae.nq.gz
    ├── 50ce22d5ce72aac34feca5e7db3d1f25265621b3.nq.gz
    ├── 50f431dd016d2102ee3ad1986f7e8ea3e266c7ab.nq.gz
    ├── 51329886a2a58913fdfb64c06410bc245d6a9a9c.nq.gz
    ├── 518aaeb9e26345ec716ecf1970a16e0e620dfa9a.nq.gz
    ├── 520cf6fb1d9a1acd7028dceb7c1e23c4a90f71b7.nq.gz
    ├── 52bced956b2dcc38abdf9521a0479e31a697e89d.nq.gz
    ├── 54e719126f974cd345df4e5ba515071bc4c8af16.nq.gz
    ├── 553193f567738508a37f80938f4dbfc0338cd120.nq.gz
    ├── 5554248e54eda9cad4cd3147bb6e62ee0d0de47a.nq.gz
    ├── 5559ed6992cadbdecf806e75d3d4d1b81d087525.nq.gz
    ├── 55bd09ad63775481d25e6940f5461cc58ef1f290.nq.gz
    ├── 55cb234f611ad63221e65fc3146a64b674116a2b.nq.gz
    ├── 5607748c2d1ecb8159784d16d5d83c5682d732e8.nq.gz
    ├── 56118a43f81d57fe784e9ca442331c4889d92977.nq.gz
    ├── 5626cb5a8aa641b34f50b1a528a0ba00327bba02.nq.gz
    ├── 5679ec4b950fe64775c2cc24067562685a59d24b.nq.gz
    ├── 5821b042515a725e7bbee6a271d9702d0d4ce207.nq.gz
    ├── 58631daf06e40a0e16157f15d3f006cd0899ff56.nq.gz
    ├── 5971f98d542237758328ecc297f69b0205def5b3.nq.gz
    ├── 599d0d6e799be5be619c5336db1973d4cc753c13.nq.gz
    ├── 59c56d088180226f539a4441b0d12ec1eacd6d24.nq.gz
    ├── 5a868c3a7137642482f8326b2688b44d9561dfd5.nq.gz
    ├── 5ae8882daad930c798b33d3fd28f7924ce7f9d5e.nq.gz
    ├── 5bb13a9e11b13cc5cb6520ec1a47b0c093f48f15.nq.gz
    ├── 5beb781cfdddb3e74cb6a0c312f57b6251d73d3d.nq.gz
    ├── 5cbca24a09b0bb2b19e7e2a3be121a19b4fb7a85.nq.gz
    ├── 5e6434daaf0a6d8517c55c2ecb1f81799d75554c.nq.gz
    ├── 5f06a478b7eea0429f8de25932e60a8ac59a984c.nq.gz
    ├── 5f8edbfd6c0538c8f00b831cece34980c096f001.nq.gz
    ├── 5fbf1ad9e1c42b613314caa44e64871e97657434.nq.gz
    ├── 5ff36ecfe10c6398d6bfd3f7f254f5365125bdb1.nq.gz
    ├── 60011b1d758077ea2f8c9e713f11f08ada4ab8da.nq.gz
    ├── 608961dfcae899686f74df414e34210cff452fc0.nq.gz
    ├── 615d89f6088d8b8136694bd367dec4eb11d14c5c.nq.gz
    └── 6185af850232ec33fb28139e4f45259c14d86051.nq.gz

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

[nltk/nltk](https://github.com/nltk/nltk)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
