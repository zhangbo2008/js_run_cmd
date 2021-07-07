# js_run_cmd

```
const { spawn } = require('child_process');
const ls = spawn('python', ['my_script.py','-p','11111111 23423 23423 432423']);
var a;
ls.stdout.on('data', (data) => {
  console.log(`${data}`,444);
  a=`${data}`
    console.log(a,444444)

});
```
