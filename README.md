# vanilla_sol
Keypairs: 64 bytes

[0:31] SK

[32:63] Pk

cargo build-bpf

solana-keygen new

solana config set -u d

solana airdrop 2

solana program deploy <path/to/program.so>
