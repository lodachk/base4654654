# base4654654
Monitoring NFT Mint Events
events = nft.events.Transfer.createFilter(
    fromBlock="latest",
    argument_filters={"from": "0x0000000000000000000000000000000000000000"}
)
print(events.get_new_entries())
