# MEME Asset List

Token List
This file determines the assets available.

IBC Assets
This file determines the assets that can be deposited and withdrawn via IBC.

Chain Info
This file provides configuation to Keplr for interacting with the chain.

Important Security Info
Before adding any assets, query the contract and ensure it is instantiated from the proper byte code. 
The metadata should also be checked with memed q wasm contract <contract-address> to ensure an admin is not set as this could put users liquidity at risk.
  
  
