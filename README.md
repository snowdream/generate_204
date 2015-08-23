#generate_204
A Replacer of  the website http://clients3.google.com/generate_204

##Requirements
* Nodejs

##HOW TO
1. push the project to a nodejs host
2. start it with `npm start`
3. run the following command in the `adb shell` of the android device.     
```
settings put global captive_portal_server 50.horseluke.sinaapp.com
```

**Attention:** 50.horseluke.sinaapp.com is your captive_portal_server.

##Reference
1. [解决刷Android 5.0后wifi等网络连接处出现感叹号问题（Nexus 5测试通过）](http://www.iirr.info/blog/?p=1544)
2. [[转载]Android 5.0网络图标上的感叹号的解决办法](http://www.lynx.im/posts/1185.html)
3. [https://github.com/HorseLuke/drafts/tree/master/sinaapp_generate_204](https://github.com/HorseLuke/drafts/tree/master/sinaapp_generate_204)

##License
```
Copyright (C) 2015 Snowdream Mobile <yanghui1986527@gmail.com>

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