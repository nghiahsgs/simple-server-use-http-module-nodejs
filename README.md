# simple-server-use-http-module-nodejs
simple server use http module nodejs

```js

const http = require("http")
const server = http.createServer((req,res)=>{
    if(req.url=="/"){
        res.write("hello")
        res.end()
    }
})
server.listen(3000)
console.log("listening on port 3000")
```
