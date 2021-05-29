## Installation

```bash
$ npm install knights-canvas
```

## Example GoodBye

```js
const ling = require("knights-canvas"),
const  fs = require('fs');

const image = await new ling.Goodbye()
    .setUsername("LING MO")
    .setGuildName("Frontline")
    .setGuildIcon("https://pandal.page/imgs/imgs/608d550e2075c.jpg")
    .setMemberCount("404")
    .setAvatar("https://pandal.page/imgs/imgs/60960b4ce3129.jpg")
    .setBackground("https://pandal.page/imgs/imgs/60a3cf9d08a5c.jpg")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/tmp/swelkom.png', data)
 
```
## IMAGE 
<img src="https://pandal.page/imgs/imgs/60b0ad54166ef.jpg" height="145"></img>

## Credits

Made by [LINZ](https://github.com/Not-found-squad) with ❤️  
Thanks to [LEN](https://github.com/lenz-cmd) for his help !
# knights-canvas
