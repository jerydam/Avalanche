## ERC20 Token Contract

This Solidity contract represents an ERC20 token contract. It includes functions for transferring, approving, and transferring from addresses, as well as minting and burning tokens. Events such as `Transfer` and `Approval` are triggered during these operations.

### Functions:

1. **transfer:** `function transfer(address recipient, uint amount) external returns (bool)`
2. **approve:** `function approve(address spender, uint amount) external returns (bool)`
3. **transferFrom:** `function transferFrom(address sender, address recipient, uint amount) external returns (bool)`
4. **mint:** `function mint(uint amount) external`
5. **burn:** `function burn(uint amount) external`

Events:

- **Transfer:** `event Transfer(address indexed from, address indexed to, uint value)`
- **Approval:** `event Approval(address indexed owner, address indexed spender, uint value)`
- **Token Contract Address**`0x5DB9A7629912EBF95876228C24A848de0bfB43A9`
---

## Vault Contract

The Vault contract interacts with the ERC20 token and facilitates the deposit and withdrawal of tokens. Users can deposit tokens, receiving shares in return, and withdraw tokens by burning a specified number of shares. Internal functions `_mint` and `_burn` handle the minting and burning of shares. The constructor initializes the Vault with the address of the associated ERC20 token.

### Functions:

1. **deposit:** `function deposit(uint amount) external`
2. **withdraw:** `function withdraw(uint shares) external`

External State Variables:

- **token:** `IERC20 public immutable token`
- **totalSupply:** `uint public totalSupply`
- **balanceOf:** `mapping(address => uint) public balanceOf`
- **Vault Contract Address**`0x4Ac1d98D9cEF99EC6546dEd4Bd550b0b287aaD6D`


# Avalanche Subnet Setup for DeFi Empire

 Use the following details for the Avalanche Browser Extension connection:

## Connection Details

- **RPC URL:** `http://127.0.0.1:9650/ext/bc/AttG2UZBTuZjucVahYeMYRQmPSttSHqm8p6XMXcyo2uN72KUQ/rpc`
- **Funded Address:** `0x8db97C7cEcE249c2b98bDC0226Cc4C2A57BF52FC`
  - **Balance:** 1000000 DFE (10^18)
  - **Private Key:** `56289e99c94b6912bfc12adc093c9b51124f0dc54ac7a766b2bc5ccf558d8027`
- **Network Name:** `DeFiempire`
- **Chain ID:** `326932`
- **Currency Symbol:** `DFE`

## Getting Started

1. **RPC URL:** Use the provided RPC URL to connect to your Avalanche subnet.
2. **Funded Address:** Start with the funded address having a balance of 1000000 DFE.
3. **Private Key:** Use the private key for secure transactions and interactions.
4. **Network Name:** Identify your network as "DeFiempire" for easy recognition.
5. **Chain ID:** The chain ID is set to `326932` for your Avalanche subnet.
6. **Currency Symbol:** The native currency symbol is `DFE`.

Feel free to reach out if you have any questions or need further assistance. Happy building!


