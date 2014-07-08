storage.js
==========

An Javascript Framework, to store information in localStorage on one Item. So you can add many of this Storage-Objects to one app without problems.

Usage
==========

1. create a new Storage object
```
var storage = new Storage();
var storage = new Storage('mysite.anotherStorageName'); //if you use other frameworks, use This
```
2. fill it with Data
```
storage.setValue('myKey',42);
```
3. read your stored data
```
var value = storage.getValue('myKey');
```
4. ask if a value with this key is stored
```
storage.hasValue('myKey');//true
storage.hasValue('myOtherKey');//false
```
5. remove an key-value-pair from the object
```
storage.removeValue('myKey');
```

LICENSE
==========
```
  Copyright 2014 Alrik Hausdorf
  
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
