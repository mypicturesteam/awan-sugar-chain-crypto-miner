# awan-sugar-chain-crypto-miner
My Docker Automation For Fast Deployment Sugar Crypto Currency Miner

1. Let's Clone this repo
$ git clone https://github.com/addhe/awan-sugar-chain-crypto-miner.git

2. Change directory and Let's build it
$ cd awan-sugar-chain-crypto-miner.git && docker build -t awan/sugar-chain-crypto-miner:1.0.1 . 

3. Run's this with your cryptocurrency wallet,
$ docker run -itd -e "CRYPTO_WALLET_MINING={{ change_me_with_your_wallet_mining }}.{{ change_me_with_uniq_id }}" -e "THREAD_COUNT={{ change me with our CPU Thread }}" awan/sugar-chain-crypto-miner:1.0.1

example:
$docker run -itd -e "CRYPTO_WALLET_MINING=sugar1qxpnfsfu0wpgl6khnjjpgrkagtqn7jsv36dj8nk.sugarchain_20201206_3" -e "THREAD_COUNT=1" awan/sugar-chain-crypto-miner:1.0.1 

or can read more
https://hub.docker.com/repository/docker/awan/sugar-chain-crypto-miner/general
