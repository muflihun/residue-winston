﷽

# Winston Transport for Residue

For options, please refer to [Residue for Node.js](https://github.com/muflihun/residue-node#connectoptions)

Simply enable the transport on winston

```
const Residue = require('residue-winston');
const logger = winston.createLogger({
  level: 'silly',
  transports: [
    new Residue({
        url: 'localhost:8777',
        logger_id: 'sample-app'
    })
  ]
});
```

## License
```
Copyright 2017-present Muflihun Labs
Copyright 2017-present @abumusamq

https://github.com/muflihun/
https://muflihun.github.io/
https://muflihun.com/

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
