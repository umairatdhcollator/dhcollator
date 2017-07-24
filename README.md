# bestcash-ios-client
iOS app for BestCash

If you are trying to run the project and dependancy pods (controls) are not on your machine, then follow the instructions to install pods and run project.

## Instructions

### Install CocoaPods

CocoaPods installs as a ruby gem. Installing the latest version is as simple as opening terminal and typing the following command:

```
[sudo] gem install cocoapods
```

The sudo prefix may not be necessary, depending on your system. This may take a while as it downloads the required Ruby packages to your machine.

The lines beginning with pod declare your project's external dependencies. 

### Install Pods

Close the project if you still have it open in Xcode. In terminal , go to the folder that includes Bestcash.xcodeproj and Podfile, then type the following command:

```
pod install
```

You'll see CocoaPods go to work, downloading the dependencies you declared, and also downloading all of their dependencies. The interesting part is at the end:

Generating support files
[!] From now on use `Bestcash.xcworkspace`.

### Open the Workspace

Instead of opening Bestcash.xcodeproj, find and open Bestcash.xcworkspace. You'll immediately notice CocoaPods downloaded all of your dependencies into a new project called Pods. 
