NSString+HTML ![License MIT](https://go-shields.herokuapp.com/license-MIT-blue.png)
=============

Decode and encode HTML character entities.

<p align="center">
  <img src="http://s7.postimg.org/p06h2atzv/NSString_HTML.png" alt="NSString-Email" title="NSString-Email" width="246" height="369">
</p>

[![Build Status](https://api.travis-ci.org/NZN/NSString-HTML.png)](https://api.travis-ci.org/NZN/NSString-HTML.png)

## Adding NSString-Email to your project

### Cocoapods

[CocoaPods](http://cocoapods.org) is the recommended way to add `NSString-HTML` to your project.

* Add a pod entry for NSString-HTML to your Podfile:

```
pod 'NSString-HTML', :git => 'https://github.com/NZN/NSString-HTML'
```

* Install the pod(s) by running :

```
pod install
```

### Source files

Alternatively you can directly add source files to your project.

1. Download the [latest code version](https://github.com/NZN/NSString-HTML/archive/master.zip) or add the repository as a git submodule to your git-tracked project.
2. Open your project in Xcode, then drag and drop all files at `NSString-HTML` folder onto your project (use the "Product Navigator view"). Make sure to select Copy items when asked if you extracted the code archive outside of your project.

## Usage

```objective-c
NSString *encodedString = @"E-mail inv&#225;lido.";
NSString *decoded = [encodedString decodeHTMLCharacterEntities];
```

## License

This code is distributed under the terms and conditions of this [copyright license](LICENSE).

## Change-log

A brief summary of each NSString-HTML release can be found on the [wiki](https://github.com/NZN/NSString-HTML/wiki/Change-log).
