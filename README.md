# learningJS
```
const request = require('request');

const options = {
    url :"https://api.openweathermap.org/data/2.5/weather?zip=92617,us&appid=b88694450f8e2f38853eb3ed89d3f290"
};

// const options = {
//     url:'http://172.16.16.200/api/slot/0/sysInfo/device',
//     headers: {
//         'Content-Type': 'application/json',
//         'Accept': 'vdn.dac.v1'
//     }
// };

request(options, function(error, response, body){
    console.log(response.statusCode);
    console.log(body);
});
```
