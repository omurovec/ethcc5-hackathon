# ERC-4626 Curve CryptoSwap Adaptation

## Overview

Forked CurveCryptoSwap2 pool from curvefi/curve-crypto-contract and adapted to work with ERC-4626.

Supported features:
- Exchange shares (ERC-4626) in pool
- Exchange underlying assets in pool
- Provide/Remove liquidity in shares (ERC-4626)
- Provide/Remove liquidity in underlying assets

## The Fun Stuff

Thanks to `vyperlang/titanoboa`, we created a Jupiter notebook that allows users to visualize changes in the pool and interact with it directly. No need to spin up a chain or deal with accounts, full on interpretation in python 😎



## Other forked code

- `ERC4626Mock.vy` forked from fubuloubu/ERC4626
- `ERC20.vy` forked from `vyperlang/vyper`
