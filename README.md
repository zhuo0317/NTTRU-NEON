This repository is associated with the paper "Efficient NTTRU TLS 1.3 for IoT Devices", an extended version of the work presented at the 29th IEEE International Conference on Parallel and Distributed Systems (ICPADS2023) and submitted to the IEEE Internet of Things Journal. NTTRU is a key encapsulation mechanism (KEM), and we give the NEON-optimized implementation. This paper presents an efficient NTTRU TLS 1.3 on IoT devices. Our NEON-optimized implementation brings performance improvements of 2.85×, 2.36×, and 3.27× in KeyGen, Encaps, and Decaps, respectively. Besides, we integrate NTTRU NEON implementation into TLS 1.3 on a Raspberry Pi 4 Model B. The results show that the NEON-optimized implementation of NTTRU achieves faster performance than its reference C implementation under various simulated network conditions and outperforms other PQC KEMs.
