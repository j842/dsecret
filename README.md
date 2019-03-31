# dsecret
Simple script for AES-256 encrypted secrets. Designed for small projects. Usually copied to /usr/local/bin.

A .dsecret.cfg file must be present in the upwards tree for dsecret to work.
The config file just sets the environment variable to be used for the key in that tree.

```
# The environment variable DEVOPS_PASSPHRASE needs
# to be set to be a high-entropy password. dsecret will
# use it to encrypt/decript secrets in this tree.

PASSPHRASE_ENV=DEVOPS_PASSPHRASE
```
