<!--suppress HtmlDeprecatedAttribute -->

<div align="center">
  <h1>KYVE + Cosmos SDK</h1>
</div>

![banner](https://github.com/kyve-org/assets/raw/main/banners/Cosmos.png)

## Configuration

```json
{
  "rpc": "https://proxy.kyve.network/cosmos",
  "github": "https://github.com/kyve-org/cosmos"
}
```

## Endpoints

- [`/cosmos/base/tendermint/v1beta1/blocks/{height}`](https://buf.build/cosmos/cosmos-sdk/docs/main:cosmos.base.tendermint.v1beta1#GetBlockByHeight)
- [`/cosmos/tx/v1beta1/txs/{hash}`](https://buf.build/cosmos/cosmos-sdk/docs/main:cosmos.tx.v1beta1#GetTx)
