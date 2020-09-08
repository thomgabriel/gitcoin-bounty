# satoshi

Manipulate satoshi-related prices in Node, simple and sweet 💵₿🍬

## Install

<img align="center" src="img/logo-black.png" height="50px" alt="OpenBits logo" title="OpenBits Logo"> This package is only served through OpenBits. 

To install OpenBits run: 

```shell
npm install openbits
```

Then login into openbits by following these <a href="https://www.npmjs.com/package/openbits" target="_blank">instructions</a>.

When OpenBits is set up, then install satoshi as followings: 

```shell
openbits install satoshi
```

## Usage

Import the package: 

```Javascript
import 'satoshi';
```

Create a bat-thing by doing the following:

```javascript
const to_usd = satoshi.to_fiat(984223); // satoshi to usd
console.log(to_usd);

// will print satoshis in usd

const to_brl = satoshi.to_fiat(18923, 'BRL') // satoshi to reais
console.log(to_brl);

// will print satoshis in brl
```

## Contribute

Feel free to become a collaborator.

