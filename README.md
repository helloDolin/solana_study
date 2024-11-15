# solana_study
solana study

# 环境
## rust
安装：
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y

环境变量：
export PATH="$HOME/.cargo/bin:$PATH"

验证
rustc --version

## solana CLI
安装
sudo sh -c "$(curl -sSfL https://release.anza.xyz/stable/install)"

环境变量
echo 'export PATH="$HOME/.local/share/solana/install/active_release/bin:$PATH"' >> ~/.zshrc

验证
solana --version

# 创建账号
教程
https://www.solanazh.com/course/1-4

## 开发网
solana config set --url https://api.devnet.solana.com
    
    Config File: /Users/you/.config/solana/cli/config.yml
    RPC URL: https://api.devnet.solana.com
    WebSocket URL: wss://api.devnet.solana.com/ (computed)
    Keypair Path: /Users/you/.config/solana/id.json
    Commitment: confirmed

solana-keygen new --force

Generating a new keypair

For added security, enter a BIP39 passphrase

NOTE! This passphrase improves security of the recovery seed phrase NOT the
keypair file itself, which is stored as insecure plain text

BIP39 Passphrase (empty for none):

Wrote new keypair to /Users/bd/.config/solana/id.json
=============================================================================
pubkey: B7cvGbzeo77ecNZbXByFEUzVrXNnMPpAJ3QBRpvcskUB
=============================================================================
Save this seed phrase and your BIP39 passphrase to recover your new keypair:
come response obvious toward section conduct exit two letter sail viable lake

## 测试网：
➜  ~ solana config set --url https://api.testnet.solana.com

Config File: /Users/bd/.config/solana/cli/config.yml
RPC URL: https://api.testnet.solana.com
WebSocket URL: wss://api.testnet.solana.com/ (computed)
Keypair Path: /Users/bd/.config/solana/id.json
Commitment: confirmed
➜  ~ solana-keygen new --force

Generating a new keypair

For added security, enter a BIP39 passphrase

NOTE! This passphrase improves security of the recovery seed phrase NOT the
keypair file itself, which is stored as insecure plain text

BIP39 Passphrase (empty for none):

Wrote new keypair to /Users/bd/.config/solana/id.json
=============================================================================
pubkey: 7jaoTL9pMim9AQ7mZB4TVfqDxsPuAuHPwjRfDvs8rxsr
=============================================================================
Save this seed phrase and your BIP39 passphrase to recover your new keypair:
dish ridge domain practice awkward day business sad evolve bacon style oppose
=============================================================================

# 申请水龙头
方式一：
solana airdrop 1

方式二：
https://solfaucet.com/





