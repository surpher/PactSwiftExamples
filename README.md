# pact-swift-examples
[![PactSwift demo projects](https://github.com/surpher/pact-swift-examples/actions/workflows/test_projects.yml/badge.svg)](https://github.com/surpher/pact-swift-examples/actions/workflows/test_projects.yml) 
[![PactSwift demo projects (macOS 11)](https://github.com/surpher/pact-swift-examples/actions/workflows/test_projects-macOS11.yml/badge.svg)](https://github.com/surpher/pact-swift-examples/actions/workflows/test_projects-macOS11.yml)
[![PactSwift Provider Verification](https://github.com/surpher/pact-swift-examples/actions/workflows/verify_provider.yml/badge.svg)](https://github.com/surpher/pact-swift-examples/actions/workflows/verify_provider.yml)

Example projects using [PactSwift][pactswift] framework.

Note that using Carthage may require you to use the [workaround script][carthage-script].

## What? How? Huh?

1. Clone this repo
2. cd into a project you're interested in
3. Fire up your Xcode 12+, 13+ or whatever your preference on Linux or provider side dev is
4. Wait for either SPM dependencies to resolve, or run `carthage update --use-xcframeworks` if the project is set up with a `Cartfile` (mind the issues with Silicon platform)
5. Check the `../.github/workflows/` for any pointers, ideas and caveats for building, setting things up, running...
6. Run tests
7. Happy days! 🎉

## Disclaimer

The code in this repository does not represent good programming practices!

This repository is used solely to demonstrate the minimal effort required to set up and use [PactSwift][pactswift] framework.

## Licence

[MIT](LICENSE.md)

[pactswift]: https://github.com/surpher/pact-swift
[carthage-script]: carthage
