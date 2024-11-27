# Aave Token

## Proxy Contract Information
- **Contract Name:** InitializableAdminUpgradeabilityProxy
- **Compiler Version:** v0.6.10+commit.00c0fcaf
- **Optimization Enabled:** Yes with 200 runs
- **Contract Address:** 0x7Fc66500c84A76Ad7e9c93437bFc5Ac33E2DDaE9
- **EVM Version:** istanbul
- **Chain:** Ethereum Mainnet

## Implementation Contract Information
- **Contract Name:** AaveTokenV3
- **Compiler Version:** v0.8.20+commit.a1b79de6
- **Optimization Enabled:** Yes with 200 runs
- **Contract Address:** 0x5D4Aa78B08Bc7C530e21bf7447988b1Be7991322
- **EVM Version:** paris
- **Chain:** Ethereum Mainnet

## Source Code Structure
```
└── proxy
    ├── contracts
    │   └── interfaces
    │       ├── IERC20.sol
    │       ├── IERC20Detailed.sol
    │       ├── ITransferHook.sol
    │   └── open-zeppelin
    │       ├── Address.sol
    │       ├── BaseAdminUpgradeabilityProxy.sol
    │       ├── UpgradeabilityProxy.sol
    │       ├── BaseUpgradeabilityProxy.sol
    │       ├── Proxy.sol
    │       ├── Context.sol
    │       ├── ERC20.sol
    │       ├── SafeMath.sol
    │       ├── InitializableAdminUpgradeabilityProxy.sol
    │       ├── InitializableUpgradeabilityProxy.sol
    │   └── token
    │       ├── AaveToken.sol
    │       ├── LendToAaveMigrator.sol
    │   └── utils
    │       └── VersionedInitializable.sol
    │       └── DoubleTransferHelper.sol
    │       └── MintableErc20.sol
    │       └── MockTransferHook.sol
└── implementation
    └── src
        ├── AaveTokenV3.sol
        ├── BaseAaveTokenV2.sol
        ├── BaseDelegation.sol
        ├── utils
        │   ├── VersionedInitializable.sol
        │   ├── EIP712.sol
        │   ├── SafeCast72.sol
        ├── BaseAaveToken.sol
        ├── interfaces
        │   ├── IGovernancePowerDelegationToken.sol
        ├── DelegationAwareBalance.sol
    └── lib
        └── openzeppelin-contracts
            └── contracts
                └── utils
                    ├── cryptography
                    │   ├── ECDSA.sol
                    ├── Strings.sol
                    ├── ShortStrings.sol
                    ├── Context.sol
                    ├── math
                    │   ├── Math.sol
                    │   ├── SignedMath.sol
                    ├── StorageSlot.sol
                └── interfaces
                    ├── IERC5267.sol
                └── token
                    └── ERC20
                        └── IERC20.sol
                        └── extensions
                            └── IERC20Metadata.sol

```