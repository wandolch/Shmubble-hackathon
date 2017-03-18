# Place comments (Wikitude version)
#### You need [Node.js](https://nodejs.org/) v6.9.* to run.

Install ionic and cordova globaly in your machine and clone the project:
```sh
npm install -g ionic@2.2.1 cordova@6.5.0
git clone https://github.com/wandolch/placeComments.git placeComments
```

#### installing modules plugins and platforms
```sh
cd placeComments
npm install
ionic prepare
```

#### Android emulating
```sh
cordova emulate
```

#### Android building
```sh
ionic build android
```
Path to apk: placeComments\platforms\android\build\outputs\apk\android-debug.apk
To build or emulate app in android you need this sdk modules: http://i.imgur.com/a7BgegE.png

#### Ionic browser serve
```sh
ionic serve
```