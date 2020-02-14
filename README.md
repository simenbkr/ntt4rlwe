# NTT4RLWE

Use it to generate your omegas for NTT and INTT. Note that your modulus must be such that 2*DIMENSION divides your MODULUS.


```bash
gcc -o nttyike -O3 main.c && ./nttyike
```

Some useful, relevant links:
[Speeding up the Number Theoretic Transform for Faster Ideal Lattice-Based Cryptography](https://link.springer.com/chapter/10.1007/978-3-319-48965-0_8)

[A note on the implementation of the Number Theoretic Transform](https://eprint.iacr.org/2017/727.pdf) (NB: PDF)

[Faster AVX2 optimized NTT multiplication for Ring-LWE lattice cryptography](https://www.crypto.ethz.ch/publications/files/Seiler18.pdf) (NB: PDF)

[iblue/nttgen](https://github.com/iblue/nttgen)
