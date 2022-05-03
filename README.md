# RSA-algorithm-Implementation
About the Project
creating an RSA Algorithm using Python Programming.The purpose of this code is to demonstrate the RSA Algorithm with 4-5 digit prime numbers
Rivest, shimar, adelman (RSA)
Finding a way to transfer data securely through networks
 It’s  use to transfer vital data such as password keys and Digital signatures

First you have to convert the text too a number
	⁃	P & q is only know by the sender
	⁃	p & q = n 
	⁃	N and k is publicize to the public
	⁃	The receiver use n & k to Encrypter there messages M 
	⁃	M^k mod n=c is sent back to the sender
	⁃	Can be decrypted by using another private key E 
	⁃	Because the mathematic difficulty in factoring N, public attackers won’t be able to work out E
	⁃	C^e mod n = M
	⁃	To read messages 
Public attacker can not find the value of M because they don’t know the value of E

Built With
The language we used to code the algorithm was Python. 
https://replit.com/@monaf1/RSA-1#main.py

Running the Code
The code is run using a Prime modulus made comprised of the numbers p and q. You'll be asked to enter prime numbers for p and q, which will print out the modulus and eulerotient if both numbers are proven True. After that, you'll be prompted to provide a number that doesn't share any factors with the first two, as well as a name to encrypt. The length of time it takes the code to encrypt/decrypt the message depends on the size of the integers.

Acknowledgements
https://www.techtarget.com/searchsecurity/definition/RSA
https://pneumannsecurity.blogspot.com/2020/06/crypto-key-and-key-exchange.html
https://www.geeksforgeeks.org/rsa-algorithm-cryptography/
