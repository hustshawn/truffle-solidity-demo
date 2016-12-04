truffle-solidity-demo
====

## Work flow ##
```
truffle compile
truffle migrate
```
### Console CLI ###
` truffle console`

```
var p = People.deployed()
p.abi
p.address
P.addPerson
p.addPerson("Shawn", "Zhang", 28)
p.getPeople().then(console.log)

>>>
[ [ '0x536861776e000000000000000000000000000000000000000000000000000000' ],
  [ '0x5a68616e67000000000000000000000000000000000000000000000000000000' ],
  [ { [String: '28'] s: 1, e: 1, c: [Object] } ] ]


var hex = "0x536861776e000000000000000000000000000000000000000000000000000000"
web3.toAscii(hex)
>>>
'Shawn\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000\u0000'

```