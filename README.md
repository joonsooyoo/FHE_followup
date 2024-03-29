# 0. Recent Release
* [Parameter Optimization and Larger Precision for (T)FHE](https://eprint.iacr.org/2022/704.pdf)

# 1. FHE in General
## Introduction
* [Holy Grail of FHE](https://www.cs.utexas.edu/~dwu4/papers/XRDSFHE.pdf)

## Youtube Video
* [a Decade of FHE (spoken at Eurocrypt 2021 by Gentry)](https://www.youtube.com/watch?v=487AjvFW1lk&t=3917s)

# 2. TFHE (Fast Fully Homomorphic Encryption over the Torus)
## General
* [TFHE Homepage](https://tfhe.github.io/tfhe/)

## TFHE Youtube Video
* [TFHE deep dive by Illaria at Zama](https://www.youtube.com/watch?v=npoHSR6-oRw&t=28s)
* [Homomorphic Large Precision Integers Using Concrete by Jean-Baptiste](https://www.youtube.com/watch?v=50zE42Lzbd8&t=182)

## Easy Illustration
* [A CONCRETE approach to torus fully homomorphic encryption by Maria Ferrara](https://eprint.iacr.org/2022/594.pdf)
* [TFHE for Practitioners by Illaria (part 1)](https://www.zama.ai/post/tfhe-deep-dive-part-1?utm_source=tfhe_deep_dive_part_I&utm_medium=discourse&utm_campaign=blogpost)
* [TFHE for Practitioners by Illaria (part 2)](https://www.zama.ai/post/tfhe-deep-dive-part-2)
* [TFHE for Practitioners by Illaria (part 3)](https://www.zama.ai/post/tfhe-deep-dive-part-3)
* [TFHE for Practitioners by Illaria (part 4)](https://www.zama.ai/post/tfhe-deep-dive-part-4)

## TFHE Paper
* [TFHE Illaria Chillotti Thesis Paper](https://ilachill.github.io/papers/these_Ilaria_Chillotti_wo_acknowl.pdf)
* [Multikey-TFHE 2019](https://eprint.iacr.org/2019/116.pdf)

## Implementation
#### Library
* [original-TFHE](https://github.com/tfhe/tfhe) : C/C++ code / implements boostrapping homomorphic binary gates
* [multikey-TFHE](https://github.com/ilachill/MK-TFHE) : (POC) C/C++ code / implements multi-key asymmetric encryption of FHE
* [Concrete Library](https://github.com/zama-ai) : New Release of TFHE / PBS functionality + many more TFHE operations

#### CONCRETE Implementation Guide (ZAMA)
* [tutorial on concrete-FHE](https://docs.zama.ai/concrete/lib/user/README.html)

# 3. B\FV, CKKS, and LWE
## B\FV
* [[FV12] Somewhat Practical Fully Homomorphic Encryption](https://eprint.iacr.org/2012/144.pdf)
#### Implementation
* [BFV written in Python from scratch](https://blog.openmined.org/build-an-homomorphic-encryption-scheme-from-scratch-with-python/)

## CKKS
#### Implementation
* [SEAL by Microsoft](https://github.com/microsoft/SEAL)

## LWE
* [On Lattices, Learning with Errors, Random Linear Codes, and Cryptography](https://cims.nyu.edu/~regev/papers/qcrypto.pdf) : first introduction of LWE
* [On Ideal Lattices and Learning with Errors Over Rings 2010](https://eprint.iacr.org/2012/230.pdf) : expansion of LWE problem to RLWE (ring)

# 4. Miscellaneous
## Programming
#### Rust Programming (Learn Rust)
* [Rust Official Documentation](https://doc.rust-lang.org/book/title-page.html)
* [Rust by Example](https://doc.rust-lang.org/rust-by-example/primitives/tuples.html)

## Cryptography
#### Open Source Book
* [A Graduate Course in Applied Cryptography by Boneh and Shoup](http://toc.cryptobook.us/book.pdf)

## Some Math
* [primitive roots](https://brilliant.org/wiki/primitive-roots-of-unity/#:~:text=Primitive%20n%20th%20n%5E%5Ctext,theory%2C%20especially%20algebraic%20number%20theory.)
* [cyclotomic poly.](https://brilliant.org/wiki/cyclotomic-polynomials/)
