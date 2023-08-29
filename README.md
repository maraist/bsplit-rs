# bsplit-rs
Bernoulli Split (rust)

# Summary

This library is a proving ground for the various implementations of
1. Arithmatic encoding of 41-choose-k, 9-choose-k
2. FiniteStateMachine encoding Bernoulli Split of n-choose-k for  1 < k <= 8
3. Byte-Aligned encoding of larger k-sizes (skip friendly, stable-size), partition-collision-residue P.C.R.
4. Recursive-Macro-Groups to allow for more efficient random-access and machine-word sized operations
5. Utilities to merge/split/search bsplit-streams
6. Higher level utilities to encode non-conforming bitsets (lists of ordered numbers, sorted arrangements, random (but similar) numbers)


The theory and testing (and automated tools for statistics) can be found at:
[bsplit-py](https://github.com/maraist/bsplit-py)


