# base6665151
Full Base Activity Snapshot Script
snapshot = {
    "block": w3.eth.block_number,
    "txs": len(w3.eth.get_block("latest").transactions),
    "gas": w3.eth.gas_price
}
print(snapshot)
