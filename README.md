## 📃 Instructions to mint NFT on Binance Smart Chain(BSC):
1. **If deploy on BSC testnet, get BNB from faucet:**
</br>**[link](https://testnet.binance.org/faucet-smart)**

2. **Migrate contract to BSC testnet:**
</br>truffle migrate --reset --network bsc_testnet

3. **Mint NFT on BSC testnet:**
</br>truffle exec scripts/mint.js --network bsc_testnet

4. **Migrate contract to BSC mainnet:**
</br>truffle migrate --reset --network bsc_mainnet

5. **Mint NFT on BSC mainnet:**
</br>truffle exec scripts/mint.js --network bsc_mainnet