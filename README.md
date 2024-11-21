# glacier-node
glacier-node tesnet

Hardware Requirements
Minimum:
CPU with 1+ cores

2GB RAM

4 MBit/sec download Internet service

Recommended:
Fast CPU with 2+ cores

4GB+ RAM

8+ MBit/sec download Internet service


installing:

mkdir glacier

cd glacier

wget https://github.com/Glacier-Labs/node-bootstrap/releases/download/v0.0.1-beta/verifier_linux_amd64
wget https://glacier-labs.github.io/node-bootstrap/config.yaml

nano config.yaml

replace YourPrivateKey with your private key.

then ctrl+x+y

screen -S glacier-node

chmod +x ./verifier_linux_amd64
./verifier_linux_amd64

ctrl A+D

done!



















