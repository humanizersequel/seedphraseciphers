Seed Phrase Ciphers
======
![landa](https://user-images.githubusercontent.com/70870763/206868415-78a3a323-5f4b-4746-acce-c37bcafe5170.jpeg)
*"You're keeping your seed phrases in a notebook on your desk, aren't you?"*
------

The BIP39 standard —— encoding wallet seeds as a series of words, usually 12 or 24 —— was originally proposed as a way to represent wallets in a format "[superior for human interaction](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki)" since strings of random characters aren't exactly conducive to memorization or communication. It is a straightforward transformation: seed goes in, a representation as words comes out. There is some added complexity with salt shenanigans and nonstandard derivation paths, but in general it's safe to assume that these mnemonics map neatly onto the seeds they represent. Pure mathematics.

Pure, *boring*, mathematics.

The words used in these mnemonics have semantic value, history, and context. By making seed phrases compatible with language, we open the possibility for their interface with a "complex mechanism that can be grasped only through reflection" (Saussure, 1916) —— locally immutable but destined for sweeping change on a long enough time scale, impossible for man to master in its totality. 
<img width="215" alt="Screen Shot 2022-12-10 at 1 04 02 PM" src="https://user-images.githubusercontent.com/70870763/206869086-a4c06877-8962-4311-9c29-466339d3ed8e.png">

The implication is obvious: seed phrases disguised in eclectic riddles and contingent references. A dense thicket of abstraction bounded by politics and geography, an escalating series of increasing impracticalities for their own sake. Secret societies, planetary smart-contract cults. Practical? Not at all, but it's pretty fun. This repo is for collecting non-mathematical methods of seed phrase encryption.
