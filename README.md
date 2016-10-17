# RetroluxReflector

A powerful reflection framework for Swift.

# Examples

For now, please refer to the unit tests for an example of how to use this framework.

Here's a simple example: [Example #1](https://github.com/izeni-team/RetroluxReflector/blob/069566ee3eedb62863757f2cbe5512d076bbc397/RetroluxReflectorTests/ReflectorTests.swift#L116).

And here's a complex example: [Example #2](https://github.com/izeni-team/RetroluxReflector/blob/069566ee3eedb62863757f2cbe5512d076bbc397/RetroluxReflectorTests/ReflectorTests.swift#L430).

# Installation

RetroluxSerializer is available through [Carthage](https://github.com/Carthage/Carthage). Since RetroluxSerializer uses Swift 3.0 and Xcode 8.0, you'll need to [install Carthage 0.18.0 or newer](https://github.com/Carthage/Carthage/releases). You can check which version you have by running `carthage version`.

Then, add this to your `Cartfile`:

```
github "izeni-team/RetroluxSerializer" ~> 0.1.0
```

Run `carthage update RetroluxSerializer` to compile the framework.

Then follow [these instructions](https://github.com/Carthage/Carthage#adding-frameworks-to-an-application) to link your application against the framework.
