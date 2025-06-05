# Minnn
MIN Coin - Proof of Work, 30min block
git clone https://github.com/minnnsx/Minnn.git
cd Minnn
Minnn/
├── src/
│   ├── chainparams.cpp    // konfigurasi MIN coin (block time, reward, halving)
│   ├── validation.cpp     // logik block reward
│   └── ... (fail dari Litecoin lain)
├── genesis.py            // generate genesis block
├── BUILD.sh              // skrip compile automatik
└── README.md             // panduan lengkap pakek di Termux
python3 genesis.py --pszTimestamp "Minnn genesis 06/2025" --time 169"timestamp" ...
#!/usr/bin/env bash
./autogen.sh
./configure --disable-wallet
make -j$(nproc)
README.md
Dalam README aku sediakan arahan untuk:

Setup proot-distro ubuntu dalam Termux
Clone repo
Run genesis.py → copy nonce & hash → update chainparams.cpp
Jalankan ./BUILD.sh
Launch node: ./src/minind -regtest -daemon
Monitor chain stats & mining reward
README.md
Dalam README aku sediakan arahan untuk:

Setup proot-distro ubuntu dalam Termux
Clone repo
Run genesis.py → copy nonce & hash → update chainparams.cpp
Jalankan ./BUILD.sh
Launch node: ./src/minind -regtest -daemon
Monitor chain stats & mining reward

