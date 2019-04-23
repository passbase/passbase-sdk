# Passbase

[![CI Status](https://img.shields.io/travis/mattk90/Passbase.svg?style=flat)](https://travis-ci.org/mattk90/Passbase)
[![Version](https://img.shields.io/cocoapods/v/Passbase.svg?style=flat)](https://cocoapods.org/pods/Passbase)
[![License](https://img.shields.io/cocoapods/l/Passbase.svg?style=flat)](https://cocoapods.org/pods/Passbase)
[![Platform](https://img.shields.io/cocoapods/p/Passbase.svg?style=flat)](https://cocoapods.org/pods/Passbase)

## 1. Requirements

Xcode 10.2
Swift 4.2

## 2. Folder Structure

The directory is straightforward. We have all the classes and storyboards in the `Passbase/Classes` folder.
Resources, like e.g. images, font or GIFs are in the `Passbase/Resource` folder.
The `podspec` is in the `Metafiles` folder together with License and Readme.

## 3. Installation

Passbase is available through [CocoaPods](https://cocoapods.org). When you want to integrate it to another app, simply add the following line to your Podfile:

```ruby
# Add to the very top of Podfile
source 'https://github.com/CocoaPods/Specs.git'
source 'https://github.com/facetec/cocoapods-specs.git'

# Add after target xxx do
pod 'Passbase'
```

After that run the following command inside the folder structure from Terminal:

`pod install` 

For a detailed instruction how to make it run check the official integration or how to run and develop locally.

## 4. Developing

To run the SDK, please clone also [PassbaseiOSDemo](https://gitlab.com/passbase/passbase-ios-sdk-demo) project, integrate the SDK and run it locally there. Continue the guide to develop on the SDK there.


## 5. Deployment

Details how to deploy to Cocoapods
[Making a Cocoapod](https://guides.cocoapods.org/making/making-a-cocoapod.html)

## Author

Mathias J. Klenk, mathias@passbase.com

## License

Passbase is available under the Apache license. See the LICENSE file for more info.
