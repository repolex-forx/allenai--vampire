# Repolex Knowledge Graph of allenai/vampire

RDF knowledge graph data for [allenai/vampire](https://github.com/allenai/vampire), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/vampire
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cf5c2fe17caf73bbd0a470c48cba4d3ab4e847ff
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cf5c2fe17caf73bbd0a470c48cba4d3ab4e847ff
│           └── chunk-001.nq.gz
├── blob
│   ├── 04f37bca9d85d19b1657e9c1810250df5cf37c2b.nq.gz
│   ├── 05cc64d7cf0655b185eebc66728bd62107b85b76.nq.gz
│   ├── 06c99d8a3ae34bb20e900e4209ad867ecfe25c84.nq.gz
│   ├── 0869a5b28a65cc1edb426b83d9d555fff11136df.nq.gz
│   ├── 16967f2292a0b7686fff2cdc4ee2ef367212e52c.nq.gz
│   ├── 1c1cdd2b1ec4b560d558860187e2c84e52968f57.nq.gz
│   ├── 23ab94fd802aaf3ae02a8ff5bb32d94db7ee919d.nq.gz
│   ├── 25394b5ecc122f57f422f60ea5866cb722e41ece.nq.gz
│   ├── 25a0335f381065802c6bd95d7f28c2ad8ce6c15f.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 27fb46a9e9aadb9653951f1f072ea4a9c5240940.nq.gz
│   ├── 2f5c577dcd5397650088db6e45483f4c44d68b58.nq.gz
│   ├── 3094c5081533948ebedca525b7164255310d1f4d.nq.gz
│   ├── 36e9923cd658feefa68932abb90132c621bb6255.nq.gz
│   ├── 39821627d098caf85b12e6983b628dd273dd7936.nq.gz
│   ├── 3a18f1ed00cfa68155ff8162d43e4901c78dfdd4.nq.gz
│   ├── 3e17c01a0471a577f3af790f9c545f6a3bd627e5.nq.gz
│   ├── 3e814599476e21699f16a4db94848864c6c1c44d.nq.gz
│   ├── 3ef6f7147517ad8958b340c3b34da96615f44812.nq.gz
│   ├── 3f1c74ae8f016466c481a7b051f58e77ad2f62eb.nq.gz
│   ├── 415bdb256a32152aab58b77b1a94e5a96dd522bb.nq.gz
│   ├── 470a7f708e5582c51d3918d448b36bcb388023f9.nq.gz
│   ├── 4f346d7c5dc590ee5ba86ae126c9c088a55012ca.nq.gz
│   ├── 52d5755f6dab392be94c9141d4f0652ea36ad5f8.nq.gz
│   ├── 54f53d25e76ddae319d35b94e2ac1af54bf1ef56.nq.gz
│   ├── 5a6457e3c8982ed32ee4bfc2c468ac8e48ade370.nq.gz
│   ├── 5d307012585f0e1363137eb0b08a854ed69e2480.nq.gz
│   ├── 60c21a6abf7a40d75173c76d519f55d6d645b5b8.nq.gz
│   ├── 62be84e6ffb3477493aa976cf400b46168f71023.nq.gz
│   ├── 6d4d2a10e5919561861035de9c98e695481d8c2a.nq.gz
│   ├── 72993681357b07fdbae5fe2f3e8d087a1a440a01.nq.gz
│   ├── 782540e31394556d8b48151b66812c5e7976fa3c.nq.gz
│   ├── 833ed432580b7b2b794fae27efab3a9878bcc31d.nq.gz
│   ├── 87e1627ea2c6aa0ba3ea6481ff510237656da76e.nq.gz
│   ├── 8d71fdd463e30492c5ed7ab87f22c3ac4cf0a1f6.nq.gz
│   ├── 91b8f99c98ad7a6437631b5528e1604330a2f5e7.nq.gz
│   ├── 924400036988fc19917e6cf6c86b9caa11c84049.nq.gz
│   ├── 934f1a14d8da73de33d858da538e6275fc4736fa.nq.gz
│   ├── 93cae89461e10287ea82b7e5dbff90b8ab0983df.nq.gz
│   ├── 9e65d15acb68ac3d9b62460c051349b28f9e15a0.nq.gz
│   ├── a0693aa0b01408beb949fe7771bf01df4d439be3.nq.gz
│   ├── a3b4dc8dfc3dbbaaecb447e72a46f8ca9cd0c240.nq.gz
│   ├── a953f2f390bf4d0c8c0ac2d33f573e2675797231.nq.gz
│   ├── af10ab6bf098831b47051247f0a80d57badcc636.nq.gz
│   ├── af480b3da9bba1a360966ca6f0fd902219168223.nq.gz
│   ├── b583e47b05b92d8c44d53445be75be074d5d0726.nq.gz
│   ├── c1adfe02f6e1a5fd86864994440f5a9e876006a8.nq.gz
│   ├── c263b8a05f7e520094d7031ecd662bc9b5d7ddbd.nq.gz
│   ├── c6ece52a60bf31e49514e98191674175457e054b.nq.gz
│   ├── c74b06c346aa0e0df4061d1a80d2d10c32a2c34f.nq.gz
│   ├── d03246dc28e58839f8f1bb6a1d93e74a27466139.nq.gz
│   ├── d6c0f1d1486e6d698efa1230b7de713dc1953a09.nq.gz
│   ├── da8a52b68f61eddcd916521fd6928334ec18d235.nq.gz
│   ├── dcb7221f08d4ff9bfa9e56f5205b74ce82858bd5.nq.gz
│   ├── e0eaf8b544a919a8bc325bcb02c6dd03f0beda7a.nq.gz
│   ├── e0f01354e10a66edd2f6213e8702808f13b8940f.nq.gz
│   ├── e28e2e422d8d952e5a9d603ed252ea9817e824e9.nq.gz
│   ├── e3836b0d989623f67e4892dbfe1bd9ab25ab278e.nq.gz
│   ├── e46bc96648b80b7448243ce745771c185a534d9b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f3396a7f5a1fdf5961cf164b2e894fc57994a14b.nq.gz
│   ├── fe5259188d846c2e520476414824e2fe9b33b28f.nq.gz
│   ├── ff1bbc91da1b370fedf27bbe5b7be20803e7f1d3.nq.gz
│   ├── ff2679ef0e99e2e344190d865461170c98574b51.nq.gz
│   └── ffadda35be7188b7033d86bc23b5a944aac27993.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cf5c2fe17caf73bbd0a470c48cba4d3ab4e847ff.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 73 files
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

[allenai/vampire](https://github.com/allenai/vampire)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
