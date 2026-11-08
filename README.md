# Repolex Knowledge Graph of UKPLab/eacl2026-meta-review-as-dialog

RDF knowledge graph data for [UKPLab/eacl2026-meta-review-as-dialog](https://github.com/UKPLab/eacl2026-meta-review-as-dialog), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/eacl2026-meta-review-as-dialog
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 94e80d92d66279e635f462cc2bc91e3426361529
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 94e80d92d66279e635f462cc2bc91e3426361529
│           └── chunk-001.nq.gz
└── blob
    ├── 004aafefe7171df40b6b34b7f9560b3e06e4947b.nq.gz
    ├── 0254e538440f79278cf74e81bf5c9f5c2e006eb5.nq.gz
    ├── 02625f6915a45afa5fb335159548265a29375279.nq.gz
    ├── 03ebe2a5de9b0af1c6a5cb02e50ec72bf47edd76.nq.gz
    ├── 03f2ef2c59bbe6efa549538a3fb801b05707babf.nq.gz
    ├── 03febee0ee2740f9ed2ed583b2f6048a686265ba.nq.gz
    ├── 045a62f59bd1e9a81f700d9561a223ce50d80b29.nq.gz
    ├── 045e8feff48540edd430381a4f883fc00de93f51.nq.gz
    ├── 054fb4f451694fedbbd9fdab6a34e1aeb354e531.nq.gz
    ├── 05ad469523a49f091b198bf5c030393944ce8ae9.nq.gz
    ├── 063bb4ee095b0d119abc9adaeb0aba0a9dd7e765.nq.gz
    ├── 07b2eadb31a0dd0033eb9c51abb8f2145863e604.nq.gz
    ├── 09401d6ba68e20b677ed78b4ac5e9ed02f8ed794.nq.gz
    ├── 0a8497e07b8d17b963429eea492c89ea04588996.nq.gz
    ├── 0b6e4a369ab3c8bfa76a871fba28239b09b09f68.nq.gz
    ├── 0bae955403c26dfc9582bd253289f4c0111723ba.nq.gz
    ├── 0bcd7132d0e9a6c7a139e21e2dd3fcf73b4a7eac.nq.gz
    ├── 0bd4beed504b5ab476bf749a153c2f1717f9c9c1.nq.gz
    ├── 0c2de860a03ecf686de7542032f393aab5ba0a03.nq.gz
    ├── 0ce8faa45defaa311c57abc688e426b038932ef4.nq.gz
    ├── 0d188b972e3b8e3e82ca08ef086fe3e18aace0f6.nq.gz
    ├── 0d1aa49d8963d396f6773aacb5faff5e1a5c1f49.nq.gz
    ├── 0d384fc290feed084385f4adec3a05f7b6375b3c.nq.gz
    ├── 0d3fa206864f1244682fcbb8b9a08cc612838ee8.nq.gz
    ├── 0dd23534208d97ab64266a59550bf7eaa9b503b0.nq.gz
    ├── 0ed7f129aad734eec3d656b0e96565e86880bdd7.nq.gz
    ├── 0f1a319af492335bf7c25ace2edd1d6da2f95c50.nq.gz
    ├── 0f5f48e4572d147c27e48b25fc509d871e485e31.nq.gz
    ├── 10db091e615a92500c97ae898fcc9e523a633aa2.nq.gz
    ├── 118b7dd22159a4586bd1ccd5909c024cd0c144f8.nq.gz
    ├── 11a0286c94c6755216803226ff892c8d8122c77a.nq.gz
    ├── 1224cfc5030bedeff21e8f894bce3fc27cf3657b.nq.gz
    ├── 1292f6ee958d11e33e434be5ec5677d9ff986e2d.nq.gz
    ├── 12e66f9fe96edb262337d5d76f373e3fe61a34b5.nq.gz
    ├── 13dbbd67fe90b58c849877043b3d01ceab706541.nq.gz
    ├── 143684fc6f4041f286a82187a6d4cc459c2fa39f.nq.gz
    ├── 148a6baaa334fce656cad9c467e608a272ec3163.nq.gz
    ├── 14e3365c92f917d7185646cdaab518765d2557c4.nq.gz
    ├── 1536b21d925e0d3943063dbc869757eab9bad53a.nq.gz
    ├── 157a87500f1614bb3711844e8527ee41fe438bea.nq.gz
    ├── 157eae4d354dbbd9566c80d8217b95b0e3022620.nq.gz
    ├── 15a5f6d87ac2d9316394e513034cf03b38c14660.nq.gz
    ├── 15da904cfa4fc62184de9a9bd09ab1ecfd547a0e.nq.gz
    ├── 16d61f18f27d5f018f3a0d963b027636c250ac57.nq.gz
    ├── 16d9ecc78363340e168f5095d7a938b003d5d379.nq.gz
    ├── 1814b496daea7b697b26c0d83fd8f5169f3e1ae4.nq.gz
    ├── 18e11b9e91e8e2c3520a19b53134a5a930a63ab6.nq.gz
    ├── 1ac9dd1d804e8ea933db0eb3277f28d3342832cf.nq.gz
    ├── 1aca51c8a7d7c64627c2e46232392e43f8427a85.nq.gz
    ├── 1b1b72dfba710eec204b9183150fd8e395c3a178.nq.gz
    ├── 1b51a76c52b1ad2038aac9784050403366619e3d.nq.gz
    ├── 1c17ec9cb74fd1bb348a8f9814f603803a9edfa5.nq.gz
    ├── 1c61f0b62b0b463d333cacec9c63b2a1c64787a4.nq.gz
    ├── 1e362960cce1782558aefb153ff815be2af9d373.nq.gz
    ├── 1ebdfa301892feeaccbc613c44a582b04c3cbb3d.nq.gz
    ├── 1f903b14a00e4bc5a0063027a5404b7e24366b08.nq.gz
    ├── 1ff408673c2a2ca6dd0b3d44f5e94352f294de7f.nq.gz
    ├── 2011820a7d9d02d2536368063c44fdeb310d8e4b.nq.gz
    ├── 210ab6a000377ad867b186915a0e319c2cd26510.nq.gz
    ├── 21866e9d66cefc5928924be68eaf633d77be0162.nq.gz
    ├── 21ae094bb2bb8876d9fb55305606b0bbac4cfb09.nq.gz
    ├── 230622af7e10ddab1914cef408229f55d397c111.nq.gz
    ├── 23225f9ca3ca551b12bdbb6e7377ac6420731258.nq.gz
    ├── 233524c78bc06c537271f7c46ca3d119a279b539.nq.gz
    ├── 233decef635a5b3dc435f38392ae65223197f51b.nq.gz
    ├── 23c72cfb8b3ff9c5044267deca34f247800ab4ab.nq.gz
    ├── 23dd50d80fa89d61a15c1786d5790eee034fdc5e.nq.gz
    ├── 25376aff7419aa96271402f0df8c240122f56b3c.nq.gz
    ├── 25c2cc4c4980e9b0c2990339f8db990dbf63c06e.nq.gz
    ├── 2601d2d34c141d24563b290537bae57b32b3e8b4.nq.gz
    ├── 287993a6ec48ee1ae4a8b80990030b756333c23b.nq.gz
    ├── 2a77506b2e95eb4597519f83328bcce2c434ce8b.nq.gz
    ├── 2b3b51201357698c9f733895fe99930935172d39.nq.gz
    ├── 2b4a3d68a4c57d8f14f3aba3c10dbfeb8e991843.nq.gz
    ├── 2c1471aa1f912a772a06d8fb9c84f537b7f6608b.nq.gz
    ├── 2c8d7582b451ac3a3d222ed2d6737806208965eb.nq.gz
    ├── 2c93ecdb540c09f93f3ddc4b950903e78b62b206.nq.gz
    ├── 2d0fdb82edab850a5e0f3a700802f8c95d66d7cd.nq.gz
    ├── 2e14a4f7442adce4a5c547a9a9576063ba6d781e.nq.gz
    ├── 2e71801eabec1ca63ad82ba478a0a3ae15c44a92.nq.gz
    ├── 2e9f1805f20d6233e8ec05630621d9b3bb0d05af.nq.gz
    ├── 2ec5376fef791dca2b56d8262ae416c23c77f453.nq.gz
    ├── 2f24d0001f331b7329ed4f2c93bbecd6c390aaf8.nq.gz
    ├── 2f79e11f4422033c438d002ef0ef3c6be8daefae.nq.gz
    ├── 305454cc9bbb5a1094907b85017cf96f900dc4e5.nq.gz
    ├── 30f9f8aaf69b227deb822f4002abeda4a58611cf.nq.gz
    ├── 3115be5c0db19b261180ac33ebd079ad7b013018.nq.gz
    ├── 322c083ea24584260a45252101e6b3a704df2203.nq.gz
    ├── 32cf628e7501fb79cffcc20912a2ad903efaa87d.nq.gz
    ├── 336ac61466254b2bda6938d504ba5ac1e9b899e4.nq.gz
    ├── 33ddd600b02e00855dfdd7ca8909461ef4d3d8ca.nq.gz
    ├── 340679459d55d925d1772b0c80b532e656f25ed6.nq.gz
    ├── 343f031fff44f843175e7d89bdb28ef4fb39740c.nq.gz
    ├── 346cbdb4fb89622073e0b15fbbfb021136d5b538.nq.gz
    ├── 3488c9d408fb9f30005509d67190ee02b36d13d8.nq.gz
    ├── 34f742f5e1d93e97763a7dff78526ed6b7c6482d.nq.gz
    ├── 34fd4c97704258278908b909a401f16653018ec8.nq.gz
    ├── 351005fbeafe5be94f9784f700fa928be97fa817.nq.gz
    ├── 351b5b89f35cbaa3d6e1c2fc0001d505629fcc0f.nq.gz
    ├── 35577555e2f5694ea9e197fafeccfd253b2b5617.nq.gz
    ├── 35c2602c7be6c6f6be60447baeb01842b980b75d.nq.gz
    ├── 35dbba67e34f6ef3a45f5594c004bb1491fe30f1.nq.gz
    ├── 36151c3db60e93608e52e2a4b90689eceae7f484.nq.gz
    ├── 36a0787a8b85a8563f474e6654f6336feb00c762.nq.gz
    ├── 36bd27dac4c8b81dd3553ba532b2c0b68e05659c.nq.gz
    ├── 3874ad8022a3afaaa8e11a820ae15af25a53bc36.nq.gz
    ├── 39a0fcc8a2dbdbb899e1cfc123a6173a91292875.nq.gz
    ├── 3aa68eadcb701f979f2ff22775f2aeb05b160925.nq.gz
    ├── 3ac143d355a498e4764a18e233f3100f4608c041.nq.gz
    ├── 3af9096ec44163f3592547915abc1ecd0fa5461a.nq.gz
    ├── 3b84a0ade7fcc8c994e71f0fb86348262209a96e.nq.gz
    ├── 3bbe88f52b69531f0aba81aa1f494d323c8473b4.nq.gz
    ├── 3c2abcd407653d55952e1764a2f112626ee2f7f1.nq.gz
    ├── 3c6eb021b22ca7e2496431606fd4c1dac74b060a.nq.gz
    ├── 3cb75f28d155998385d9da830444413f8fb1d76c.nq.gz
    ├── 3cd03b11b8aa2addaa149b0d037b7d1147defaea.nq.gz
    ├── 3cec24ae7488e3703daf517e82a1fa732181f047.nq.gz
    ├── 3d2c6508ba48cd7283a28e5d140b0e85e53fa39a.nq.gz
    ├── 3dc2953065e910cfc26c70b96bd08c58b132dc40.nq.gz
    ├── 3e3d1e82371203648f692a2299ecda1eac6cc6b1.nq.gz
    ├── 3ec81e7228f6ba13105260f65204fe5acddf7375.nq.gz
    ├── 3edae7b8b96e8dadfab83442bff38da34f904382.nq.gz
    ├── 3ee746eeefd87f485c489685e10f2ce60276e053.nq.gz
    ├── 3f360630b3efaf189ed2497acc5751596e2404a0.nq.gz
    ├── 402340e04ffe5144d0219941644ccc900e34dff3.nq.gz
    ├── 40523d898e580bf05ae8341f24573e9a6064b185.nq.gz
    ├── 4233817251c36648fa6a1c69dec3988c7be65c5d.nq.gz
    ├── 426296c72c925c792f84ed4b135713069e554061.nq.gz
    ├── 42c6cb6774b40ce3c4e8b520cfb4170ec0517ad6.nq.gz
    ├── 4454243282d7eaba541343b229287638a18b2237.nq.gz
    ├── 44565c99d2c18a4904fb8d82d98e8415210a74f5.nq.gz
    ├── 44ba3720976c1d6851ae98a52bf94b284439010d.nq.gz
    ├── 44eb18159cc36bb2e925b9ed2fb10f41b3cdfe3b.nq.gz
    ├── 4775f83c2508474242087c6a5ac641a173d8806e.nq.gz
    ├── 47e662e9a2685a8f0d90adb82abe6cb28e6fe0f2.nq.gz
    ├── 484fd38d30c86a93096132d6faf1aaaa7e887ec7.nq.gz
    ├── 486a17ad487de2e52bd9bbafd6fccf8aabae0e3f.nq.gz
    ├── 487acc4667a72baceac19c9c768c41c6a84410ef.nq.gz
    ├── 4938313ab235b717743977900cc2d4c543ef9d4f.nq.gz
    ├── 4ca3a71fbea9ea31d0a04f8096007ccc23c48325.nq.gz
    ├── 4cef0baaf43900e49b21d8f1b2f5bc92a79aa34a.nq.gz
    ├── 4d13c29d1218b97322e6d7fd6f6c6056bb8e55b1.nq.gz
    ├── 4d5732618187c2e3e775cf85077eb31decf94d36.nq.gz
    ├── 4decbdee91c5513a6da0117fe5e417c5425d98e4.nq.gz
    ├── 4eebda5450ace6d9a7848699600f73bcc9c45232.nq.gz
    ├── 4f1410d14745ce0f8b4a07b83050ff3dd08492f5.nq.gz
    ├── 4fa97309814d53c775fed87ded5068a761888a66.nq.gz
    ├── 509577aa2ac586e5295445e0dcb03c58dbf3e909.nq.gz
    ├── 510e87a7a615a63f20d4f66cef78a1e6ea64ddbb.nq.gz
    ├── 51aeecb0e8772f3ff5da476961edaa3b69fe38ed.nq.gz
    ├── 51f2beede7eecb6160b9cda88bffe0dcdd065a38.nq.gz
    ├── 526b83c2f05f76bee0fc7b6485d7a5ef8150c970.nq.gz
    ├── 530ade2e59efc3b05c78fc46764335398d213551.nq.gz
    ├── 533745f263f12c78e153f5dd0f88a0f869ecc63d.nq.gz
    ├── 539eaafcbde819e3a2ffd96db5c9b1ad9b13f321.nq.gz
    ├── 53fece3ac7dfd56d6a1954f7100e608521c8e3d4.nq.gz
    ├── 54747ef5dd1d5d91cc168323b6d4f56dc4c3f565.nq.gz
    ├── 54d52f93a39fd7ddf93a023b84072a915c6bc5ed.nq.gz
    ├── 551cff913dda3595acdc2ae5fd94a07c36814aff.nq.gz
    ├── 553b90daa44a03964158290b42abeb34d141289b.nq.gz
    ├── 5747dcf160cc712259a5c34d5cce75b48ab24704.nq.gz
    ├── 5804be384a061a37aef132c798816e89987c3e73.nq.gz
    ├── 58ecf672b2b85a9975cc5457222cc0a4ce752077.nq.gz
    ├── 58fc9f3d594dbd9fa43f2a8df280f1a03b67f1f8.nq.gz
    ├── 59376752b8d1c08c331006b0804c7441bf30ec63.nq.gz
    ├── 59b5eb85e8cd84855b96992de4a097045fba214e.nq.gz
    ├── 59fbe4a5818b99498ad85bebe8b03935dc42b325.nq.gz
    ├── 5aa8372d4d3ff2ee20a9c4eb7dcb27c785f80e6d.nq.gz
    ├── 5ac1f4be783b0d3764deb42a1aeb3ad1dd0009b8.nq.gz
    ├── 5adef40a61b9530f6db38fa73fd2b6fd41056ba2.nq.gz
    ├── 5b6187c8da3afc7a6bda18997fe508746c4aa3a6.nq.gz
    ├── 5df7ec497ea82f7af60f017f7df167562dc7f178.nq.gz
    ├── 5f3fd5148af4fed5a2e8af10278f8f4cfc78ae6c.nq.gz
    ├── 5fe0839410d70a67eb21e11f55eef64f7a51f915.nq.gz
    ├── 60d55c7d91de0c3fa2494623a604b4615da4e19b.nq.gz
    ├── 6111b5fa5ceea2ecf18c6d1c59a57c315ba4f580.nq.gz
    ├── 6156d723b47cd710799b5f6f788e83324545a8c3.nq.gz
    ├── 62253906e445112d17b7f36ce777d9b070eceb17.nq.gz
    ├── 629f0d4539b58aeddd3f7effdc51801f417d005c.nq.gz
    ├── 6353abf0f5bb7fd419206b7f47ea7c361ad5a388.nq.gz
    ├── 63763838822f24d674a0434845bdad5a3157a8e7.nq.gz
    ├── 63c2c2c869f60ae0ca115aff5d97107ea0650f3e.nq.gz
    ├── 64449e86a46b720283ad9a27dfa028c487ba05c4.nq.gz
    ├── 64821b152f3dad845fa5c1836907b7638330a5ee.nq.gz
    ├── 64d8983634647731fe46d572c9b60539e4282729.nq.gz
    ├── 65ae134116c0d05e55036d48474d3592fd917a4e.nq.gz
    ├── 65c4b4a883058915320ccc6257564779146c8d77.nq.gz
    ├── 65cd64232855e5f2f101ad498a6e4403cb05f0b5.nq.gz
    ├── 65fd6114835749eb6fb09293e98e4350252f5d86.nq.gz
    ├── 667f5594603f5decc6991847e7bf53ef7d2e3644.nq.gz
    ├── 669cb6b7b6e1e0c79a3eb56e20ba54ccf2eafe7d.nq.gz
    ├── 66b665e8f32fba602589803e35defad58f129eb6.nq.gz
    ├── 67bd8d38f7f285dede4974da94f8606b9bb58bd4.nq.gz
    ├── 68b94f08b014b865c2e0197907a4a8da4c49258c.nq.gz
    ├── 69626f28aeb7a224b30d2b6a82c7668c718bf4d1.nq.gz
    ├── 69a6732e9ebcdd6016a5cdf281efc79f6d4787a5.nq.gz
    ├── 6b7cdaafd725c303084cd38470bf47aeaba4423c.nq.gz
    └── 6be6e03b8ef9409308e536aff3c0e0ee0ef51d3b.nq.gz

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

[UKPLab/eacl2026-meta-review-as-dialog](https://github.com/UKPLab/eacl2026-meta-review-as-dialog)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
