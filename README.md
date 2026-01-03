# base1lll
Detecting Empty Blocks on Base  Empty blocks can signal low activity periods.
block = w3.eth.get_block("latest")
if len(block.transactions) == 0:
    print("Empty block detected")
