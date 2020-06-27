# Known-Plaintext-Attack
--> Known-plaintext attack tool for XOR-encrypted data

Let's say we XOR-encrypt a text file using this "secure" password/key: @v3RyS3cREtK3y!
We should not forget that:

--> plaintext ⊕ key = encrypted_text
--> encrypted_text ⊕ plaintext = key
--> encrypted_text ⊕ key = plaintext

If the key is smaller than the plaintext, the key is repeated. This fact makes this encryption scheme extremely weak.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

--> Python 3.5 or above  (Download Python from www.python.org)

--> strings 0.1.2 (pip install strings)

--> os-sys 2.1.4 (pip install os-sys)

## Running Method
--> Open Powershell

--> type python KPA.py <encrypted filename> --key=<encryption key>
  
                          OR

--> KPA.py <encrypted file> <known plaintext> [max_key_length]


## Authors

* **Usama Naveed** -https://github.com/usamanaveed900)

See also the list of [Projects] (https://github.com/usamanaveed900?tab=repositories) i have woked on.



