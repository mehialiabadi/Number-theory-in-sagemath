# Number-theory-in-sagemath


Lets start with implemention of RSA in sagemath.
Whole process includes key generation, encryption and decryption algotithms.

Key generation:

1- choose	two	big	primes	p	and	q,	and	let	n=pq. 

2. Let e>0 s.t. gcd(e, phi(n))=1

4. Find	a	an integer d s.t.	d be the inverse of e in mode phi(n). 


6. Consider (n,	e) as public	key		and (p,	q,	d)	as private key. 

Encryption: 

1- For any message m <n, encrypt m by c=m^e mode n

Decryption:

1- Decrypty ciphertext c and obtaim m by m=c^d=m^(e.d) mod n
 
Now it's time to go through sagemath and impleemnt this sudocode in sagemath. 


