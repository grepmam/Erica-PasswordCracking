# Erica Password Cracking

Erica is a tool that will allow you to crack many families of algorithms with their respective versions.

## How to use it

The commands are the following:

- -H/--hash
- -a/--algorithm
- -w/--wordlist

Example:

```python
python3 -H d8e8fca2dc0f896fd7cb4cb0031ba249 -a md5 -w passwords.txt 
```

## Available algorithms

* md5
* sha1
* sha3_256
* sha3_224
* sha224
* sha3_384
* sha3_512
* shake_128
* sha384
* blake2s
* blake2b
* sha512
* shake_256
* sha256
