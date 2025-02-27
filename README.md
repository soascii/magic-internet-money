# Magic Internet Money

It's magic!

# Testing

```
yarn test
```

If the test are running super slow, be sure the `contracts-flat` contract artifacts are not in the `artifacts` folder.
When that's the case, run `yarn rebuild` and `yarn test` again.

# License

The Kashi code is licensed from BoringCrypto and is licensed only to Abracadabra.

## Deployments

## Avalanche

| Contract                    | Address                                    | Note                                  |
| --------------------------- | ------------------------------------------ | ------------------------------------- |
| **AVAX/USDT**               |                                            |                                       |
| AvaxUsdtCauldron            | 0x0a1e6a80E93e62Bd0D3D3BFcF4c362C40FB1cF3D | 85% LTV .5% initial 3% Interest       |
| AvaxUsdtProxyOracle         | 0x2cA12e0Ca5c2E1EE8DC18eAA0D24EEd647aE7531 | Using AvaxUsdtLPOracle                |
| AvaxUsdtLPOracle            | 0xEd5D79F369D878C9038ac156D7D71b6364756f8e | Using AvaxUsdtLPChainlinkOracleV1     |
| AvaxUsdtLPChainlinkOracleV1 | 0xd15f851A912e4Fa9947e6024f16f02Ef25Ff311B | Using AvaxUsdtOracleV1                |
| AvaxUsdtOracleV1            | 0xD43f26102b0671dCf8D6357aA2908D6cC80C0559 | Using Chainlink AVAX/USD and USDT/USD |
| AvaxUsdtSwapper             | 0x9Ca03FeBDE38c2C8A2E8F3d74E23a58192Ca921d | Liquidation Swapper                   |
| AvaxUsdtLevSwapper          | 0x8CEe5B335f450933b4720B5b84e6125d4225FB62 | Leverage Swapper                      |
| **MIM/AVAX**                |                                            |                                       |
| MimAvaxCauldron             | 0x2450Bf8e625e98e14884355205af6F97E3E68d07 | 85% LTV .5% initial 1% Interest       |
| MimAvaxProxyOracle          | 0x15f57fbCB7A443aC6022e051a46cAE19491bC298 | Using MimAvaxLPOracle                 |
| MimAvaxLPOracle             | 0x3e6ef9E97147C266c5bddeF03E7dfba7a167d853 | Using MimAvaxLPChainlinkOracleV1      |
| MimAvaxLPChainlinkOracleV1  | 0xE275ec65fDbB4ECF0142b393402eE90D47359fBf | Using MimAvaxOracleV1                 |
| MimAvaxOracleV1             | 0x4437DB9538eb74C7418a1668766536b279C52709 | Using Chainlink AVAX/USD and MIM/USD  |
| MimAvaxSwapper              | 0xBc00ca0d71231c5E23Ba90A90D8C5D9039C39614 | Liquidation Swapper                   |
| MimAvaxLevSwapper           | 0xBA7fd957ad9b7C0238E6E4413dbA69E83224a582 | Leverage Swapper                      |
