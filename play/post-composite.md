funcid                                       |(string)                     |describes either a bid ask `b`, a bid fill `B`, an ask `s`, or an ask fill `S`
txid                                         |(string)                     |the txid of the identifying order or fill
vout                                         |(number)                     |the vout value
amount                                       |(number)                     |the amount of the relevant bid/ask request/fill
bidamount/askamount                          |(number)                     |the total amount of the relevant bid or ask request
origaddress                                  |(string)                     |the address that made the original bid `b` or ask `s`
tokenid                                      |(string)                     |the tokenid for the relevant bid/ask request/fill
totalrequired                                |(number, `b` and `s` only)   |the total required before the offer is considered full ===?===
price                                        |(number)                     |the price per token, units are in the parent asset chain's coin