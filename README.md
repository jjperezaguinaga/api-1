# HOPR API

A general purpose API for all HOPR related operations
## Faucet

Used for our CI/CD pipeline and other tasks.

- https://api.hoprnet.org/api/faucet/xdai/balance/native/get          <-- get the current balance of the faucet
- https://api.hoprnet.org/api/faucet/xdai/$ethAddress/native/default  <-- funds the $address with 0.1291 xDAI


## Balance

Used for our CI/CD pipeline and other tasks.

- https://api.hoprnet.org/api/balance/xdai/$ethAddress/native/get             <-- get the balance of an $address
- https://api.hoprnet.org/api/balance/xdai/$ethAddress/native/get?text=true   <-- get the balance of an $address (plain text)
