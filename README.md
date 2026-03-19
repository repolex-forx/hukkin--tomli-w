# Repolex Knowledge Graph of hukkin/tomli-w

RDF knowledge graph data for [hukkin/tomli-w](https://github.com/hukkin/tomli-w), parsed by [repolex](https://repolex.ai).

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
lexq download hukkin/tomli-w
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 1210bb6f5708a4dc084cc3deb4a3a3e3939f4d6d.nq.gz
│   │   ├── 179105660c367874818f2cdd1e06ed98eea668f1.nq.gz
│   │   ├── 1796378726fd0fbae219eeabc724bc1c294ea8a1.nq.gz
│   │   ├── 19099125f32e7c491603e393263754262b356956.nq.gz
│   │   ├── 22874ff44581f34810e6f19fb6f682ca39fe0fce.nq.gz
│   │   ├── a8f80172ba16fe694e37f6e07e6352ecee384c58.nq.gz
│   │   ├── caa5cc2be87ba50a3396619b0eb4d555e4861c2f.nq.gz
│   │   ├── f0dcd3fa69e988f541d617ced799e9ac27ff649c.nq.gz
│   │   └── f6ba33ea19cf1473fe5426fd5850875b2e23f57a.nq.gz
│   ├── dataflow
│   │   ├── 1210bb6f5708a4dc084cc3deb4a3a3e3939f4d6d.nq.gz
│   │   ├── 179105660c367874818f2cdd1e06ed98eea668f1.nq.gz
│   │   ├── 1796378726fd0fbae219eeabc724bc1c294ea8a1.nq.gz
│   │   ├── 19099125f32e7c491603e393263754262b356956.nq.gz
│   │   ├── 22874ff44581f34810e6f19fb6f682ca39fe0fce.nq.gz
│   │   ├── a8f80172ba16fe694e37f6e07e6352ecee384c58.nq.gz
│   │   ├── caa5cc2be87ba50a3396619b0eb4d555e4861c2f.nq.gz
│   │   ├── f0dcd3fa69e988f541d617ced799e9ac27ff649c.nq.gz
│   │   └── f6ba33ea19cf1473fe5426fd5850875b2e23f57a.nq.gz
│   ├── lsp
│   │   ├── 1210bb6f5708a4dc084cc3deb4a3a3e3939f4d6d.nq.gz
│   │   ├── 179105660c367874818f2cdd1e06ed98eea668f1.nq.gz
│   │   ├── 1796378726fd0fbae219eeabc724bc1c294ea8a1.nq.gz
│   │   ├── 19099125f32e7c491603e393263754262b356956.nq.gz
│   │   ├── 22874ff44581f34810e6f19fb6f682ca39fe0fce.nq.gz
│   │   ├── a8f80172ba16fe694e37f6e07e6352ecee384c58.nq.gz
│   │   ├── caa5cc2be87ba50a3396619b0eb4d555e4861c2f.nq.gz
│   │   ├── f0dcd3fa69e988f541d617ced799e9ac27ff649c.nq.gz
│   │   └── f6ba33ea19cf1473fe5426fd5850875b2e23f57a.nq.gz
│   └── repolex
│       ├── 179105660c367874818f2cdd1e06ed98eea668f1.nq.gz
│       ├── 1796378726fd0fbae219eeabc724bc1c294ea8a1.nq.gz
│       ├── 19099125f32e7c491603e393263754262b356956.nq.gz
│       ├── 22874ff44581f34810e6f19fb6f682ca39fe0fce.nq.gz
│       ├── a8f80172ba16fe694e37f6e07e6352ecee384c58.nq.gz
│       ├── caa5cc2be87ba50a3396619b0eb4d555e4861c2f.nq.gz
│       ├── f0dcd3fa69e988f541d617ced799e9ac27ff649c.nq.gz
│       └── f6ba33ea19cf1473fe5426fd5850875b2e23f57a.nq.gz
└── blob
    ├── 003002442866cba465c5a380098ef1fbde9ebc7c.nq.gz
    ├── 003ab54512e6bf4d9604d1d4240d453a99226e7f.nq.gz
    ├── 00411dd95fa56eadeef3e6e8ad487206fd2803ac.nq.gz
    ├── 004135598c1e645e6d285adfd8590ba24a362ece.nq.gz
    ├── 00c1645beed462cc344d185d9a18cab3cc6037e2.nq.gz
    ├── 01a56a51d99765b05aee08bfd2fa9e18279bcaa9.nq.gz
    ├── 022b096ee44b899339a86ed3f3e49031b0ca4761.nq.gz
    ├── 024db2911c9f8d12209e5f3571e3f7f24ce31acd.nq.gz
    ├── 025b02a177bcef58c18895d7e74a026f62d07df1.nq.gz
    ├── 026c93a8b8d78285d84b954950dfe6a2dd2e8bd3.nq.gz
    ├── 03ceb5a248db9f2353ba78bbd784114dfd0e8185.nq.gz
    ├── 0444cd95bda51e9a575c02db26e2e514bee1f40f.nq.gz
    ├── 04a1336c5aeb2f2dcd248fa9fc841eed14100512.nq.gz
    ├── 0632e9ccde38c0497cee287587b82c79221fe6c8.nq.gz
    ├── 090b474834610cb018e511c9e8aa67ed0a6986fa.nq.gz
    ├── 098e7df265245e8ebf8799ac872617643984666a.nq.gz
    ├── 09f1fcbadb0ff1e84a26934cda32f22972127f7d.nq.gz
    ├── 0a1640dc2b77a0b7c228914416c978f740a43699.nq.gz
    ├── 0a830df73ad45683c33c823ad5bd01254f7d0bfc.nq.gz
    ├── 0af7025e71403caf497e4f6714d3d17dc147bc8a.nq.gz
    ├── 0b463511f8db211485a8c3fafedbb720e3f53c3a.nq.gz
    ├── 0b74664ebaa58e6c268ba1c7221b6369e2c11247.nq.gz
    ├── 0b836f17dc0e130fa9d2147d99d9e9f6e1fa3a1f.nq.gz
    ├── 0d7f10ef5383d24829e85247e3f40ffe12362b29.nq.gz
    ├── 0e388ed39a92838c09c1aeb4857b2829b1d1b54b.nq.gz
    ├── 0f318fc51b37334d2846288022b0f91dbd4ddb2e.nq.gz
    ├── 0f3377cd990e3c696738f8e31a7df415505b8763.nq.gz
    ├── 11aa1fd55e31d514cdedeb1760ef74a573437deb.nq.gz
    ├── 12796e9bca1093dec7451f398e17b50027c59670.nq.gz
    ├── 15b11434ff00960720b8895d4678703e8204f5a0.nq.gz
    ├── 15b43b1d0a8ead6e9763601c00b1bc6da097d568.nq.gz
    ├── 15d3b52fe4b14ba1dcd092931bf452cacf12dd72.nq.gz
    ├── 15e2b84b86494290c93822849937b63281a35743.nq.gz
    ├── 173878300e5d24c586cf6bcab0722c8e11b9e18d.nq.gz
    ├── 177861624d6b531187e0325ac38b097ab34b6fa9.nq.gz
    ├── 1882bc24a1f80acffa478731e10d5da3593c6bfc.nq.gz
    ├── 18bffe10c25d3a22f65028cb051da12bac8186fb.nq.gz
    ├── 19c3210fd939e35c47d9a32faca0c8d3fd732b40.nq.gz
    ├── 1a20ef6d674f68ff80e8352bec579fc08d75a03c.nq.gz
    ├── 1ac9eafcc45ae17e4bb1ff22ce51daac2e4e9d40.nq.gz
    ├── 1ae858707264bf6bb97fd7b8b13622c205c51395.nq.gz
    ├── 1be4a5f8ebe68faa1b5d8b770b7cfbdb993ae4ac.nq.gz
    ├── 1c2f2e5312966d9456309d73265528d151b2a76f.nq.gz
    ├── 1ccdd686e905fa760cfbd184f20c12ac62760ec7.nq.gz
    ├── 1e09a8bf78d684892e3c056cb584722c66c12807.nq.gz
    ├── 1f1f36bff11b9d263e6ca8be6bb1da0ee3a9bc84.nq.gz
    ├── 201fff6acb7be9da5cf956f56c66b591c597d95e.nq.gz
    ├── 206f8a4defaf54d2a72ef292bd75e335ca0cc167.nq.gz
    ├── 211cc25f8bed0c5dee8bd52156b881a891ae68ee.nq.gz
    ├── 21895a2acb4b3a0b390a750740dffc22285a0049.nq.gz
    ├── 21ab5f81c91022af243522c0f4075a1d012f9bff.nq.gz
    ├── 23f908bb5e7427ee36fcd0c74738e8add5909bbf.nq.gz
    ├── 24905929b22f34e063aa7522baf569d2dc6475b8.nq.gz
    ├── 255239237aba179cde7b7cdead015fabd76248da.nq.gz
    ├── 257047eebc019014403fd0a12e9d79e649a4fe48.nq.gz
    ├── 2575f9dd25de919cd1622628ba5e68ccc7b10e4d.nq.gz
    ├── 257864fef9ff36359b772356325234199b9ea5f3.nq.gz
    ├── 25a87ac0ae7a8a990e46b4e3486079efa4744560.nq.gz
    ├── 2624c1d5453ae6a74e4df508cf0286ed4a8bdc40.nq.gz
    ├── 266c9876415d668edb983c3de62f50a4917a6d8e.nq.gz
    ├── 2b37fb3ecde285a2cf0172f9462ff3ae544c3d88.nq.gz
    ├── 2bc61bf1d1a1cb66489d20b90b8052005a3e81f6.nq.gz
    ├── 2dfa897ba4282e82de5a59ba76aafa458c500bbf.nq.gz
    ├── 2efd659b8d8e9ccd57ce64b33c271c23221de4b2.nq.gz
    ├── 3157ac981d37991ea98e6191aaac27b6983d2c60.nq.gz
    ├── 32b6bbe5f6fd1b8e9c9993cf692dec83fc6362ac.nq.gz
    ├── 32cbe7924b480dbf4e2b69117b97f01c899e265f.nq.gz
    ├── 337ad080befbde5ec35a5ff2b41f41cea3ed302e.nq.gz
    ├── 33f2c4fd6cf02ef95585356cd18cff60d7f6d362.nq.gz
    ├── 343353a89e063b6981261d6d80bc26530c9207c5.nq.gz
    ├── 3661f327df785c061b428587d922fdff55c3b86f.nq.gz
    ├── 367e8ec4957ab48531a69abfd5d893456b85fdbd.nq.gz
    ├── 37615338822f4b8cb1e004df71b3d8557532f05c.nq.gz
    ├── 37a4d7508604db1758f86c6063571ff41f8314ad.nq.gz
    ├── 386629ca075bc685183950f57d8be5c2402b48a7.nq.gz
    ├── 388027d5a86fc3be8619b7bcb97146b02e784f71.nq.gz
    ├── 3a2120968c6a2780e0bd0fe15e3342e6f82f331f.nq.gz
    ├── 3a83cc161365ac8cb0f0896334c88905c466a29a.nq.gz
    ├── 3ae8fe0039ffd213bdebde10f485cbbdafcec849.nq.gz
    ├── 3c8f0aa5547d264c3ff0c67d3bea884c3502cbb7.nq.gz
    ├── 3c9046991c2dcb40ffc7912fa28a694fe7209593.nq.gz
    ├── 3d5e8e85a9cbcedcfd2bed7f12bb108aa36b8dbf.nq.gz
    ├── 3dca74cade51620fef199de4b45c5cd1d2232367.nq.gz
    ├── 3fa60d6695574c7b576b6a5700c4d57d0d4ce5cf.nq.gz
    ├── 3ff0f9f0d0096cb1a72b93d9b5b90c09dedc7e0b.nq.gz
    ├── 4013d575f0a98338e2c97f9658fe38d608502798.nq.gz
    ├── 4091028bf6f5c50c4850c55bab80fc4585db44de.nq.gz
    ├── 41a772b78b31eb4cd6c088734fb386b213e22483.nq.gz
    ├── 41bd282d824d725a0d02f652a2b4442f278ab271.nq.gz
    ├── 424a13ac2af1b3987c94d02634c8d1b2e588027e.nq.gz
    ├── 4288d080ca37bba0db8f6adc3980738c1011762d.nq.gz
    ├── 42dcb27530dc268d4269f7f728baf0b63f03260c.nq.gz
    ├── 42e39cde83a34bffae5f45d7f10e9fb051698316.nq.gz
    ├── 4553198225a2277a62ba54d5f1985cbdfe37a97f.nq.gz
    ├── 45822afd7e2c528a85f0db734930afab1a0c4289.nq.gz
    ├── 4588c90964a9c19af478c66e3c196ed3047f8489.nq.gz
    ├── 45e161b1ba87aed3cb6bd3bcb4020d52d42e1418.nq.gz
    ├── 45eb4f71ab58364058fb29fbd66c47cbfe88875d.nq.gz
    ├── 45efcf78274da7e9df118d270307e53cf5eaffbb.nq.gz
    ├── 45f9bb57098769cc0b270ab4ef080de78ea2dd09.nq.gz
    ├── 46062beb8e747400602845f40ad477219286afa6.nq.gz
    ├── 4758ddcade2f49cdd7ab1527b0f84f44a5ece857.nq.gz
    ├── 4aa0752d496337697530172a66780e498240ee1d.nq.gz
    ├── 4aa57e6e46d88f30fac3952df45152ed7238a5a3.nq.gz
    ├── 4b87f4c77c97c844ba21159f207af8bfce6de235.nq.gz
    ├── 4dfbebfaadc40e1b971e849b51483efc7a0c49d4.nq.gz
    ├── 4e2a3607098b3d16ce786335e1af84aa183813ef.nq.gz
    ├── 4f307e2859a1d8f7eb6ab4a05063de95ccd0f4fe.nq.gz
    ├── 5131b1e7d73fe41326782583b45d30af6c10e250.nq.gz
    ├── 51894ce10027d0903f8f50eccfd822042b98c5a3.nq.gz
    ├── 52fd1e89c11e7264df2e0776c161add5f4ad7d63.nq.gz
    ├── 532356f49b43ea20653b85bf60fed32cb6f27d48.nq.gz
    ├── 5413ac9c6bfe69885b619b94ccde98a5934e62f9.nq.gz
    ├── 54b023fd31ab710f8106f868d0bf88d0ec4addb5.nq.gz
    ├── 54f6470761d3135903b7758cb7dc308f880e8beb.nq.gz
    ├── 55809d62846b8de957d74547f70526bae67ce393.nq.gz
    ├── 560901c5a43f20751e78d665433bdd1d03f64aeb.nq.gz
    ├── 56e52cc990a13c0f101ea9840ed723b324683268.nq.gz
    ├── 573e0a85aa6560aaff729587053bdd1c483f65f9.nq.gz
    ├── 57ed4c6cd2aad4399d3b40010ccffc057eec06a6.nq.gz
    ├── 58c08c91bad0df9d188b4a5822b3fe5be573d663.nq.gz
    ├── 58c93ddd4df2e437d08bf1532ce36dacb79d10ac.nq.gz
    ├── 58f215bfb86be6d99cc1c2ff57d615eff37c54a6.nq.gz
    ├── 5aea8eeaa10762041a055e3b6bfd8284d7797c00.nq.gz
    ├── 5bfa47f1b1f89a354d877f52ab11d4956ab18d57.nq.gz
    ├── 5cc4bfea5d801f5553739301eb92f2452ee93e81.nq.gz
    ├── 5d6cc0edccad834be19df0a9b2a5778e96e1fd51.nq.gz
    ├── 5f023229486b9e4fb1cbf028d8ee0965cdf14b09.nq.gz
    ├── 5f5f16f5fde5ba73b4a4918a916009330ca1928a.nq.gz
    ├── 5f5f6168f555b1d7a729d356f479f996991da4dd.nq.gz
    ├── 5fa98882cab55bd133887b4dea2b7ebd411c05b7.nq.gz
    ├── 5fd87466dff05ebe69f6488aeef45951678aabd2.nq.gz
    ├── 61b0f387ff2bf082b7e5cfd73c9ce6da1ec39ebd.nq.gz
    ├── 61ff8d876a5dddd3865834c202b07271a710f454.nq.gz
    ├── 655c40e27ed44db90348b1d1e649f2a56aca5f3e.nq.gz
    ├── 656628a093aebc11b24f766af7100ba1305ec165.nq.gz
    ├── 65c30fb8325c3205b6094c0d00ef6e63e5d930c9.nq.gz
    ├── 65fcddf96a491ec7a9d43b115c0e639fcabb976e.nq.gz
    ├── 66189367fe9eb53de353a250f70431404b4d0349.nq.gz
    ├── 6670e5dd990ba5e20452fa0ff8315623d445ec50.nq.gz
    ├── 67652cb5d53b38c906d76e3c97cb4bb56a65b973.nq.gz
    ├── 6929c435ee1dd953deac5791456f98dff18bf6ec.nq.gz
    ├── 693b410e44836ba95bcc4efac3919e6e308b9eab.nq.gz
    ├── 6b10d70a31fb478364d08ae50d83a19433af66f6.nq.gz
    ├── 6b458e1e8b96bc606eb3f8d49ee5df622d8e37ed.nq.gz
    ├── 6b4884c2c69a07a52cbbdbce04d6148f1aba6878.nq.gz
    ├── 6be8b5153794c4754f2e2275bc6acf3fd81cc8ff.nq.gz
    ├── 6e3e62c1610f586902bcb5c859f0f9879421dfb8.nq.gz
    ├── 6f2304c1767fbe7c7d828df06d7f2d2101fcedf9.nq.gz
    ├── 705686c94f1b1ebfe86295f63df671e0ad1ae12e.nq.gz
    ├── 7075307841176177e69db71f34ffd3d1e5a5659d.nq.gz
    ├── 70b7fe11c3d12f9342824e8b9e0c2c996123a26d.nq.gz
    ├── 71c4d43260c400d7b56563e227de9062d96b15a7.nq.gz
    ├── 726e1fea3e32d0383e497647939914ecdc17f866.nq.gz
    ├── 72a63f61c178ec7a9c01d57218cde45a40fb5f59.nq.gz
    ├── 73ed68b2c145b5069bdacd6d9499231399f210d1.nq.gz
    ├── 74abe9e161becceab9e3d9a0d7d2bafac78c4c28.nq.gz
    ├── 7632ecf77545c5e5501cb3fc5719df0761104ca2.nq.gz
    ├── 7666b87360d9e57addf100992dbd324969f217de.nq.gz
    ├── 78bb2dc3a162cc4e3df30c94f447c4d1e783e0ab.nq.gz
    ├── 78e7e72927950582936638534f49a8c6da87b225.nq.gz
    ├── 78f7ebdf432417e9c7e65c5704cc2d95bf5a2257.nq.gz
    ├── 791962c55cd97cd1510d090568519a67396a6f96.nq.gz
    ├── 7ceae346a762405fdc00395869135ec3557bd392.nq.gz
    └── 7e6396367cad25f05123a8f13ccac3a49b0f51be.nq.gz

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

[hukkin/tomli-w](https://github.com/hukkin/tomli-w)

---
*Parsed on 2026-03-19 by [repolex](https://repolex.ai)*
