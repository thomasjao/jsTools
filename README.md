# JavaScript Tools
## records useful tools written in JavaScript

1. convert epoch used in Taiwan to AD  將中華國國紀元改成西元紀元
2. 去掉數字中的敝節號


```javascript
function toNumber( numString ) {
    if ( numString.contains('.') ) {
        return parseFloat( numString.replace(/,/g, ''));        // deem as a real number string
    } else {
        return parseInt( numString );                           // deam as an integer number string
    }
}
```
