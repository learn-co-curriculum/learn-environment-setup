---
tags: setup, environment, bash
languages: bash
---

# Setup

## Setting Up Your Environment for Learn.co

You need a proper development environment to learn to code, whether you're learning Web Development, with a focus on the Ruby, or Python, or Javascript, or Mobile Development, with a focus on Objective-C and iOS or Java and Android. This guide is going to go through the manual steps you can take to setup your environment to work with Learn.

## Automating the Setup with Environmentalizer

Normally we setup your computer using the [Learn OSX Companion application](https://flatironschool-static.s3.amazonaws.com/learn.zip). That is definetly the easiest way to setup your computer.

That application actually just uses a BASH script called [Environmentalizer](https://github.com/learn-co-curriculum/setup-with-environmentalizer).

You can choose to run that script manually. Or you can proceed with this guide to install the requirements as you see fit.

## Requirements

In general the list of requirements for using Learn are:

1. A [GitHub](https://github.com/join) account. You can use the Free account on GitHub, you won't need private repositories at this point.

2. You should have your GitHub account tied to your shell preferably via [SSH](https://help.github.com/articles/generating-ssh-keys/) but you can use [OSX Keychains](https://help.github.com/articles/updating-credentials-from-the-osx-keychain/).

3. You'll need a way to compile software. If you're on OSX, the best thing you can do is use [XCode](https://developer.apple.com/xcode/downloads/) and [XCode Command Line Tools](https://developer.apple.com/library/ios/technotes/tn2339/_index.html) [download for 10.10 XCode 6.3.1](http://adcdownload.apple.com/Developer_Tools/Command_Line_Tools_OS_X_10.10_for_Xcode_6.3.1/commandlinetoolsosx10.10forxcode6.3.1.dmg) to get gcc.

4. You'll probably need a package manager of some sort. We love [Homebrew](http://brew.sh/) on OSX.

5. You're going to need [git](http://git-scm.com/downloads). It generally comes with most modern operating systems, can be installed via Homebrew and apt-get and most package managers easily. 

6. A Ruby Interpreter. Even for Mobile Development with iOS and XCode, even for Web Development with Python or Javascript, because so much tooling is built in Ruby, having a working interpreter is a great idea. If you can type `ruby -v` and not get an error, you probably have enough of a Ruby environment.

If you are studying Web Development with Ruby, such as the Rails framework, you definetly need a great Ruby environment. We love [RVM](https://rvm.io/) for managing Ruby versions and environments.

7. The `learn` gem. Simply type: `gem install learn-co` or if you get a permissions error, `sudo gem install learn-co`. Then type in `learn` to configure it with your github account and you're all set.

8. A Text Editor. For iOS, XCode is a great IDE. But why not install the free editors [Sublime Text](http://www.sublimetext.com/) and [Atom](https://atom.io/)

Those are the absolute requirements.

### Additional Requirements for iOS and XCode

1. You need to install the Learn-XCPretty gem with `gem install learn-xcpretty` or if you get permission errors, `sudo gem install learn-xcpretty`.

### Additional Requirements for Ruby on Rails

If you're planning on working with the Ruby on Rails framework. We additionally suggest you setup at least:

1. The easiest free database to use with Rails is [SQLite](https://www.sqlite.org/download.html. You can install it with `brew install sqlite` or an equivalent package manager or install it yourself from source.

2. Postgres is a great idea to have setup too and the [Postgres.app](http://postgresapp.com/) makes it easy.

3. You probably want to install LibXML2 via Homebrew (`brew install libxml2`) and then test it by trying to install the gem [Nokogiri](http://www.nokogiri.org/tutorials/installing_nokogiri.html#mac_os_x) with `gem install nokogiri`

### Help and Advice

Since you're reading this guide you probably have some experience with environment setups, if not, please use the Learn Companion app to automate your setup. We also think the [RailsApps Install Guides](http://railsapps.github.io/installrubyonrails-mac.html) are great. [InstallRails](http://installrails.com/) isn't bad either.

Good luck!!!
