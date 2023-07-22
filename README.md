# Encrypt
```sh
openssl enc -aes-256-cbc -pbkdf2 -iter 600000 -md sha256 -salt -in test.txt -out test.encrypted -a -A
```
# Decrypt
```sh
openssl enc -d  -aes-256-cbc -pbkdf2 -iter 600000 -md sha256 -salt -in test.encrypted -out test.txt -a -A
```

