# Moccasin Project

🐍 Welcome to your Moccasin project!

## Quickstart

```bash
mox init
mox run deploy
```

_For documentation, please run `mox --help` or visit [the Moccasin documentation](https://cyfrin.github.io/moccasin)_

# Stablecoin

1. Users can deposit $200 of ETH
2. They can then mint $50 of stablecoin
    1. This means they will have a 4/1 ratio of collateral to stablecoin (200/50 == 4/1)
    2. We will set a required collateral ratio of 2/1
3. If the price of ETH drops, for example to $50, others should be able to liquidate those users!