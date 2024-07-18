# ident
JavaScript library for ident.me
# main
```js
async function main(){
    const {ident} = require('./ident');
    const id= new ident();
    let req=await id.my_ip()
    console.log(req)
}
main()
```
