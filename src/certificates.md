# Post Quantum Certificates

Post-Quantum Certificates (PQCs) are cryptographic certificates designed to be secure against potential attacks from quantum computers, which are expected to break traditional algorithms like RSA and ECC. These certificates leverage post-quantum algorithms to protect data in a future where quantum computing capabilities might threaten current cryptographic methods.

Open Quantum Safe (OQS) provides tools to integrate post-quantum algorithms into commonly used security protocols such as TLS and X.509 certificates. The project supports generating both hybrid and pure post-quantum certificates, making it possible to use combinations of traditional and post-quantum cryptography for a smoother transition during this shift.

NIST has been actively involved in selecting and standardizing post-quantum algorithms for digital signatures and key exchange. Examples of these algorithms include Dilithium for digital signatures and Kyber for key exchange, both of which have been recommended for adoption to ensure the robustness of future cryptographic solutions. In this context, QubeSec has also been working on implementing quantum-resistant certificates using these algorithms to help secure communications and sensitive data.

