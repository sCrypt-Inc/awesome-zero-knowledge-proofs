<div align="center">
  <h1 align="center">Awesome ZKPs</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>
  
  <p align="center">A curated list of awesome ZKP resources, libraries, tools and more.</p>
  <p align="center">Please check the <a href="CONTRIBUTING.md">contribution guidelines</a> for information on formatting and writing pull requests.</p>
  
</div>

### Contents

- [Introductions](#introductions)
- [Tutorials](#tutorials)
- [Programming Languages](#programming-languages)
- [Tools](#tools)
  - [ZoKrates: a toolbox for zkSNARKs](#zokrates-a-toolbox-for-zksnarks)
  - [Snarkjs: zkSNARK implementation in JavaScript & WASM](#snarkjs-zksnark-implementation-in-javascript--wasm)
- [Books](#books)
- [Communities](#communities)
- [Other Curated Lists](#other-curated-lists)
- [Proof Systems](#proof-systems)
  - [zkSNARKs](#zksnarks)
    - [PLONK](#plonk)
      - [Videos](#videos)
  - [zkSTARKs](#zkstarks)
  - [Bulletproofs](#bulletproofs)
- [Trusted Setup](#trusted-setup)
  - [Subversion Resistance](#subversion-resistance)
- [Applications](#applications)
- [License](#license)

## Introductions
- [Understanding ZKPs Through Illustrated Examples](https://blog.goodaudience.com/understanding-zero-knowledge-proofs-through-simple-examples-df673f796d99)
- [Zero Knowledge Proofs: An Illustrated Primer by Matthew Green](https://blog.cryptographyengineering.com/2014/11/27/zero-knowledge-proofs-illustrated-primer/)
- [Demonstration of Zero-Knowledge Proof for Sudoku Using Standard Playing Cards](https://www.wisdom.weizmann.ac.il/~naor/PAPERS/SUDOKU_DEMO/)
- [zudoku](https://zudoku.xyz/): ZK proving knowledge of Sudoku solutions
- [Zero Knowledge Proof and its Applications in Bitcoin](https://xiaohuiliu.medium.com/zero-knowledge-proof-and-its-applications-in-bitcoin-aca833d7d745)
- [zk-SNARKs on Bitcoin](https://xiaohuiliu.medium.com/zk-snarks-on-bitcoin-239d96d182bd)
- [ZKPs for Engineers: Introduction](https://blog.zkga.me/intro-to-zksnarks)


## Tutorials
- [zk Battleship interactive course by sCrypt](https://learn.scrypt.io/en/courses/630b1fe6c26857959e13e160)
- [Create Your First Zero-Knowledge Proof Program on Bitcoin](https://xiaohuiliu.medium.com/create-your-first-zero-knowledge-proof-program-on-bitcoin-ec159cc501f4): use ZoKrates
- [Intro to Circom and Snarkjs by Iden3](https://iden3-docs.readthedocs.io/en/latest/iden3_repos/circom/TUTORIAL.html)
- [Getting Started with zkSnarks on ZoKrates](https://blog.gnosis.pm/getting-started-with-zksnarks-zokrates-61e4f8e66bcc)
- [Proving Knowledge of a Hash Pre-Image with ZoKrates](https://blog.decentriq.com/proving-hash-pre-image-zksnarks-zokrates/)
- [Zokrates Hello World Walkthrough](https://hackmd.io/@adietrichs/HkH0OduZw)
- [Zero Knowledge Proofs Workshop - Zokrates Tutorial](http://extropy.foundation/workshops/zkp/zokrates.html)
- [A Practical Guide To Building Zero Knowledge dApps](https://kndrck.co/posts/practical_guide_build_zk_dapps/): Circom


## Programming Languages 
- [Introduction to Domain Specific Languages (DSLs)](https://youtu.be/kqnYbSmdcbA?t=392) by Alex Ozdemir
- [Programming Languages in ZKP](https://medium.com/delendum/thoughts-of-programming-languages-in-zkp-c906e96f056e) by Delendum Ventures: video is on [YouTube](https://www.youtube.com/channel/UCM7Dc3y3BVTTpprDidVV7iw)

| Name  | Type | GitHub | Documentation | 
| ------------- |:-------------:|:-------------:|:-------------:|
| ZoKrates     | Python subset   | https://github.com/Zokrates/ZoKrates | https://zokrates.github.io |
| Circom |  HDL   | https://github.com/iden3/circom | https://docs.circom.io |
| SnarkyJS | Typescript DSL | https://github.com/o1-labs/snarkyjs | https://docs.minaprotocol.com/en/zkapps/snarkyjs-reference | 
| Cairo     | for STARK  | https://github.com/starkware-libs/cairo-lang | https://cairo-lang.org/docs/ | 
| Leo      | Functional, statically-typed  | https://github.com/AleoHQ/leo | https://developer.aleo.org/developer/language/layout/ |


## Tools
### ZoKrates: a toolbox for zkSNARKs
Both on [Bitcoin](https://github.com/sCrypt-Inc/zokrates) and [Ethereum](https://zokrates.github.io/)
- [Zero Knowledge Proofs Workshop - Zokrates Tutorial](http://extropy.foundation/workshops/zkp/zokrates.html)
- [Zokrates Hello World Walkthrough](https://hackmd.io/@adietrichs/HkH0OduZw)
- [Practical ZK-SNARKs for Ethereum](https://coders-errand.com/practical-zk-snarks-for-ethereum/)

### Snarkjs: zkSNARK implementation in JavaScript & WASM
Both on [Bitcoin](https://github.com/sCrypt-Inc/snarkjs) and [Ethereum](https://github.com/iden3/snarkjs)
- [Circom Workshop 1 by 0xparc](https://learn.0xparc.org/materials/learning-group-1/circom-1)
- [Circom Workshop 2 by 0xparc](https://learn.0xparc.org/materials/learning-group-1/circom-2)


## Books

- [Proofs, Arguments, and Zero-Knowledge](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf) (Justin Thaler, 2022)
- [A Graduate Course in Applied Cryptography](http://toc.cryptobook.us/book.pdf) (Dan Boneh and Victor Shoup, 2020)


## Communities
- [Zero-knowledge podcast](https://www.zeroknowledge.fm): #1 podcast for ZK
- [0xPARC: Applied ZK Learning Group](https://learn.0xparc.org/)
- [ZKProof](https://zkproof.org/): an academic and industry initiative for standardizing ZKPs


## Other Curated Lists
- [matter-labs: Awesome zero knowledge proofs](https://github.com/matter-labs/awesome-zero-knowledge-proofs)
- [ventali/awesome-zk](https://github.com/ventali/awesome-zk)
- [zkp.science](https://zkp.science)
- [Zero-Knowledge Proofs Starter Pack](https://ethresear.ch/t/zero-knowledge-proofs-starter-pack/4519)
- [gakonst/awesome-starknet](https://github.com/gakonst/awesome-starknet)
- [Zero Knowledge Canon by a16z](https://a16zcrypto.com/zero-knowledge-canon/)


## Proof Systems
- [Comparison of the most popular zkp systems](https://github.com/matter-labs/awesome-zero-knowledge-proofs#comparison-of-the-most-popular-zkp-systems)

|                                       | SNARKs                     | STARKs                        | Bulletproofs    |
| ------------------------------------: | -------------------------: | ----------------------------: | --------------: |
| proving time       | O(N * log(N))              | O(N * poly-log(N))            | O(N * log(N))   |
| verifying time      | ~O(1)                      | O(poly-log(N))                | O(N)            |
| proof size | ~O(1)                      | O(poly-log(N))                | O(log(N))       |
| Trusted setup required?               | YES :unamused:             | NO :smile:                    | NO :smile:      |
- [Proving system comparison](https://youtu.be/LBTrX0Ukdvs?t=309) ![compare snarks](./images/compare_snarks3.png)
- [zk-SNARKs vs. Zk-STARKs vs. BulletProofs](https://ethereum.stackexchange.com/questions/59145/zk-snarks-vs-zk-starks-vs-bulletproofs-updated) ![compare](./images/comparisons.png)
- [Comparing General Purpose zk-SNARKs](https://medium.com/coinmonks/comparing-general-purpose-zk-snarks-51ce124c60bd) ![compare snarks](./images/compare_snarks2.png)
- [Comparison of Different zk-SNARKs](https://zhuanlan.zhihu.com/p/40245832) ![compare snarks](./images/compare_snarks.jpeg)
- [A Cambrian Explosion of Crypto Proofs Eli Ben-Sasson](https://nakamoto.com/cambrian-explosion-of-crypto-proofs/)

### zkSNARKs


#### PLONK
- [Awesome PLONK](https://github.com/fluidex/awesome-plonk): a curated list of awesome things related to Plonk
- How PLONK works: [Part 1](https://xiaohuiliu.medium.com/how-plonk-works-part-1-bc8050f4805e) and Part 2
- [PLONK by Hand](https://research.metastate.dev/plonk-by-hand-part-1/): 3 parts from MetaState
- [A good tutorial on PLONK in CN](https://blog.csdn.net/AdijeShen/article/details/123332665)
- [Understanding PLONK by Vitalik](https://www.vitalik.ca/general/2019/09/22/plonk.html)
- [Understanding PLONK by David Wong](https://www.cryptologie.net/article/527/understanding-plonk/)
- [A Python tutorial of the paper PLONK](https://github.com/barryWhiteHat/plonk_tutorial)

##### Videos
- [ZK Study Club - Plonk with Zac Williamson](https://youtu.be/NqrVcDuQ8hM)
- [How PLONK works by David Wong](https://www.youtube.com/playlist?list=PLBJMt6zV1c7Gh9Utg-Vng2V6EYVidTFCC): a 12-part series
- [PLONK: Privacy in a World of Universal SNARKs - Zac Williamson](https://youtu.be/V7Hmtan98r8)
- [PLONK: Ariel Gabizon (Protocol Labs)](https://youtu.be/dHo56MhQlHk)


### zkSTARKs

### Bulletproofs


## Trusted Setup
- [The Incredible Machine](https://medium.com/qed-it/the-incredible-machine-4d1270d7363a): ZKP proving Sudoku and physical trusted setup
- [Diving into the zk-SNARKs Setup Phase](https://medium.com/qed-it/diving-into-the-snarks-setup-phase-b7660242a0d7)
- [Trusted Setup Workshop by 0xparc](https://learn.0xparc.org/materials/learning-group-1/trusted-setup)
- [Setup Ceremonies](https://zkproof.org/2021/06/30/setup-ceremonies/)
- [On-Chain Trusted Setup Ceremony](https://a16zcrypto.com/on-chain-trusted-setup-ceremony/)
- [How do trusted setups work?](https://vitalik.ca/general/2022/03/14/trustedsetup.html)
- [Announcing the Perpetual Powers of Tau Ceremony to benefit all zk-SNARK projects](https://medium.com/coinmonks/announcing-the-perpetual-powers-of-tau-ceremony-to-benefit-all-zk-snark-projects-c3da86af8377)
- [Trusted setup ceremonies explored](https://www.zeroknowledge.fm/133)

### Subversion Resistance
- [A Subversion-Resistant SNARK](https://eprint.iacr.org/2017/599)
- [Zero knowledge, subversion resistance, and concrete attacks | Steven Goldfeder | RWC 2018](https://youtu.be/DP8xSEM9bd8)
- [Zero-Knowledge Contingent Payments Revisited](https://eprint.iacr.org/2017/566)


## Applications
- [zkDocs: attestation](https://a16zcrypto.com/zkdocs-zero-knowledge-information-sharing/): [Github repo](https://github.com/a16z/zkdocs)
- [Poker](https://medium.com/coinmonks/zk-poker-a-simple-zk-snark-circuit-8ec8d0c5ee52)
- [StealthDrop: anonymous airdrop](https://github.com/stealthdrop/stealthdrop): [another one from a16z](https://a16z.com/2022/03/27/crypto-airdrop-privacy-tool-zero-knowledge-proofs/)

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, sCrypt Inc has waived all copyright and related or neighboring rights to this work.
