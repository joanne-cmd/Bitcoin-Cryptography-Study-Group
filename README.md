# Bitcoin Cryptography Study Group

The purpose of the group is to end up doing a deep dive into the cutting edge bitcoin tech, such as MUSIG2, FROST, and BitVM.

The initial plan is to meet every week, discuss a whitepaper, and work out the math behind it.

## Resources

### Technologies used by Bitcoin

- Taproot and Signature aggregation using MUSIG: https://github.com/bitcoinops/taproot-workshop
- MUSIG2: https://developer.blockchaincommons.com/musig/sequence/
- FROST: https://github.com/BlockchainCommons/Learning-FROST-from-the-Command-Line/blob/main/README.md
- FROST2: https://eprint.iacr.org/2021/1375.pdf
- BitVM: https://bitvm.org/

### Foundations

- Elliptic Curves, ECDSA an Schnorr (by sandipan)
- Programming Bitcoin, by Jimmy Song. Chapters 1-4 include building the ECC layer from scratch. Source code: https://github.com/jimmysong/programmingbitcoin?tab=readme-ov-file. Book: https://www.oreilly.com/library/view/programming-bitcoin/9781492031482/
- Some slides on taproot and schnorr: https://download.wpsoftware.net/bitcoin/wizardry/mw-slides/2017-05-milan-meetup/slides.pdf
- Intro to Zero Knowledge Proofs: https://zkintro.com/
- The RareSkills Book of Zero Knowledge: https://rareskills.io/tutorials/zk-book
- Groth16: https://alinush.github.io/groth16
   - This one has a lot of explainers about digital signatures and other ZKPs
- Arkworks: https://github.com/arkworks-rs/snark
   - BitVM uses arkworks as an inspiration
- For cryptography, in general: https://github.com/sobolevn/awesome-cryptography


## Meetings

Whenever possible, we will organize a meeting every week.

How a meeting is organized:
- Choose a topic for that meeting
- Research publicly available materials
- Create an easy to understand summary (preferably in Markdown)
- The meeting lasts for an hour
- First 30-40 minutes are allocated for the presentation, according to the summary
- Last 20-30 minutes are allocated for Q&A and discussion


## Roadmap

- Elliptic Curves
- Schnorr Signatures
- Zero Knowledge Proofs
- Scriptless scripts
- MUSIG2
- FROST
- BitVM
