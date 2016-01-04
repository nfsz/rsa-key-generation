This program implements the RSA encryption algorithm. It outputs a pair of generated public and private keys, along with a sample message that is encrypted and decrypted with the keys.

Run instructions: 
On the command line, type 'python rsa.py' 

if you want to specify the modulus size in bits, you may add the arg e.g.
'python rsa.py 2048'

Otherwise, the modulus size will default to 1024 bits.


This program was written with the latest version of python (3.5)

The primality test is performed with the Miller-Rabin algorithm.
The modular multiplicative inverse is computed with the Extended Euclidean algorithm.

The algorithm uses certain Python library functions:
Multiplication - Python uses the Karatsuba algorithm for large integers
Modular exponentiation - Python uses the k-ary LR method for large exponents.



Coded for UMBC CMSC 441 Project 2