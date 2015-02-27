# financial-api

An Opendata financial API that allows you to programatically access structured financial information.

## Resources (WIP)

### Investments
<!-- API prosper -->

Lists investments for the authenticated user. It should include some kind of status per entry such (pending, cancelled, completed, etc).

### Loans
<!-- API prosper -->

List of loans that the platform provides you with.

### Notes
<!-- API prosper -->

All notes for the authenticated user - showing user specific debits and credits

## Inspirational links

- [Prosper](https://api.prosper.com/)
- [Kiva - person to person micro-lending](http://build.kiva.org/docs/)
- [Ribbon BIN list](http://bins.ribbon.co/)
- [OpenBank API](https://github.com/OpenBankProject/OBP-API/wiki/Sandbox)
- [BankImport](https://www.bankimport.com/?i18n_locale=en)
- [Markit On Demand](https://www.markit.com/product/markit-on-demand)

## Example Endpoint documentation

Below you can find an example on how to document a certain API. Make sure you list all the possible details to make it clear what the API and its endpoints contain.


### Account information


URL: `https://api.prosper.com/accounts/{:account_id}`

#### Entry points

|Name   	|Description   	|Structure   	|Type   	|Required   	|
|---	|---	|---	|---	|---	|
|`customer_name`   	|Customer name   	|`John F. Knope`   	|`string`   	|Yes   	|
|`acc_number`   	|Customer account number   	|`1234567890`   	|`integer`   	|Yes   	|
|`amount`   	|Amount of account value   	|`1234.56`   	|`string`   	|No   	|


#### Endpoints

|Name   	|Description   	|Structure   	|Type   	|
|---	|---	|---	|---	|
|`customer_name`   	|Customer name   	|`John F. Knope`   	|`string`   	|
|`acc_number`   	|Customer account number   	|`1234567890`   	|`integer`   	|
|`amount`   	|Amount of account value   	|`1234.56`   	|`string`   	|
