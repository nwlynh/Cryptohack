#Cryptohack Write-up
Writeup lời giải cho RSA trên Cryptohack. Toàn bộ nội dung nằm trong RSA.md: phân tích lỗ hổng, chứng minh toán học và code khai thác từng bài 

## Danh mục
``` 
|-- Starter/
|       |-- Modular Exponentiation
|       |-- Public Keys
|       |-- Euler's Totient
|       |-- Private Keys
|       |-- RSA Decryption
|       |-- RSA Signatures
|-- Primes Part 1/
|       |-- Factoring
|       |-- Inferius Prime
|       |-- Monoprime
|       |-- Square Eyes
|       |-- Manyprime
|-- Public exponent/
|       |-- Salty
|       |-- Modulus Inutilis
|       |-- Everything is Big
|       |-- Crossed Wires
|       |-- Everything is Still Big
|       |-- Endless Emails
|-- Primes Part 2/
|       |-- Infinite Descent
|       |-- Marin's Secrets
|       |-- Fast Primes
|       |-- Ron was Wrong, Whit is Right
|       |-- RSA Backdoor Viability
|-- Padding/
|       |-- Bespoke Padding
|       |-- Null or Never
|-- Signatures Part 1/
|       |-- Signing Server
|       |-- Let's Decrypt
|       |-- Blinding Light
|-- Signatures Part 2/
	|-- Vote for Pedro 
	|--  Let's Decrypt Again 
``` 
## Công cụ sử dụng
* pycryptodome, sympy, gmpy2
* FactorDB để phân tích N 
