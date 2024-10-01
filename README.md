# command for 3.1:   
`openssl enc -aes-128-cbc -e -in plain.txt -out cipher_aes_128_cbc.bin -K 00112233445566778899aabbccddeeff -iv 01020304050607080102030405060708`   
`openssl enc -aes-128-cfb -e -in plain.txt -out cipher_aes_128_cfb.bin -K 00112233445566778899aabbccddeeff -iv 01020304050607080102030405060708`   
`openssl enc -aes-128-ofb -e -in plain.txt -out cipher_aes_128_ofb.bin -K 00112233445566778899aabbccddeeff -iv 01020304050607080102030405060708`   
`openssl enc -aes-128-ctr -e -in plain.txt -out cipher_aes_128_ctr.bin -K 00112233445566778899aabbccddeeff -iv 01020304050607080102030405060708`   

# command for 3.2:
`openssl enc -aes-128-ecb -in test.bmp -out test_ecb.bmp -K 00112233445566778899aabbccddeeff`   
`openssl enc -aes-128-cbc -in test.bmp -out test_cbc.bmp -K 00112233445566778899aabbccddeeff -iv 01020304050607080102030405060708`
