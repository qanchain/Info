# Info + Q&A
QUALNET Unveils Quantum Cryptographic Integration in EVM Hybrid Chain

 QUALNET, the pioneering quantum cryptographic blockchain, proudly announces a transformative upgrade to its EVM hybrid chain, reinforcing its position as a leader in quantum-resistant security. 
We have integrated advanced quantum cryptographic codes, featuring two state-of-the-art post-quantum proof signature verification algorithms: ML-DSA-87 and Dilithium Mode 5.
This strategic enhancement ensures that QUALNET’s blockchain infrastructure is fully equipped to withstand the computational power of quantum computers, safeguarding crypto assets, banking systems, IoT networks, and end-to-end encrypted communications.

Key Highlights:

ML-DSA-87:  https://qanchain.gitbook.io/qan/quantum-proof-onchain/dilithium5


Dilithium Mode 5:  https://qanchain.gitbook.io/qan/quantum-proof-onchain/mldsa-87


Input Format for Precompiled Function Calls:   https://qanchain.gitbook.io/qan/quantum-proof-onchain/input-format-for-precompiled-function-calls


 With these additions, QUALNET ensures that its network remains at the forefront of blockchain innovation, delivering unmatched security and scalability for decentralized applications across industries.


QUALNET $QAN is a Layer 1 quantum cryptographic EVM chain.
$QAN Chain integrated advanced quantum cryptographic codes, featuring two state-of-the-art post-quantum proof signature verification algorithms: ML-DSA-87 and Dilithium Mode 5. 

Here’s how these algorithms could fit in:
Wallet Security:
Users generate key pairs for their wallets. The private key stays offline, while the public key is registered on-chain.

Transaction Flow:
A user signs a transaction (e.g., token transfer or smart contract call) using one these quantum proof algorithms.

The signature, transaction data, and public key are broadcast to the network.

Verification by Nodes:
Validator nodes run the verification algorithm. They check the signature’s validity using the quantum based math, ensuring it’s authentic and untampered.

This step integrates into the consensus mechanism (e.g., Proof of Stake), where only verified transactions are added to the block.

Quantum Resistance:
These algorithms protect against quantum attacks, meaning an adversary with a quantum computer couldn’t forge signatures or reverse-engineer private keys, preserving the blockchain’s integrity.

Hybrid Approach:
For extra caution, the blockchain uses a hybrid model combining with a classical algorithm (ECDSA) to maintain compatibility during the full quantum resistance transition.

