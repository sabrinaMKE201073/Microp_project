# Microp_project
In this algorithm coding of AES implementation,
It consists of 4 main steps in order for the encryption of data;
a. SubBytes that associate all the 8bits letters of the state with other letter.
b. ShiftRow that rearange the subparts of the key by rotating those by 0, 
1, 2 and 3 bytes
c. MixColumns that multiply all the 4 parts of the state by a matrix (A)
d. AddRoundKey that XOR the state with the key optained with the Key 
Schedule algorithm
And, at the end, the final phase that is the same as a repetition from the main phase 
but withtout the MixColumns function.
