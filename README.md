# Auto_Vigenere_Cracker

# HW 1
# Date: Sep 17
# Chenfeng Nie

---
Usage:
---

# Problem 1:

run: 
	* ./vigenere-encrypt <encipherment key> <plaintext filename> > <ciphertext filename>
		- encrypt plainetext file with given key and output as a file in the vigenere-encrypt folder
	* ./vigenere-decrypt <decipherment key> <ciphertext filename>
		- decrypt ciphertext file with given key in the vigenere-encrypt folder

# Problem 2 & 3: Finding key lengths and Full cryptanalysis
run:
	* ./vigenere-keylength <ciphertext filename>
		- run full cryptanalysis to figure out the possible key length, possbile key and decrypted ciphertext
		
# Problem 4:
	if we modify the Vigenere encipherment to use a single key that is at least as long as the message. 
	This cipher might be more secure because in this case it is too hard to do index of coincidence analysis. Moreover, the longer length of key cause computer process longer time to decrypt.  
	 I would place the key long enough.